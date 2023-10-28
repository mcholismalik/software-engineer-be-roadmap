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
      - Depth First Search :fire:
      - Breadth First Search :fire:
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
  3. Stack** :star:
  4. Queue** :star:
  5. Tree** :snowflake: 
      - Tree
      - Binary Tree
      - Binary Search Tree
      - Heap
  7. Graph :fire: 
  8. Hash :fire:
  9. Bloom Filters :fire:

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
      1. Basic syntax :star:
          - Struct
          - Pointer
          - Defer Recover
      2. I/O
          - Reader :star:
          - Writer :star:
          - Stream :fire:
      3. Concurrency
          - Goroutine :star:
          - Channel :snowflake:
          - Select :snowflake:
          - Sync Package :snowflake: 
            - Wait group
            - Mutex
      4. Low Level :fire:
          - Garbage collector
          - Context switching
          - Go runtime scheduler
          - Goroutine queues
          - Stealing work

  2. NodeJS
      1. Basic syntax :star:
          - Closure
          - Interpolation
      2. I/O
          - Reader :star:
          - Writer :star:
          - Stream :fire:
      4. Concurrency
          - Promise :star:
          - Clustering :fire:
          - Child process :fire:
      5. Low Level :fire:
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
        - B-tree
        - B+ tree
        - LSM tree
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
  2. HTTP :star:
     - HTTP/2
     - HTTP/3
  4. Rest API :star:
  5. Grpc :snowflake:
  6. Websocket :fire:
  7. Graphql :snowflake:
  8. Webhook :snowflake:
  9. Sftp :star:
     
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
  8. SSL, TLS, HTTPS :snowflake:
  9. Container 
      - Docker :star:
      - Kubernetes :fire:
  10. CI/CD
      - Jenkins :snowflake:
  11. Ops :fire:
      - Git flow 
  12. Serverless :fire:

## Security    

  1. Authentication :star:
  2. Authorization :star:
  3. Oauth2 :star:
  4. CSRF :star:
  5. XSS :star:
  6. Validation :star:
  7. Encryption :snowflake:
      - Symetrical
      - Asymetrical
  
## Contributing

Your contributions are always welcome.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
