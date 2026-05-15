# Day 04: HTTP and REST API Cheatsheet

## 1. What is HTTP?

HTTP means HyperText Transfer Protocol.

It is a communication protocol between client and server.

Simple flow:

Client sends Request → Server returns Response

Example:
A browser or application sends a request to the backend API, and the backend returns data, success message, or error.

---

## 2. What is REST API?

REST API is a way for applications to communicate using HTTP methods.

API allows frontend, backend, mobile apps, and other systems to exchange data.

Example:

- Frontend asks backend for user data
- Backend returns user data as JSON

---

## 3. HTTP Methods

| Method | Meaning | Example |
|---|---|---|
| GET | Get data | Get user list |
| POST | Create new data | Create a new user |
| PUT | Fully update data | Replace user profile |
| PATCH | Partially update data | Change only user name |
| DELETE | Delete data | Delete user |

Simple memory formula:

- GET = read
- POST = create
- PUT = replace
- PATCH = partially update
- DELETE = remove

---

## 4. Status Codes

| Status Code | Meaning | Simple Explanation |
|---|---|---|
| 200 OK | Success | Request worked successfully |
| 201 Created | Created | New resource was created |
| 400 Bad Request | Client error | Request data is incorrect |
| 401 Unauthorized | Auth error | Authentication is missing or invalid |
| 404 Not Found | Not found | Resource or endpoint does not exist |
| 500 Internal Server Error | Server error | Backend/server has a problem |

Simple memory formula:

- 2xx = Success
- 4xx = Client error
- 5xx = Server error

---

## 5. Request Structure

A request usually includes:

- Method
- URL / Endpoint
- Headers
- Query Parameters
- Body

Example:

```http
POST /api/users HTTP/1.1
Content-Type: application/json
x-api-key: YOUR_API_KEY

{
  "name": "Bata",
  "job": "QA Engineer"
}
