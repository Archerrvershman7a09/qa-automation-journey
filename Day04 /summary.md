# Day 04 Summary

## What I learned

Today I learned the basics of HTTP and REST API.

HTTP is the communication protocol between client and server.

REST API allows different systems to exchange data using HTTP methods like GET, POST, PUT, PATCH, and DELETE.

## Key Concepts

### HTTP Methods

- GET: get/read data
- POST: create new data
- PUT: fully update data
- PATCH: partially update data
- DELETE: delete data

### Status Codes

- 200 OK: request was successful
- 201 Created: new resource was created
- 400 Bad Request: request data is incorrect
- 401 Unauthorized: authentication is missing or invalid
- 404 Not Found: resource or endpoint does not exist
- 500 Internal Server Error: server has a problem

### Request Structure

A request can include:

- Method
- URL / Endpoint
- Headers
- Query Parameters
- Body

### Response Structure

A response can include:

- Status Code
- Headers
- Body

### Headers

Headers provide additional information about the request or response.

Examples:

- Content-Type
- x-api-key
- Authorization

### Body

Body contains the data sent to the server or returned from the server.

Usually API body is written in JSON format.

### Query Parameters

Query parameters are extra values in the URL after `?`.

Example:

```http
GET /api/users?page=2

### What was difficult

The most difficult part was understanding the difference between headers, body, and query parameters.

Now I understand it this way:

Headers = additional request information
Body = data sent or received
Query Parameters = extra values in the URL

### Hours spent: 3 hours

### Questions

Should I create a ReqRes API key for practical testing?
Is my understanding of GET vs POST correct?
Should I practice these requests in Postman next?
