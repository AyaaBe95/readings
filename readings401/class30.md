# Hashtables

- Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects.
- Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
- Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## What Are they?
- The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value. 
- A hash is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.

![scanner](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Hash_table_3_1_1_0_1_0_0_SP.svg/1200px-Hash_table_3_1_1_0_1_0_0_SP.svg.png)


## Advantages:
- hash map has O(1) access.

## Structure:

### Hashing
- hash code turns a key into an integer. 

### Creating a Hash
- It  is created from an array.
- turn  “key” into a numeric number value.

### Collisions
- It occurs when more than one key hashes to the same index in an array.
- Collisions are solved by changing the initial state of the buckets. Instead of starting them all as null we can initialize a LinkedList in each one!
-

## Hash maps do this to store values:
- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- store the key with the value by appending both to the end of a linked list

## Hash maps do this to read value:
- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- use the array index to access the short LinkedList representing a bucket
- search through the bucket looking for a node with a key/value pair that matches the key you were given

## Internal Methods:
- Add()
- Find()
- Contains()
- GetHash()





