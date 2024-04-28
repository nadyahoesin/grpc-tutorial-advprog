# Reflections

1. As explained in the module, the key differences between unary, server streaming, and bi-directional streaming RPC (Remote Procedure Call) methods are:
   - Unary RPC methods are for services that perform a simple client-server interactions where the client sends a single request and the server sends a single response. These methods are suitable for fetching a single item from the database.
   - Server streaming RPC methods are for services that allow the server to send a stream of responses to the client. These methods are suitable for real-time updates like stock market prices.
   - Bi-directional streaming RPC methods are for services that allow both the client and server to send multiple messages to each other in a continuous stream. These methods are suitable for a chat service.

2. The potential security considerations involved in implementing a gRPC service in Rust, particularly regarding authentication, authorization, and data encryption, are

3. The potential challenges or issues that may arise when handling bidirectional streaming in Rust gRPC, especially in scenarios like chat applications, are

4. The advantages and disadvantages of using the tokio_stream::wrappers::ReceiverStream for streaming responses in Rust gRPC services

5. The Rust gRPC code can be structured to facilitate code reuse and modularity, promoting maintainability and extensibility over time by

6. In the MyPaymentService implementation, additional steps that might be necessary to handle more complex payment processing logic are

7. The impact that the adoption of gRPC as a communication protocol have on the overall architecture and design of distributed systems, particularly in terms of interoperability with other technologies and platforms, are

8.  The advantages and disadvantages of using HTTP/2, the underlying protocol for gRPC, compared to HTTP/1.1 or HTTP/1.1 with WebSocket for REST APIs, are

9.  The request-response model of REST APIs contrast with the bidirectional streaming capabilities of gRPC in terms of real-time communication and responsiveness by

10. The implications of the schema-based approach of gRPC, using Protocol Buffers, compared to the more flexible, schema-less nature of JSON in REST API payloads