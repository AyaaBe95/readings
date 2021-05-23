# Serverless 

## What it is?
- It is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers.
- Its price is based on the number of executions rather than pre-purchased compute capacity.
- Serverless applications are event-driven cloud-based systems where application development rely solely on a combination of third-party services, client-side logic and cloud-hosted remote procedure calls (Functions as a Service).

## Traditional vs. Serverless Architecture

- Traditional: applications have run on servers which you had to patch, update, and continuously look after late nights and early mornings due to all the unimaginable errors that broke your production.
- Serveless: users are no longer need to worry about the underlying servers.beacuse they are not managed by users anymore and with management out of the picture the responsibility falls on the Cloud vendors.

### Pricing
- Serverless is reduced cost
* The winner here is serverless Architecture.

### Networking
- The downside is that Serverless functions are accessed only as private APIs. To access these you must set up an API Gateway.
* The winner here is Traditional Architecture.

### 3rd Party Dependencies
- The winner here is based on the context. For simple applications with few dependencies, Serverless is the winner; for anything more complex, Traditional Architecture is the winner.

### Environments
- Users  no longer need to set up dev, staging, and production machines.
* The winner here is Serverless Architecture.

### Timeout
- With Serverless computing, there’s a hard 300-second timeout limit. Too complex or long-running functions aren’t good for Serverless.
* The clear winner here is Traditional Architecture.

### Scale
- Scaling process for Serverless is automatic and seamless, but there is a lack of control or entire absence of contro
* It’s a tie between Serverless and Traditional Architecture.

## Functions as a Service (FaaS)
- FaaS is an implementation of Serverless architectures where engineers can deploy an individual function or a piece of business logic.

### Principles of FaaS:
- Complete management of servers
- Invocation based billing
- Event-driven and instantaneously scalable

### Key properties of FaaS:
- Stateless
- Ephemeral
- Event-triggered
- Scalable by default
- Fully managed by a Cloud vendor

## The Serverless App
![scanner](https://hackernoon.com/hn-images/1*TIrjN7EjLUVJmJ6YvHR7Dg.png)

- A Serverless solution consists of a web server, Lambda functions (FaaS), security token service (STS), user authentication and database.

1. Client Application — The UI of your application is rendered client side in Modern Frontend Javascript App which allows us to use a simple, static web server.
2. Web Server — Amazon S3 provides a robust and simple web server. All of the static HTML, CSS and JS files for our application can be served from S3.
3. Lambda functions (FaaS) — They are the key enablers in Serverless architecture. Some popular examples of FaaS are AWS Lambda, Google Cloud Functions and Microsoft Azure Functions.
4. Security Token Service (STS) — generates temporary AWS credentials (API key and secret key) for users of the application. 
5. User Authentication — AWS Cognito is an identity service which is integrated with AWS Lambda.
6. Database — AWS DynamoDB provides a fully managed NoSQL database. DynamoDB is not essential for a serverless 


