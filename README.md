# Node.js Backend Interview Questions

## 1. Node.js Fundamentals

- [ ] What is Node.js?
- [ ] How is Node.js different from JavaScript?
- [ ] What is the V8 engine?
- [ ] Why is Node.js called single-threaded?
- [ ] How can Node.js handle thousands of concurrent requests if JavaScript is single-threaded?
- [ ] What is non-blocking I/O?
- [ ] What is the difference between blocking and non-blocking I/O?
- [ ] What is the difference between synchronous and asynchronous programming?
- [ ] What is the Node.js Event Loop?
- [ ] ⭐ Explain the Event Loop phases.
- [ ] ⭐ What is libuv?
- [ ] What is the Node.js thread pool?
- [ ] What is the difference between the Event Loop and the thread pool?
- [ ] What is `process.nextTick()`?
- [ ] What is the difference between `process.nextTick()` and `setImmediate()`?
- [ ] What is the difference between `setImmediate()` and `setTimeout(fn, 0)`?
- [ ] What is the difference between the microtask queue and the callback/task queue?
- [ ] What happens internally when a Node.js API receives a request?

## 2. Async JavaScript

- [ ] What is a callback?
- [ ] What is callback hell?
- [ ] How do you avoid callback hell?
- [ ] What is a Promise?
- [ ] What are the states of a Promise: pending, fulfilled, and rejected?
- [ ] What is `Promise.all()`?
- [ ] ⭐ What is `Promise.allSettled()`?
- [ ] What is `Promise.race()`?
- [ ] What is `Promise.any()`?
- [ ] What is the difference between `Promise.all()` and `Promise.allSettled()`?
- [ ] What is `async/await`?
- [ ] How do you handle errors with `async/await`?
- [ ] What is the difference between sequential and parallel API calls?
- [ ] What happens if you forget to use `await`?
- [ ] How would you retry a failed API request?
- [ ] How do you limit concurrency when processing 10,000 operations?

## 3. CommonJS and ES Modules

- [ ] What is `require()`?
- [ ] What is `import`?
- [ ] What is the difference between CommonJS and ES Modules?
- [ ] ⭐ What is the difference between `module.exports` and `export`?
- [ ] What is the difference between `exports` and `module.exports`?
- [ ] What is the difference between default exports and named exports?
- [ ] What does `"type": "module"` in `package.json` mean?
- [ ] What is module caching?

## 4. Process, Buffer, Events, and Streams

- [ ] What is the `process` object?
- [ ] What is `process.env`?
- [ ] What is `process.argv`?
- [ ] What is `process.exit()`?
- [ ] What are exit codes?
- [ ] What is a Buffer?
- [ ] What is the difference between a Buffer and a Stream?
- [ ] What are Streams in Node.js?
- [ ] ⭐ What are the four types of streams: Readable, Writable, Duplex, and Transform?
- [ ] Why should you use streams for large files?
- [ ] What is piping?
- [ ] What is backpressure?
- [ ] ⭐ What is EventEmitter?
- [ ] How do custom events work in Node.js?

## 5. Express.js

- [ ] What is Express.js?
- [ ] Why use Express instead of Node.js's native HTTP module?
- [ ] What is middleware?
- [ ] ⭐ How does the middleware chain work?
- [ ] What is application-level middleware?
- [ ] What is router-level middleware?
- [ ] What is error-handling middleware?
- [ ] What is built-in middleware?
- [ ] What is third-party middleware?
- [ ] What is custom middleware?
- [ ] What is authentication middleware?
- [ ] What is authorization middleware?
- [ ] What is logging middleware?
- [ ] What is validation middleware?
- [ ] What is rate-limit middleware?
- [ ] What is CORS middleware?
- [ ] What is Helmet middleware?
- [ ] What is `next()`?
- [ ] What happens if `next()` is not called?
- [ ] What is the difference between `req.params`, `req.query`, and `req.body`?
- [ ] How do you implement centralized error handling?
- [ ] ⭐ How do you handle asynchronous errors in Express?
- [ ] How do you structure Express routes, controllers, and services?
- [ ] How do you implement API versioning?
- [ ] How do you implement pagination?
- [ ] How do you implement filtering and sorting?
- [ ] What is the difference between PUT and PATCH?
- [ ] What are the important HTTP status codes?

## 6. CORS, Helmet, and Security

