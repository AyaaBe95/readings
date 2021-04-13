# HTTP Request Lifecycle

![scanner](https://budjb.github.io/http-requests/latest/images/filter-lifecycle.png)


## Step 1: Local Processing
 - the browser extracts the "scheme"/protocol 
 - Now that the browser has the intended hostname for the request, it needs to resolve an IP address
## Step 2: Resolve an IP
- If the cache lookup fails (we will assume it does), your browser fires off a DNS request using UDP3.
   * The DNS request contains the preconfigured IP for your DNS server and your return IP in its header.
- Your request will now have to travel many network devices to reach its target DNS server.
- Once your request arrives at your configured DNS server, the server looks for the address associated with the requested hostname.
- If the response makes it back,the requesting client now has a target IP

## Step 3: Establish a TCP Connection
- The client initiates the active open by sending a SYN7 "control"8 packet to the server.
- The server responds with a SYN-ACK9 message.
- the client sends an ACK10 message back to the server with a sequence number equal to x+1, which should match the SYN-ACK message’s acknowledgment number
 
## Step 4: Send an HTTP Request
- The request is made up of a "request line", request header, and a body.
- Once the HTTP request is sent, it follows a similar routing procedure.
- Once the server receives the request, processes it, and finds the resource being requested, it generates an HTTP response.
- Once the response is generated, the server responds to the request. At the TCP layer.

## Step 5: Tearing Down and Cleaning Up
- Once the response has been fully delivered, the client sends a FIN packet at the TCP level, to which the server responds with an ACK, and then generally sends a FIN of its own, which the client responds to with its own ACK signal.
- browser begins processing what it has received. 
