# SaaS Example

This folder provides a minimal proof of concept for a SaaS application with a
Java backend and an Angular frontend.

## Backend

The backend uses Spring Boot with Gradle. To run it:

```bash
cd backend
gradle bootRun
```

A single endpoint is exposed at `GET /api/hello`.

## Frontend

The frontend contains a lightweight Angular setup. To serve it in development
mode you will need the Angular CLI:

```bash
cd frontend
npm install
npm start
```

This will start the Angular development server on port 4200.