- [ ] What is CORS?
- [ ] Why does CORS happen?
- [ ] What is a preflight OPTIONS request?
- [ ] What is CORS middleware?
- [ ] What is Helmet?
- [ ] What security headers does Helmet help configure?
- [ ] What is the difference between authentication and authorization?
- [ ] ⭐ Explain the JWT authentication flow.
- [ ] What is the difference between access tokens and refresh tokens?
- [ ] What is the difference between sessions and JWT?
- [ ] What is the difference between cookies and localStorage for authentication?
- [ ] What are HttpOnly cookies?
- [ ] What does the Secure cookie attribute mean?
- [ ] What is SameSite?
- [ ] How do you hash passwords?
- [ ] What is the difference between hashing and encryption?
- [ ] What is bcrypt?
- [ ] How do you prevent brute-force login attempts?
- [ ] What is rate limiting?
- [ ] How do you validate and sanitize input?
- [ ] What is SQL injection?
- [ ] What is NoSQL injection?
- [ ] What is XSS?
- [ ] What is CSRF?
- [ ] How do you manage secrets and environment variables?
- [ ] How would you design a secure authentication API?

## 7. MongoDB and Mongoose

- [ ] What is MongoDB?
- [ ] What is the difference between SQL and MongoDB?
- [ ] What is a collection?
- [ ] What is a document?
- [ ] What is ObjectId?
- [ ] What is the difference between a schema and a model in Mongoose?
- [ ] What is the difference between `create()` and `save()`?
- [ ] What does `.lean()` do?
- [ ] What is the difference between `find()` and `findOne()`?
- [ ] What is `findById()`?
- [ ] What is the difference between `updateOne()` and `updateMany()`?
- [ ] What is `findOneAndUpdate()`?
- [ ] What do `$set`, `$unset`, `$inc`, `$push`, and `$pull` do?
- [ ] What is an aggregation pipeline?
- [ ] ⭐ What is `$match`?
- [ ] What is `$project`?
- [ ] What is `$group`?
- [ ] What is `$lookup`?
- [ ] What is `$unwind`?
- [ ] What is `$sort`?
- [ ] What are `$limit` and `$skip`?
- [ ] What is indexing?
- [ ] ⭐ What is the difference between single-field and compound indexes?
- [ ] What is a unique index?
- [ ] What is `explain()`?
- [ ] Why can too many indexes hurt performance?
- [ ] What is a MongoDB transaction?
- [ ] When would you use transactions?
- [ ] What is the difference between an embedded document and a reference in MongoDB?
- [ ] How do you optimize a slow MongoDB query?

## 8. Redis and Caching

- [ ] What is Redis?
- [ ] Why is Redis fast?
- [ ] What is the difference between Redis and MongoDB/PostgreSQL?
- [ ] What is API caching?
- [ ] How would you cache an API using Redis?
- [ ] ⭐ What is cache-aside or lazy loading?
- [ ] What is TTL?
- [ ] What is the difference between a cache hit and a cache miss?
- [ ] What is cache invalidation?
- [ ] ⭐ What happens when data changes in the database but Redis contains the old value?
- [ ] What are Redis data types?
- [ ] What are Strings, Hashes, Lists, Sets, and Sorted Sets?
- [ ] What happens if Redis goes down?
- [ ] Should your API continue working if Redis fails?
- [ ] What is Redis Pub/Sub?
- [ ] What are Redis Streams?
- [ ] What is the difference between Redis as a cache and Redis as a messaging system?
- [ ] What are Redis distributed locks?
- [ ] What is a cache stampede?
- [ ] What is cache penetration?

## 9. Kafka and Messaging

- [ ] What is a message queue?
- [ ] Why do we need asynchronous messaging?
- [ ] What is the difference between Kafka and Redis Pub/Sub?
- [ ] What is Kafka?
- [ ] What are producers and consumers?
- [ ] What is a Kafka topic?
- [ ] What is a partition?
- [ ] What is an offset?
- [ ] What is a consumer group?
- [ ] ⭐ Why does Kafka use partitions?
- [ ] How does Kafka provide scalability?
- [ ] What happens when a Kafka consumer fails?
- [ ] What is the difference between at-most-once and at-least-once processing?
- [ ] What is idempotency?
- [ ] What is the difference between RabbitMQ and Kafka?
- [ ] When would you use Kafka instead of REST APIs?

## 10. Microservices

- [ ] What are microservices?
- [ ] What is the difference between a monolith and microservices?
- [ ] ⭐ What are the advantages and disadvantages of microservices?
- [ ] How do microservices communicate?
- [ ] What is the difference between REST and messaging communication?
- [ ] What is the difference between synchronous and asynchronous communication?
- [ ] What is an API Gateway?
- [ ] What is service discovery?
- [ ] What is the database-per-service pattern?
- [ ] How do you handle transactions across microservices?
- [ ] What is eventual consistency?
- [ ] What is the Saga pattern?
- [ ] What is the circuit breaker pattern?
- [ ] What is the retry pattern?
- [ ] What is distributed tracing?
- [ ] How do you handle authentication across multiple services?
- [ ] How do you handle failures between services?

