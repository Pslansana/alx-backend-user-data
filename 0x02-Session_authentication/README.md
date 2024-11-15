# Session Authentication Project

## Overview
This project involves implementing Session Authentication from scratch to understand the underlying mechanism without relying on external modules. This approach will help you gain a thorough understanding of how session-based authentication works, how cookies are sent and parsed, and the fundamental concepts of session management in web applications.

## Project Timeline
- **Start Date**: Nov 13, 2024, 3:00 AM
- **End Date**: Nov 15, 2024, 3:00 AM
- **Checker Release**: Nov 13, 2024, 3:00 PM
- **Auto-Review**: Nov 15, 2024, 3:00 AM (project deadline)

## Background Context
In production environments, it is recommended to use established libraries or frameworks like Flask-HTTPAuth to handle session authentication securely and reliably. However, in this project, we will manually implement session authentication to deepen our understanding of how the process works.

## Learning Objectives
Upon completing this project, you should be able to:
- Explain the purpose of authentication and the basics of session authentication
- Understand the role of cookies in managing sessions and user state
- Demonstrate how to send cookies from the server and read cookies from the client
- Parse cookies to manage sessions

## Concepts and Resources

### Authentication
Authentication is the process of verifying the identity of a user. It ensures that users are who they claim to be and provides access control based on their credentials.

### Session Authentication
Session authentication is a stateful method that keeps track of the user's identity and state through sessions. Sessions are stored on the server and referenced through session IDs stored in cookies on the client's side.

### Cookies
Cookies are small pieces of data stored on the client's browser, often used to remember the user’s session or preferences. In session-based authentication, a cookie usually contains a session ID that links to the user's session on the server.

### Resources
- **[REST API Authentication Mechanisms](#)**: Read the section on session authentication for an introduction to this authentication method.
- **[HTTP Cookie](#)**: Learn how cookies work and how they store small pieces of data on the client side.
- **[Flask](#)**: Familiarize yourself with the Flask framework, which will be used to build the authentication system.
- **[Flask Cookie](#)**: Understand how to manage cookies in Flask, including setting and retrieving cookie values.

## Project Structure

This project will be divided into multiple tasks to build up the session authentication system step-by-step. Below is an outline of each task you will complete:

1. **Initialize Flask Application**: Set up a simple Flask app to serve as the basis for the project.
2. **User Login and Authentication**: Create endpoints for user login, where valid credentials create a new session.
3. **Session Management with Cookies**: Generate session IDs and store them in cookies. Implement cookie sending from the server.
4. **Session Verification**: Build middleware or route guards to verify session cookies and manage access to protected routes.
5. **Logout and Session Deletion**: Implement a logout route that deletes the session on the server and removes the cookie from the client.
6. **Error Handling and Security Considerations**: Handle common errors like unauthorized access and consider security improvements (e.g., secure cookie flags, session expiration).

## Getting Started

### Prerequisites
- Python 3.x
- Flask (only core Flask package, no external modules for authentication)

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd session-authentication

