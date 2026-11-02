# Day 8 — HTTP Methods, Requests, Responses, and JSON

## 1. Objective

The objective of this session was to understand how web applications communicate with APIs using HTTP and how data is exchanged between a client and a server. The session focused on common HTTP methods, status codes, request and response structures, and JSON as a format for transferring structured data. These concepts are essential for connecting AI models and external services with software applications.

## 2. Topics Covered

### HTTP and Client-Server Communication

HTTP (Hypertext Transfer Protocol) is a protocol used for communication between clients and servers. A client can be a web application, mobile application, or Python program, while a server receives requests and returns responses.

For example, when an AI application sends a user's question to an external AI service, it makes a request to an API endpoint. The service processes the request and returns a response that the application can use.

The general communication process involves preparing a request, sending it to the server, processing the request, and receiving the response.

### Common HTTP Methods

HTTP methods describe the type of operation a client wants to perform.

- **GET:** Retrieves information from a server.
- **POST:** Sends data to a server, commonly to create a resource or perform an operation.
- **PUT:** Replaces an existing resource or updates it according to the API's rules.
- **PATCH:** Updates specific fields or parts of a resource.
- **DELETE:** Requests the removal of a resource.

In AI applications, POST is commonly used to submit input to an API for processing, while GET may be used to retrieve previously stored information.

### HTTP Status Codes

Status codes indicate the result of an HTTP request. Understanding them helps developers identify whether a request succeeded or encountered a problem.

Some common status codes include:

- **200 OK:** The request was successful.
- **201 Created:** A resource was successfully created.
- **400 Bad Request:** The request contains invalid or unsuitable data.
- **401 Unauthorized:** Authentication is missing or invalid.
- **403 Forbidden:** The client does not have permission to perform the operation.
- **404 Not Found:** The requested resource or endpoint could not be found.
- **429 Too Many Requests:** The request limit has been exceeded.
- **500 Internal Server Error:** The server encountered an unexpected problem.

These codes are useful when troubleshooting API integrations and understanding why a request may fail.

### Requests, Responses, and JSON

An HTTP request may contain a URL, method, headers, and a body. Headers can carry information such as the content type and authentication details, while the body can contain the data being submitted.

A response typically includes a status code, headers, and sometimes a body containing the returned information.

JSON (JavaScript Object Notation) is a widely used format for exchanging structured data. It represents information using key-value pairs and arrays, making it convenient for applications to send and receive data.

For example, a chatbot request might contain the following JSON data:

```json
{
  "message": "Explain machine learning in simple words",
  "language": "English"
}
```

The receiving application can read the `message` and `language` fields and use them to process the request.

## 3. Research and Practical Work

During this session, I researched how HTTP supports communication between applications and APIs. I explored the differences between common HTTP methods and examined examples of successful and unsuccessful requests.

As part of the practical exploration, I reviewed JSON structures and considered how user input could be represented as structured data before being sent to an API. I also examined how an application could process a response and use its contents to display information to a user.

I studied common HTTP status codes and their importance in troubleshooting. For example, a 401 response may indicate an authentication problem, while a 429 response may indicate that the request limit has been exceeded.

This session helped me understand the communication layer behind API integrations and how structured requests, responses, and error codes support the development of reliable AI applications.

## 4. Tools and Technologies

- **HTTP:** Studied communication between clients and servers.
- **REST APIs:** Explored common patterns for accessing web services.
- **JSON:** Practised understanding structured request and response data.
- **Python:** Considered for sending HTTP requests and processing responses.
- **API documentation:** Used as a reference for understanding endpoints, methods, and expected data formats.

## 5. Learning Outcomes

By the end of this session, I understood how HTTP requests and responses work and how common methods are used to communicate with APIs. I learned the meaning of important HTTP status codes and how they help identify request failures.

I also gained a better understanding of JSON and its role in transferring structured data between applications. These concepts strengthened my foundation for integrating AI services, troubleshooting API issues, and developing applications that communicate with external systems.
