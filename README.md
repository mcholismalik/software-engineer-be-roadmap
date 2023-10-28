# Backend Engineer Roadmap

Backend engineer roadmap from zero to one.
- :star: (Beginner)
- :snowflake: (Intermediate)
- :fire: (Advanced)

## Table of Contents

  1. [Big O(n) Notation](#big-on-notation)
  2. [Algorithm](#algorithm)
  3. [Data Structure](#data-structure)
  4. [Software Architecture](#software-architecture)
  5. [Programming Language](#programming-language)
  6. [Database](#database)
  7. [Protocol](#protocol)
  8. [Test](#test)
  9. [Distributed System](#distributed-system)
  10. [DevOps](#devops)
  11. [Security](#security)

## Big O(n) Notation

  1. O(1) :star:
  2. O(n) :star:
  3. O(log n) :fire:
  4. O(n log n) :fire:
  5. O(n^2) :star:

## Algorithm

  1. Recursion :star:
  2. Search
      - Linear Search :star:
      - Binary Search :star:
      - Tree Traversal :star:
      - BFS & DFS :fire:
  3. Sort
      - Bubble Sort :star:
      - Quick Sort :snowflake:
      - Merge Sort :snowflake:
  4. Sliding Window :snowflake:
  5. Two Pointer :snowflake:
  6. Greedy :fire:
  7. Dynamic Programming :fire:
  8. Backtracking :fire:
  9. Concurrencies & Parallelism :fire:
      - Concurrency
      - Parllellism
      - Multithreading
      - Multiprocessing
   
## Data Structure

  1. Array :star:
  2. LinkedList :star:
      - Single LinkedList
      - Double LinkedList
      - Circular LinkedList
  3. Stack :star:
  4. Queue :star:
  5. Tree :snowflake: 
      - Tree
      - Binary Tree
      - Binary Search Tree
      - Heap
  7. Graph :fire: 
  8. Hash :fire:
  9. Bloom Filters :fire:
      - [Bloom Filters | Algorithms You Should Know #2 | Real-world Examples](https://www.youtube.com/watch?v=V3pzxngeLqw&t=84s)
      - [Bloom Filters Explained by Example](https://www.youtube.com/watch?v=gBygn3cVP80&t=46s)
## Software Architecture

  1. Paradigm :star:
      - Object Oriented Programming
        - Encaptulation
        - Abstraction
        - Inheritance
        - Polymorphism
      - Functional Programming
  2. Principle :snowflake:
      - SOLID Principle
      - Clean Architecture
  3. Design Pattern :fire:
      - Creational
          - Factory
          - Builder
          - Singleton
          - Prototype
      - Behavioral
          - Observer
          - Iterator
          - Strategy
          - Command
      - Structural
          - Adapter
          - Facade
          - Bridge
          - Composite

## Programming Language

  1. Golang
     - Basic syntax :star:
        - Struct
        - Pointer
        - Defer Recover
     - I/O
        - Reader :star:
        - Writer :star:
        - Stream :fire:
     - Concurrency
        - Goroutine :star:
        - Channel :snowflake:
        - Select :snowflake:
        - Sync Package :snowflake: 
          - Wait group
          - Mutex
     - Low Level :fire:
        - Garbage collector
        - Context switching
        - Go runtime scheduler
        - Goroutine queues
        - Stealing work

  2. NodeJS
     - Basic syntax :star:
        - Closure
        - Interpolation
     - I/O
        - Reader :star:
        - Writer :star:
        - Stream :fire:
     - Concurrency
        - Promise :star:
        - Clustering :fire:
        - Child process :fire:
     - Low Level :fire:
        - Event queue
        - Event loop
        - Thread pool
        - Callback
        - Promise

## Database

  1. Principle :snowflake:
      - ACID Principle
      - CAP Theorem
  2. Transaction Isolation Level :snowflake:
      - Serializable
      - Repeateble Read
      - Read Commited
      - Read Uncommited
  3. Optimization
      - Indexing :fire:
        - B tree
          - [B Trees and B+ Trees. How they are useful in Databases](https://www.youtube.com/watch?v=aZjYr87r1b8)
        - B+ tree
          - [The Difference Between B-trees and B+trees](https://www.baeldung.com/cs/b-trees-vs-btrees) 
        - LSM tree
          - [The Secret Sauce Behind NoSQL: LSM Tree](https://www.youtube.com/watch?v=I6jB0nM9SKU&t=46s)
          - [How databases scale writes: The power of the log](https://www.youtube.com/watch?v=_5vrfuwhvlQ) 
      - Replication :snowflake:
      - Sharding :fire:
          - Type
            - Logical
            - Physical
          - Strategy
            - Algorithmic
            - Dynamic
          - Hash 
            - Basic Hashing
            - Geo Hashing
            - Consistent Hashing
  4. Type
      - SQL :star:
          - Postgres
          - MySQL
      - No SQL :fire:
          - MongoDb
          - Elastic Search
          - Cassandra
          - Scylla
      - Memory :star:
          - Redis
          - Memcached
      - Distributed :fire:
          - Debezium

## Protocol

  1. TCP / UDP :snowflake:
     - [TCP vs UDP Crash Course](https://www.youtube.com/watch?v=qqRYkcta6IE&t=21s)
  3. HTTP :star:
     - [What happens when you type a URL into your browser?](https://www.youtube.com/watch?v=AlkDbnbv7dk&t=155s)
     - [HTTP/1 to HTTP/2 to HTTP/3](https://www.youtube.com/watch?v=a-sBfyiXysI)
  4. Rest API :star:
     - [REST API Interview Questions (Beginner Level)](https://www.youtube.com/watch?v=faMdrSCVDzc)
     - [REST API Interview Questions (Advanced Level)](https://www.youtube.com/watch?v=n2JQFFFEd0M)
  6. Grpc :snowflake:
     - [What is RPC? gRPC Introduction.](https://www.youtube.com/watch?v=gnchfOojMk4)
  7. Websocket :fire:
  8. Graphql :snowflake:
  9. Webhook :snowflake:
  10. Sftp :star:
     
## Distributed System

  1. Pattern :snowflake:
     - Ambassador
       - Kubernetes Envoy 
     - Circuit Breaker
     - CQRS
     - Event Sourcing
     - Leader Election
       - Zookeper
     -  Sharding
  2. Microservices
     - Monolith :star:
     - API Driven :star:
     - Event Driven :fire:
       - Stream
         - Kafka
         - Flink
         - Spark
       - Queue
         - Rabbit MQ
  3. Database :fire:
     - CAP theorem
       - [CAP Theorem Simplified](https://www.youtube.com/watch?v=BHqjEjzAicA&t=1s) 
       - [CAP Theorem for System Design Interviews](https://www.youtube.com/watch?v=BTKBS_GdSms)
     - Eventually Consistency
     - Connection Pool
  4. Race Condition :fire:
     - Optimistic Locking
     - Pessimistic Locking
  5. Load Balancer :snowflake:
     - Round robin
     - Worker pool
  6. Thorttling :fire:
     - Rate Limiter
     - Circuit Breaker
  7. Fusing :fire:
     - Request Coalescing
     - Idempotency
     - Batch Processing
  8. Logging :star:
     - Datadog
     - Logstash
  9. Monitoring & Alerting :fire:
     - Prometheus
     - Grafana
     - Pyroscope
 10. Tracking :fire:
     - Open Telemetry
     - Zipkin
     - Jeager
  
## Test

  1. Unit Test :star:
  2. Functional Test
  3. Integration Test :star:

## DevOps    

  1. Scaling :star:
      - Vertical
      - Horizontal
  2. Load Balancer :star:
  3. CDN (Content Delivery Network) :star:
  4. TCP :star:
  5. IP Address :star:
  6. DNS :star:
  7. Proxy & Reverse Proxy :star:
      - [Proxy vs Reverse Proxy (Real-world Examples](https://www.youtube.com/watch?v=4NB0NDtOwIQ&t=14s)
      - [Proxies | System Design Tutorials | Part 4 | 2020](https://www.youtube.com/watch?v=Nu-4Q3OoR4E)
  9. SSL, TLS, HTTPS :snowflake:
      - [SSL, TLS, HTTPS Explained](https://www.youtube.com/watch?v=j9QmMEWmcfo&t=1s)
      - [Transport Layer Security, TLS 1.2 and 1.3 (Explained by Example)](https://www.youtube.com/watch?v=4NB0NDtOwIQ&t=14s)
      - [What are SSL/TLS Certificates? Why do we Need them? and How do they Work?](https://www.youtube.com/watch?v=r1nJT63BFQ0)
  11. Container 
      - Docker :star:
      - Kubernetes :fire:
  12. CI/CD
      - Jenkins :snowflake:
  13. Ops :fire:
      - Git flow 
  14. Serverless :fire:

## Security    

  1. Authentication :star:
  2. Authorization :star:
  3. Oauth2 :star:
  4. CSRF :star:
  5. XSS :star:
  6. Validation :star:
  7. Encryption :snowflake:
      - [Symmetrical vs asymmetrical Encryption Pros and Cons by Example](https://www.youtube.com/watch?v=Z3FwixsBE94)
  
## Contributing

Your contributions are always welcome.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
