# Day 04: ReqRes API Examples

## What is ReqRes?

ReqRes is a hosted REST API that can be used for testing API requests, QA automation, Postman practice, and Playwright API testing.

I used ReqRes documentation to understand GET and POST request examples.

Important note:
Current ReqRes documentation says that requests require `x-api-key` header.

---

## Example 1: GET Request

### Purpose

Get a list of records from the API.

### Method

GET

### Example Request

```bash
curl "https://reqres.in/api/collections/products/records" \
  -H "x-api-key: YOUR_API_KEY" \
  -H "X-Reqres-Env: prod"
