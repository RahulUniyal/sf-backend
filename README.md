# Salesforce Validation Rule Manager - Backend

Node.js + Express backend server that handles Salesforce OAuth and API calls.

## Live Demo
🔗 [https://sf-backend-7163.onrender.com](https://sf-backend-7163.onrender.com)

## Features
- ✅ Salesforce OAuth 2.0 Token Exchange
- ✅ Fetch Validation Rules via Tooling API
- ✅ Toggle Single Validation Rule
- ✅ Fetch Single Rule Metadata

## Tech Stack
- Node.js
- Express.js
- Axios
- CORS
- Dotenv
- Render (Deployment)

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | /auth/token | Exchange OAuth code for token |
| GET | /api/rules | Fetch all validation rules |
| GET | /api/rules/:id | Fetch single rule |
| PATCH | /api/rules/:id | Toggle rule active/inactive |

## Setup Instructions

### Clone the repo
```bash
git clone https://github.com/RahulUniyal/sf-backend
cd sf-backend
npm install
```

### Create `.env` file
