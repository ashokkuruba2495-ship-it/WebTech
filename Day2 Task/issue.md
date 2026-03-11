# Day 2 – Issue & Fix

## Issue: Postman ENOTFOUND Error

While testing the API using Postman, the request failed and showed the following error:

```
Could not send request Error: getaddrinfo ENOTFOUND postman-library-api.glitch.me
```

## Reason

This error occurs when Postman cannot resolve the domain name of the API server.

The main reasons can be:

- The API endpoint URL is incorrect.
- The domain server is not available.
- Internet or DNS connection issue.
- The API service is temporarily down.

## Error Log

Postman console showed:
```
GET https://postman-library-api.glitch.me/⁠�
Error: getaddrinfo ENOTFOUND postman-library-api.glitch.me
```

This means Postman could not find the server address for the requested API.

---

## Solution

1. Check the API URL carefully.
2. Ensure the internet connection is working.
3. Try opening the API URL in a browser.
4. If the API server is down, wait and try again later.
5. Use a valid API endpoint.

Example working endpoint:

---

## Screenshot of Error

![Postman ENOTFOUND Error](./postman-error.png)

---

## Outcome

After verifying the API endpoint and internet connection, the request was successfully sent from Postman and the API response was received correctly.
