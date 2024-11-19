---
title: Overview
layout: default
parent: Middleware
nav_order: 1
---
# Middlewares

Middleware functions are executed before or after a route callback, enabling you to extend the behavior of your routes.

They are an excellent way to implement features like API authentication, access control, or request validation. 

With Goma, you can create custom middleware tailored to your needs and apply them to your routes seamlessly.

## Supported Middleware Types

- **Authentication Middleware**
  - **JWT**: Performs client authorization based on the result of a request using JSON Web Tokens.
  - **Basic-Auth**: Verifies credentials through Basic Authentication.
  - **OAuth**: Supports OAuth-based authentication flows.

- **Rate Limiting Middleware**
  - **In-Memory Client IP Based**: Throttles requests based on the client’s IP address using an in-memory store.
  - **Distributed Rate Limiting**: Leverage Redis for scalable, client IP-based rate limits.

- **Access Middleware**
  - Validates user permissions or access rights for specific route paths.

Middleware provides a flexible and powerful way to enhance the functionality, security, and performance of your API.