# User Authentication Flow

## Goal
Allow users to sign up, log in, and stay authenticated securely.

## Actors
- User (browser)
- Frontend application
- Backend API
- Database

## Flow (High Level)
1. User submits credentials from the frontend
2. Frontend sends request to backend API
3. Backend validates input
4. Backend checks credentials against database
5. Backend issues auth token
6. Frontend stores token securely
7. Authenticated requests include token

## Open Questions
- Token vs session?
- Where should validation live?
- How are errors communicated to the UI?
