# Secure Citizen Application Intake API (Flask + PyTest)

A lightweight RESTful service demonstrating secure API design, automated test suites, and strict input validation for public sector digital services.

## Key Features
- **Defensive Design**: Regex-based National Insurance Number validation, strict type-checking, and parameterized payload enforcement.
- **Security Baseline**: Header-based API authentication (`X-API-KEY`) and automated injection of security headers (`X-Content-Type-Options: nosniff`, `X-Frame-Options: DENY`, `Content-Security-Policy`).
- **Automated Testing Suite**: Full test coverage using `pytest` validating authentication, status codes (`201`, `400`, `401`, `404`), and schema failure paths.

## Setup & Running

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt# secure-application-intake-api

### 🤖 AI Collaboration Disclaimer
This project was developed as a hands-on learning lab exploring front-end web architecture and vanilla development. Code snippets, boilerplate scaffolding, and architectural patterns were generated in collaboration with Gemini (Google AI) acting as an interactive technical mentor. All implementations, file structures, debugging, and styling integrations were manually reviewed, tested, and assembled by me to master underlying web fundamentals.
