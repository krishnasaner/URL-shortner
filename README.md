# URL Shortener Service

A lightweight microservice built with Flask for generating and managing shortened URLs using custom Base62 encoding. The service supports redirection, analytics, and persistent storage using SQLite or PostgreSQL.

## Features

- Shorten long URLs with custom Base62 encoding
- Redirect to original URLs using short codes
- Store and manage URL records in a database
- Optional support for URL expiration and analytics (click counts, creation date)
- RESTful API for integration with frontend or other services

## Technology Stack

- **Backend**: Flask (Python)
- **Database**: SQLite (development) / PostgreSQL (production)
- **Encoding Logic**: Custom Base62 algorithm for short code generation

