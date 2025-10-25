# Credit Approval System

## Quick Start
1. Copy Excel files to data/ folder
2. Run: docker-compose up --build
3. API: http://localhost:8000

## API Endpoints
- POST /register
- POST /check-eligibility
- POST /create-loan
- GET /view-loan/{loan_id}
- GET /view-loans/{customer_id}
