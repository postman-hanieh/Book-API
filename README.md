# Simple Book API – Postman Collection

This repository contains a **Postman collection** for testing the Simple Book API.
The collection includes common API operations such as checking API status, retrieving books, placing orders, updating orders, and deleting them.

---
##  Test Scenarios
- Verify API status endpoint
- Validate book retrieval by ID
- Verify order creation with valid data
- Negative test for invalid book ID

##  Features Covered

* **API Health Check** (`GET /status`)
* **List All Books** (`GET /books`)
* **Get Book by ID** (`GET /books/:bookId`)
* **Create an Order** (`POST /orders`)
* **Get All Orders** (`GET /orders`)
* **Get a Single Order** (`GET /orders/:orderId`)
* **Update an Order** (`PATCH /orders/:orderId`)
* **Delete an Order** (`DELETE /orders/:orderId`)
* **Register API Client** (`POST /api-clients`)

---

##  Included Tests

Some requests include Postman tests, such as:

* Status code validation
* JSON field validation
* Logging response data

---

##  Structure

```
Simple-Book-API-Postman/
│── Simple Book API.postman_collection.json
│── README.md
└── (optional) environment.json
```

---

##  Notes

* You must register an API client to receive an **access token** before making order-related requests.
* Some optional query parameters (like `type` and `limit` for book listing) are provided but disabled by default.

---


