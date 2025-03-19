---
title: FastApi
sidebar_label: FastApi
description: Why use FastAPI
---
FastAPI

## Introduction
FastAPI is a modern, high-performance web framework for building APIs with Python. It is designed for speed, ease of use, and automatic OpenAPI documentation generation. If you're looking for a lightweight yet powerful API framework, FastAPI is a great choice.
## Why use FastAPI?
1. Blazing Fast: It is known to be the fastest Python frameworks.
2. Automatic Documentation: Generates interactive API documentation.
3. Type Safety: For request validation and serialization it utilizes python type hints.
4. Asynchronous Support: Easily handles async programming with native support.
5. Data Validation: It enforce data types and structure.
6. Dependency Injection: Supports built-in dependency injection for better modularity.
7. Security Features: Provides authentication mechanisms.
8. WebSockets Support: Enables real-time communication.
9. GraphQL Support: Easily integrates with GraphQL.

### How to intsall FastAPI
To install FastAPI and the uvicorn server, type in the following code in your respective terminal:
```bash
pip install fastapi uvicorn
```
### Creating a Simple API
Here's a basic FastAPI application:
```bash
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def read_root():
    return {"message": "Hello, FastAPI!"}
```

## Conclusions
FastAPI's speed, integrated validation, and automated documentation make API creation easier. FastAPI is an excellent framework for creating contemporary online services, regardless of your level of development experience.