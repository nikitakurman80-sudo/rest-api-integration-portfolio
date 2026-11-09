# REST API Integration & Troubleshooting

### Technical Implementation Specialist | Portfolio Project

## Project Overview

This project demonstrates practical REST API integration testing, automated validation, authentication header testing, and API troubleshooting using Postman.

The project was developed using public testing APIs to simulate common SaaS integration scenarios.

## Technologies & Tools

- Postman
- REST API
- JSON
- JavaScript (Postman Tests)
- HTTP Methods: GET, POST, PUT, PATCH, DELETE
- Environment Variables
- Bearer Token Authentication Headers
- Postman Collection Runner

## API Testing Scenarios

| Test Scenario | HTTP Method | Expected Status |
|---|---|---|
| Retrieve Users | GET | 200 OK |
| Create User | POST | 201 Created |
| Update User | PUT | 200 OK |
| Partial Update | PATCH | 200 OK |
| Delete User | DELETE | 200 OK |
| Invalid User ID | GET | 404 Not Found |
| Bearer Token Header Test | GET | 200 OK |

## Automated Testing

Developed 23 automated checks using Postman to validate HTTP status codes, JSON response data, resource identifiers, and authentication header transmission.

The collection supports automated execution through Postman Collection Runner.

## API Troubleshooting

**Scenario: 404 Not Found**

Investigated an API request targeting a non-existent user resource.

- Verified the endpoint and HTTP method.
- Checked the requested resource ID.
- Validated the expected HTTP 404 response.
- Confirmed that the API handled the missing resource as expected.

## Environment Configuration

Configured a reusable `base_url` environment variable to simplify API endpoint management.

## Project Deliverables

- Exported Postman Collection
- Automated API Test Scripts
- API Error Handling Scenarios
- Collection Runner Test Execution
- Technical Documentation

## Project Limitations

This is a personal technical demonstration using public test APIs. JSONPlaceholder simulates write operations without permanently saving changes. The Bearer Token test demonstrates header transmission rather than production-grade authentication validation.

## Skills Demonstrated

REST API Testing | API Troubleshooting | HTTP Status Codes | JSON Validation | Postman Automation | Environment Configuration | Technical Documentation

---

**Author:** Mykyta Kurman

**Location:** Ontario, Canada

**Career Focus:** Technical Implementation Specialist

## Test Evidence

**### Postman Collection
![Collection Overview](screenshots/collection-overview.png)

### Automated API Tests
![Automated Tests](screenshots/automated-tests.png)

### Collection Runner Results
![Collection Runner](screenshots/collection-runner.png)**
