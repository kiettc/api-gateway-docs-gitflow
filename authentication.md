# Authentication Guide

This API Gateway supports API Key based authentication.

---

## Authentication Methods

### 1. API Key (Header)

Send your API key using the request header:

```http
GET /api/orders
Authorization: ApiKey YOUR_API_KEY
