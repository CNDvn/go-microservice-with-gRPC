- reference: https://levelup.gitconnected.com/microservices-with-go-grpc-api-gateway-and-authentication-part-1-2-393ad9fc9d30
- We will develop 3 Microservices and 1 API Gateway which handles incoming HTTP requests. HTTP requests will be forwarded to these Microservices by gRPC. Additionally, we deal with JWT authentication.
- We going to build a small e-commerce system

### Application Infrastructure

1. API Gateway: Handles incoming HTTP requests
2. Auth Service: Provides features such as Register, Login and generates Token by JWT
3. Product Service: Provides features such as Add Product, Decrease Stock and Find Product
4. Order Service: The only feature we ship in this Microservice is Create Order
