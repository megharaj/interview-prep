# Interview Prep & Materials

<!-- QUESTIONS_START -->

### <ins>JavaScript Interview Q&A </ins>

[Sudheerj - Javascript Interview- Questions](https://github.com/sudheerj/javascript-interview-questions/tree/master)

### <ins>Forward proxy vs. Reverse proxy</ins>

#### 𝗙𝗼𝗿𝘄𝗮𝗿𝗱 𝗣𝗿𝗼𝘅𝘆: A forward proxy server sits between a client (like a web browser) and the internet. It acts as an intermediary for requests from the client seeking resources on other servers. Here’s how it works:

- 𝗣𝗿𝗶𝘃𝗮𝗰𝘆 & 𝗔𝗻𝗼𝗻𝘆𝗺𝗶𝘁𝘆: Users can hide their IP addresses and locations by routing through the proxy, which can mask their identity.
- 𝗖𝗼𝗻𝘁𝗲𝗻𝘁 𝗙𝗶𝗹𝘁𝗲𝗿𝗶𝗻𝗴: Often used by organizations to block access to certain sites or monitor employee internet usage.
- 𝗖𝗮𝗰𝗵𝗶𝗻𝗴: Speeds up access to frequently visited websites by storing copies of web pages, saving time and bandwidth.
- 𝗘𝘅𝗮𝗺𝗽𝗹𝗲 𝗨𝘀𝗲 𝗖𝗮𝘀𝗲: A company implementing a forward proxy for employees to access the internet, with controls to monitor or restrict certain websites.

#### 𝗥𝗲𝘃𝗲𝗿𝘀𝗲 𝗣𝗿𝗼𝘅𝘆: A reverse proxy sits between the internet and a web server, forwarding client requests to the appropriate backend server. Its purpose is quite different:

- 𝗟𝗼𝗮𝗱 𝗕𝗮𝗹𝗮𝗻𝗰𝗶𝗻𝗴: It can distribute incoming traffic across multiple servers, improving performance and preventing overload.
- 𝗦𝗲𝗰𝘂𝗿𝗶𝘁𝘆: Helps protect backend servers by hiding their identities and filtering out malicious traffic.
- 𝗖𝗮𝗰𝗵𝗶𝗻𝗴 & 𝗖𝗼𝗺𝗽𝗿𝗲𝘀𝘀𝗶𝗼𝗻: Often used to cache responses or compress content to speed up delivery.
- 𝗦𝗦𝗟 𝗧𝗲𝗿𝗺𝗶𝗻𝗮𝘁𝗶𝗼𝗻: Offloads SSL encryption/decryption to reduce server load.
- 𝗘𝘅𝗮𝗺𝗽𝗹𝗲 𝗨𝘀𝗲 𝗖𝗮𝘀𝗲: A website using a reverse proxy to route user requests to multiple web servers behind the scenes, improving scalability and uptime.

In summary, 𝗳𝗼𝗿𝘄𝗮𝗿𝗱 𝗽𝗿𝗼𝘅𝗶𝗲𝘀 are used by clients to access the internet with privacy and control, while 𝗿𝗲𝘃𝗲𝗿𝘀𝗲 𝗽𝗿𝗼𝘅𝗶𝗲𝘀 are used by servers to manage traffic and improve security and performance.
Both are invaluable tools but serve opposite ends of the client-server relationship!

<img src="assets/forward-proxy-vs-reverse-proxy.gif" width="600" height="800">

### <ins>REST API Design</ins>

#### Key Principles for REST API Design:

- Use HTTP methods (GET, POST, PUT, DELETE) for clarity.
- Cache responses to boost performance.
- Ensure each client request is self-contained, with no server-side state storage.
- Provide fine-grained control over resources for efficiency.
- Support pagination, filtering, and ordering for large datasets.
- Interconnect resources for easy discoverability.
- Prioritise security with authentication and authorization.

#### Best Practices for Implementation:

- Implement versioning to handle changes smoothly.
- Use self-descriptive messages to improve usability.
- Include HATEOAS to guide clients through resources.
- Use a layered, consistent interface for modularity and clarity.
- Enable CORS and idempotence for safe, predictable operations.
- Focus on security with authentication, logging, and input validation.
- Secure data with TLS and manage load with rate limiting.

#### Conclusion:
Designing an effective REST API is crucial for building scalable, secure, and interconnected digital solutions. By following these principles, developers can create APIs that drive innovation and elevate the user experience in a rapidly evolving tech world.


### <ins>API Protocols</ins>

1. REST (Representational State Transfer)
- An architectural style for designing networked applications.
- It emphasizes stateless communication, the use of standard HTTP methods (GET, POST, PUT, DELETE), and resources identified by URLs.

2. GraphQL
- A query language for APIs that allows clients to request exactly the data they need, nothing more and nothing less.
- This efficiency is a major advantage over REST, where endpoints often return fixed data structures.

3. SOAP (Simple Object Access Protocol)
- A protocol for exchanging structured information in the form of XML messages over a network.

4. gRPC (Google Remote Procedure Call)
- A high-performance, open-source framework for remote procedure calls (RPCs).
- It uses Protocol Buffers (a compact binary format) for data serialization.

5. Webhooks
- A mechanism for real-time communication between applications.
- A webhook is essentially an HTTP callback triggered by a specific event in one system, which sends a notification to another system.

6. WebSockets
- A protocol providing full-duplex communication channels over a single TCP connection.
- WebSockets enable real-time data exchange between a client and a server.

7. MQTT (Message Queuing Telemetry Transport)
- A lightweight publish-subscribe messaging protocol designed for low-bandwidth, high-latency, or unreliable networks.
- It is commonly used in IoT (Internet of Things) applications.

8. AMQP (Advanced Message Queuing Protocol)
- An open standard protocol for message-oriented middleware.
- AMQP provides features like reliable message delivery, routing, and queuing, making it suitable for enterprise integration scenarios.

9. EDA (Event-Driven Architecture)
- A software architecture pattern where applications react to events (e.g., user actions, sensor readings).
- EDA promotes loose coupling and scalability.

10. EDI (Electronic Data Interchange)
- A set of standards for exchanging business documents (e.g., purchase orders, invoices) electronically between organizations.
- EDI is widely used in supply chain management and logistics.

11. SSE (Server-Sent Events)
- A server-push technology that allows a server to send updates to a client over an HTTP connection in a unidirectional manner.

<img src="assets/api-protocols.gif">

<!-- QUESTIONS_END -->
