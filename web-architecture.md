# Web Architecture Notes

## Basic Web Application Flow

A user interacts with the frontend through a client such as a web browser.

The frontend sends an HTTP request to a backend API.

The backend receives the request, processes application logic and may request data from a database.

The database returns the requested data to the backend.

The backend creates an HTTP response and sends it back to the frontend through the API.

The frontend receives the response and displays the result to the user.

## Basic Flow

User
→ Client / Browser
→ Frontend
→ HTTP Request
→ Backend API
→ Backend
→ Database
→ Backend
→ HTTP Response
→ Frontend
→ User

## Key Concepts

- Client: software that sends requests to a server, for example a web browser.
- Server: a system that receives requests and provides responses.
- Frontend: the user-facing part of a web application.
- Backend: the server-side part that processes requests and application logic.
- Database: stores and provides application data.
- API: defines how software components communicate with each other.
- HTTP: a protocol used for communication between clients and servers.
- HTTP Method: describes the action requested, for example GET.
- API Endpoint: a specific address exposed by an API, for example /api/flights.
- HTTP Status Code: describes the result of an HTTP request, for example 200 OK.