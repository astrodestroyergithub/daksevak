# DakSevak API Testing Guide

Welcome to DakSevak! Follow these steps to start testing your APIs in seconds.

## Step 1: Choose Your Request Method & URL
1. Select the HTTP method (`GET`, `POST`, `PUT`, `DELETE`, etc.) from the dropdown next to the URL input.
2. Enter your API endpoint URL in the input bar (e.g., `https://jsonplaceholder.typicode.com/posts/1`).

## Step 2: Configure Headers & Parameters
- **Params Tab:** Add URL query parameters. They automatically append to your request URL.
- **Headers Tab:** Add authentication tokens (`Authorization: Bearer <token>`) or content types (`Content-Type: application/json`).
- **Body Tab:** For `POST`/`PUT` requests, select your body format (`JSON` or `Raw`) and enter your payload.

## Step 3: Send & Inspect
1. Click the **Send** button.
2. View the real-time **Status Code** (e.g., `200 OK`), **Response Time** (e.g., `142 ms`), and **Payload Size**.
3. Toggle between **Pretty** (syntax-highlighted JSON), **Raw**, and **Preview** tabs to inspect the response.

---

## Sample APIs & Public Endpoints to Test

You can copy and paste these public test endpoints directly into DakSevak to verify everything works:

1. **Get All Posts (GET)**
   - URL: `https://jsonplaceholder.typicode.com/posts`
   - Description: Returns a list of 100 sample JSON posts.

2. **Get a Single User (GET)**
   - URL: `https://jsonplaceholder.typicode.com/users/1`
   - Description: Returns user profile details.

3. **Create a New Post (POST)**
   - URL: `https://jsonplaceholder.typicode.com/posts`
   - Body (JSON):
     ```json
     {
       "title": "Testing DakSevak",
       "body": "API testing made effortless.",
       "userId": 1
     }
     ```