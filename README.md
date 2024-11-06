# HTTP Server from scratch in RUST

## HTTP (library)

HTTP library to parse incoming HTTP requests and construct HTTP responses. The HTTP requests and responses were modeled
using Rust structs and enums.

- ### HttpRequest
    - Converting request to Rust structs and methods for same

- ### HttpResponse
    - Converting Rust structs into bytes to be written in byte stream

## HTTP Server (module)

Serves two types of content: static web pages (with associated files, such as stylesheets) and JSON data. Accept
requests and send responses to standard HTTP clients, such as browsers and the curl tool.

- ### Router (module)
    - Determines which handler to invoke

- ### Handler (module)
    - Processing the incoming request and return an HTTP response

