# Wheel the World — Accessibility Data Catalog API

A REST API that gives third-party partners access to Wheel the World's catalog of accessibility information.

**Base URL:** `https://api.wheeltheworld.com/public-api`

> **Beta notice:** This API is currently in beta. Endpoints, parameters, and response schemas may change at any time without prior notice. Backwards compatibility is not guaranteed until a stable release is announced.

---

## Getting Access

Access to the API is granted on request. To obtain credentials reach out to our customer service team to get registered as a REST API Client.

Keep your token secure and do not expose it in client-side code or public repositories. Wheel the World reserves the right to rotate or revoke tokens at any time.

---

## Authentication

Every request must include an `Authorization` header using the **Bearer** scheme:

```
Authorization: Bearer <your_token>
```

Requests with a missing or invalid token receive a `401 Unauthorized` response.

---

## API Reference

The full specification — endpoints, request parameters, response schemas, and error codes — is defined in [`openapi.yaml`](./openapi.yaml).

Import it into any OpenAPI-compatible tool (e.g. [Swagger UI](https://swagger.io/tools/swagger-ui/)) to explore and test the API.
