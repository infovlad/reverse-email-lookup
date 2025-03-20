# Reverse Emails API

## Try the Free Demo
🚀 **[Try a Free Email Lookup](https://www.reversemails.com/demo)** – Test our service with a free lookup and see how it works!

## Introduction
The **Reverse Emails API** is a powerful service that allows you to perform reverse email lookups to find LinkedIn profiles associated with a given email address. This API is designed for developers, businesses, and researchers who need to enrich their contact data with LinkedIn profile information.

### Features:
- Secure HTTPS requests
- Fast and reliable email lookup
- Standardized API response codes
- Easy authentication with API keys
- No rate limits for requests

## API Documentation

### Base URL
All API requests must be made over **HTTPS** to ensure data security and privacy. The base URL for the API is:

```
https://api.reversemails.com/v1
```

### Authentication
Authentication is required for all API requests. You must include your API key as a query parameter:

```
https://api.reversemails.com/v1/lookup/?email=example@example.com&apikey=YOUR_API_KEY
```

> **Note:** Replace `YOUR_API_KEY` with your actual API key.

#### Reset API Key
If your API key has been compromised, you can reset it through your account settings.

### Making Requests
You can make a request to the Reverse Emails API using `curl`:

```sh
curl -L 'https://api.reversemails.com/v1/lookup/?email=example@example.com&apikey=YOUR_API_KEY' \
-H 'Accept: application/json'
```

### Response Codes
The API returns standard HTTP response codes:

| Status Code | Meaning |
|------------|---------|
| **200** | Successful request (even if no user is found) |
| **400** | Bad request - check the parameters |
| **401** | Unauthorized - missing or invalid API key |
| **5xx** | Server error |

> **Important:** A `200` response indicates that the request was processed, even if no LinkedIn profile was found. Credits will still be deducted for each processed request.

### Rate Limits
There are currently **no rate limits** imposed on API requests.

---

## Contact & Support
For any issues, feature requests, or API-related inquiries, please reach out to our support team at **support@reversemails.com**.