## 11. MVC and Software Architecture

- [ ] What is MVC architecture?
- [ ] What are Model, View, and Controller?
- [ ] What is the difference between MVC and layered architecture?
- [ ] What is the difference between a controller and a service?
- [ ] What is the repository pattern?
- [ ] Why shouldn't business logic be placed directly in controllers?
- [ ] How would you explain a typical Node.js application architecture?
- [ ] How would you structure a large Node.js application?
- [ ] What are SOLID principles?
- [ ] What is dependency injection?
- [ ] What is separation of concerns?

## 12. Performance and Scalability

- [ ] What is latency?
- [ ] What is the difference between latency and throughput?
- [ ] How do you identify a slow API?
- [ ] ⭐ What is the difference between CPU-bound and I/O-bound work?
- [ ] What are Worker Threads?
- [ ] ⭐ When would you use Worker Threads?
- [ ] What is the difference between Worker Threads and child processes?
- [ ] What is `child_process`?
- [ ] What is clustering in Node.js?
- [ ] How can Node.js use multiple CPU cores?
- [ ] What is the difference between horizontal and vertical scaling?
- [ ] What is load balancing?
- [ ] How do you process large files without consuming huge amounts of memory?
- [ ] How do you detect memory leaks?
- [ ] What causes high CPU usage in Node.js?
- [ ] What causes Event Loop blocking?
- [ ] How do you monitor Event Loop lag?
- [ ] What is backpressure?
- [ ] How would you optimize an API whose response time increased from 100 ms to 3 seconds?
- [ ] How do you perform graceful shutdown?
- [ ] ⭐ What happens to requests during application shutdown?

## 13. Docker and Kubernetes

- [ ] What is Docker?
- [ ] What is the difference between an image and a container?
- [ ] What is a Dockerfile?
- [ ] What is Docker Compose?
- [ ] What is port mapping?
- [ ] What are Docker volumes?
- [ ] How do environment variables work in Docker?
- [ ] What is a multi-stage build?
- [ ] How would you Dockerize a Node.js application?
- [ ] What is Kubernetes?
- [ ] What is a Pod?
- [ ] What is a Deployment?
- [ ] What is a Service?
- [ ] What is a ConfigMap?
- [ ] What is a Secret?
- [ ] What is Ingress?
- [ ] What is a Replica?
- [ ] What is a Horizontal Pod Autoscaler?
- [ ] What is the difference between liveness and readiness probes?
- [ ] How do you deploy a Node.js API using containers?

## 14. Testing

- [ ] What is the difference between unit testing and integration testing?
- [ ] What is Jest?
- [ ] What is Supertest?
- [ ] How do you test an Express API?
- [ ] How do you mock external APIs?
- [ ] How do you mock database calls?
- [ ] What is dependency mocking?
- [ ] What should you test in controller, service, and repository layers?
- [ ] How would you test authentication middleware?
- [ ] How do you test failure scenarios?

## 15. Production-Level Scenario Questions

### Scenario 1: Node.js API Becomes Slow

- [ ] Your Node.js API suddenly becomes very slow in production. How will you debug it?
- [ ] How would you investigate request latency?
- [ ] How would you investigate CPU and memory usage?
- [ ] How would you check Event Loop lag?
- [ ] How would you investigate slow database queries?
- [ ] How would you identify slow external API calls?
- [ ] How would you investigate connection pool issues?
- [ ] How would you check Redis cache performance?
- [ ] How would you investigate network latency?

### Scenario 2: Sequential vs. Parallel API Calls

- [ ] Your endpoint performs the following operations:

  ```js
  const users = await getUsers();
  const orders = await getOrders();
  const products = await getProducts();
  ```

- [ ] If these operations are independent, why might parallel execution be faster?
- [ ] How would you rewrite the code using `Promise.all()`?

  ```js
  const [users, orders, products] = await Promise.all([
    getUsers(),
    getOrders(),
    getProducts()
  ]);
  ```

### Scenario 3: 10,000 Concurrent Users

- [ ] 10,000 users simultaneously call your API. How would you scale it?
- [ ] How would you use load balancing?
- [ ] Why might you need multiple Node.js instances?
- [ ] Why should APIs be stateless?
- [ ] How would you use Redis?
- [ ] Why is database connection pooling important?
- [ ] How would database indexing help?
- [ ] How would caching and queues help?
- [ ] How would you implement horizontal scaling?

