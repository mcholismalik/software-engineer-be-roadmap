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
  7. [API](#api)
  8. [Test](#test)
  9. [Microservices](#microservices)
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
      - Depth First Search :fire:
      - Breadth First Search :fire:
  3. Sort
      - Bubble Sort :star:
      - Insertion Sort :star:
      - Selection Sort :star:
      - Merge Sort :snowflake:
      - Quick Sort :snowflake:
  4. Concurrency :fire:
      - Multithreading
      - Multiprocessing

## Data Structure

  1. Array :star:
  2. LinkedList :star:
      - Single LinkedList
      - Double LinkedList
      - Circular LinkedList
  3. Stack & Queue :star:
  4. Tree :snowflake:
      - Tree Data Structure
      - Tree Traversal
      - Binary Search Tree Data Structure
      - Heap Data Structure
  5. Graph :fire:
      - Graph Data Structure
      - DFS Traversal
      - BFS Traversal
  6. Hash :fire:
      - Hash Map Data Structure

## Software Architecture

  1. Paradigm :star:
      - Object Oriented Programming
        - Encaptulation
        - Abstraction
        - Inheritance
        - Polymorphism
      - Procedural Programming
  2. Principle :snowflake:
      - SOLID Principle
      - ACID Principle
  3. Architecture :snowflake:
      - Clean Architecture
      - Hexagonal Architecture
  4. Design Pattern :fire:
      - Creational
          - Abstract Factory
          - Builder
          - Singleton
          - Prototype
      - Structural
          - Adapter
          - Bridge
          - Composite
          - Facade
      - Behavioral
          - Command
          - Observer

## Programming Language

  1. Golang
      1. Basic syntax :star:
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
          - Go runtime scheduler
          - Goroutine queues
          - Stealing work

  2. NodeJS
      1. Basic syntax :star:
      2. I/O
          - Reader :star:
          - Writer :star:
          - Stream :fire:
      4. Concurrency
          - Promise all :star:
          - Child process :fire:
      5. Low Level :fire:
          - Non blocking I/O, single thread event loop

## Database

  1. ACID :snowflake:
  2. Transaction Isolation Level :snowflake:
      - Serializable
      - Repeateble Read
      - Read Commited
      - Read Uncommited
  3. Optimization
      - Indexing :snowflake:
      - Replication :snowflake:
      - Sharding :fire:
          - Consistent Hashing
  4. Type
      - SQL :star:
          - Postgres
          - MySQL
      - No SQL :fire:
          - MongoDB
          - Elastic Search

## API

  1. TCP / UDP :snowflake:
  2. Rest API :star:
  3. Grpc :snowflake:
  4. Websocket :fire:
  5. Graphql :snowflake:
  6. Stream :fire:
  7. Sftp :star:
  8. Pubsub :fire:
      - Kafka
      - Google Pubsub
  9. Queue :fire:
      - RabbitMQ

## Microservices    

  1. Monolith :star:
  2. API Driven :star:
  3. Event Driven :fire:
  4. CAP theorem :fire:
  
## Test

  1. Unit Test :star:
  2. Integration Test :star:

## DevOps    

  1. Container 
      - Docker :star:
      - Kubernetes :fire:
  2. CI/CD
      - Jenkins :snowflake:
  3. Ops :fire:
      - Grafana 
      - Kibana
      - Logstash

## Security    

  1. Authentication :star:
  2. Authorization :star:
  3. CSRF :star:
  4. XSS :star:
  5. Validation :star:
  6. Encryption :snowflake:
      - Symetrical
      - Asymetrical
  7. Race Condition :fire:
  8. Docker Security :fire:
  9. Linux Security :fire:
  
## Contributing

Your contributions are always welcome.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
