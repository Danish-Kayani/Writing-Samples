# JSON vs XML: How APIs Share Data
A beginner-friendly comparison of two common data formats used in APIs.

## Introduction
When two applications interact through an API, they require a common language to exchange information. Most APIs use either **JSON** (JavaScript Object Notation) or **XML** (eXtensible Markup Language) to exchange data. 
This guide breaks down what each format looks like, how they differ, and why developers choose one over the other. 

## Quick Refresher: What is an API 
- An **API (Application Programming Interface)** allows software systems to communicate with each other.  
- Think of it like a restaurant menu: you (the client) order a dish (request), and the kitchen (server) sends it back (response).  
- JSON and XML are simply two ways the server can describe what is on the plate.
## Example: A Simple API Response 
Imagine you ask a Book API for details about "The Great Gatsby". 
JSON's response should be:

```json
{
  "title": "The Great Gatsby",
  "author": "F. Scott Fitzgerald",
  "year": 1925
}
```
And here’s the same data in XML:
<book>
 <title></title>