### Scenario 4: Redis Failure

- [ ] Redis goes down. Should the entire API stop working?
- [ ] How would you implement graceful cache failure?
- [ ] When can the API fall back to the database?
- [ ] How would you prevent a Redis failure from overloading the database?

### Scenario 5: Processing a 5 GB CSV File

- [ ] Your API receives a 5 GB CSV file. How would you process it?
- [ ] Why can loading the entire file into memory be problematic?
- [ ] How would you use Streams, Transform streams, and batch processing?
- [ ] When would you use a database or queue during file processing?
- [ ] Why should you avoid `fs.readFile()` for very large files when streaming is appropriate?

### Scenario 6: Slow MongoDB Query

- [ ] One MongoDB query takes several seconds. How would you optimize it?
- [ ] How would you use `explain()`?
- [ ] How would indexes improve query performance?
- [ ] How does query shape affect performance?
- [ ] Why should you return only the required fields?
- [ ] How can aggregation pipelines affect performance?
- [ ] How can pagination improve performance?
- [ ] How can the data model affect query performance?

### Scenario 7: Increasing Node.js Memory Usage

- [ ] Your Node.js server memory continuously increases. What could be happening?
- [ ] How can global references cause memory leaks?
- [ ] How can timers and event listeners cause memory leaks?
- [ ] How can unbounded caching cause memory problems?
- [ ] How can large Buffers affect memory usage?
- [ ] How would you investigate memory using heap analysis?

### Scenario 8: Payment Succeeds but Order Update Fails

- [ ] Payment succeeds, but your application crashes before updating the order. What would you do?
- [ ] How would you implement idempotency?
- [ ] How would you handle retries?
- [ ] How could queues or events help?
- [ ] How would you manage transaction boundaries?
- [ ] How would you reconcile payment and order states?
- [ ] How would you handle distributed-system failures?

## 16. Additional Advanced Scenario Questions

### 16.1 Event Loop Blocking

- [ ] Your API normally responds in 100 ms, but after adding CPU-heavy JSON processing, it takes 4–5 seconds. Why can this happen in Node.js?
- [ ] How would you identify Event Loop blocking?
- [ ] Would `async/await` solve this problem?
- [ ] Would you use Worker Threads?

### 16.2 CPU-Heavy Tasks

- [ ] Your application needs to generate a large report involving millions of calculations. Would you execute it directly inside the API request?
- [ ] How would you design an API → Queue/Background Processing → Worker → Result workflow?
- [ ] When would you use Worker Threads for CPU-bound operations?

### 16.3 10,000 Concurrent Requests

- [ ] Your API suddenly receives 10,000 simultaneous requests. How would you protect and scale it?
- [ ] How would you use load balancing?
- [ ] Why use multiple application instances?
- [ ] Why are caching and connection pooling important?
- [ ] When would you use queues?
- [ ] How would rate limiting help?
- [ ] How would you implement horizontal scaling?

### 16.4 Memory Keeps Increasing

- [ ] Your Node.js application's memory grows from 300 MB to several GB over time. How would you investigate a possible memory leak?

### 16.5 Application CPU Reaches 100%

- [ ] Production CPU suddenly reaches 100%. What would you investigate first?

### 16.6 Event Loop Starvation

- [ ] A developer recursively uses `process.nextTick()` thousands of times. What could happen to other operations waiting in the Event Loop?

### 16.7 `Promise.all()` Concurrency Problem

- [ ] You call 2,000 external services simultaneously using `await Promise.all(requests)`. What problems could occur?
- [ ] How would you introduce concurrency limits?

### 16.8 Synchronous API in Production

- [ ] Consider this code inside an API endpoint:

  ```js
  const data = fs.readFileSync("large-file.csv");
  ```

- [ ] What is wrong with this approach?
- [ ] How can synchronous file operations affect other requests?

### 16.9 Large JSON Response

- [ ] Your API returns 100,000 database records. How would you redesign it?
- [ ] How would pagination help?
- [ ] How would filtering and field selection help?
- [ ] When would you use compression?
- [ ] When would streaming be appropriate?
- [ ] How could caching improve performance?

### 16.10 Graceful Shutdown in Kubernetes

- [ ] Kubernetes sends your Node.js container a `SIGTERM` signal. How would you safely stop the application?
- [ ] How would you stop accepting new requests?
- [ ] How would you allow current HTTP requests to finish?
- [ ] How would you close database connections?
- [ ] How would you close Redis connections?
- [ ] How would you stop a Kafka consumer safely?
