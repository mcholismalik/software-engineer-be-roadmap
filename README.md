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

  1. **O(1)** :star: Performance remains constant, regardless of input size.
  2. **O(n)** :star: Performance grows linearly with input size.
  3. **O(log n)** :fire: Performance grows logarithmically with input size, common in efficient searching algorithms.
  4. **O(n log n)** :fire: Performance grows linearithmically, often seen in efficient sorting algorithms.
  5. **O(n^2)** :star: Performance grows with the square of input size, common in nested loop situations.

## Algorithm

  1. **Recursion** :star: Recursion is a programming technique in which a function calls itself to solve a problem.
  2. **Search** 
      - **Linear Search** :star: Scanning through a list one element at a time to find a specific item.
      - **Binary Search** :star: Efficiently finding an item in a sorted list by repeatedly dividing the search space in half.
      - **Tree Traversal** :star: Methods to visit nodes in a specific order (in-order, pre-order, post-order).
      - **Depth First Search** :fire: Explores as far as possible along a branch before backtracking
      - **Breadth First Search** :fire: Explores all the neighbors of a node before moving to their child nodes.
      - **Backtracking** :fire: Solving a tricky puzzle by trying different moves and undoing them if they don't work, until you find the right sequence of moves.
  3. **Sort**
      - **Bubble Sort** :star: Comparing and swapping adjacent elements until the list is sorted.
      - **Insertion Sort** :star: Building a sorted list by inserting elements into their correct positions.
      - **Selection Sort** :star: Selecting the smallest item and placing it in the sorted portion
      - **Merge Sort** :snowflake: Divides the list into tiny parts, sorts each part, and then puts them together to make a sorted list.
      - **Quick Sort** :snowflake: Quickly rearranges the list by picking a number and sorting the list around it, and it keeps doing this until the whole list is sorted.
  4. **Parallelism** :fire:
      - **Concurrent** Make progress simultaneously, providing the illusion of parallelism.
      - **Multithreading** Multiple threads within a single process run concurrently and share memory.
      - **Multiprocessing** Independent processes run concurrently, with their own memory spaces.
  5. **Dynamic Programming** :fire: Breaking them into smaller subproblems, solving each subproblem only once, and storing the results to avoid redundancy.
   
## Data Structure

  1. **Array** :star: An array is a linear data structure that holds a fixed number of elements of the same data type. Elements are stored in contiguous memory locations, allowing efficient access based on their index.
  2. **LinkedList** :star: A linked list is a linear data structure in which elements (nodes) are connected through pointers.
      - **Single LinkedList** Each node points to the next node in the list.
      - **Double LinkedList** Each node points to both the next and previous nodes.
      - **Circular LinkedList** The last node points back to the first node, forming a loop.
  3. **Stack** :star: Linear data structure that follows the Last-In-First-Out (LIFO) principle. 
  4. **Queue** :star: Linear data structure that follows the First-In-First-Out (FIFO) principle.
  5. **Tree** :snowflake: 
      - **Tree**  Hierarchical data structure with nodes and edges.
      - **Binary Tree** Tree where each node has at most two children.
      - **Binary Search Tree** Type of binary tree with ordered values for efficient searching.
      - **Heap** Is a specialized binary tree-based structure used for priority queues and efficient access to extreme values.
  7. **Graph** :fire: Versatile data structure that consists of a set of nodes (vertices) connected by edges. 
  8. **Hash** :fire: Fundamental data structure used for efficient data storage, retrieval, and manipulation.

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

  1. ACID Principle :snowflake:
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
          - MongoDb
          - Elastic Search
      - Memory
          - Redis
          - Memcached
      - Distributed
          - Debezium

## Protocol

  1. TCP / UDP :snowflake:
  2. Rest API :star:
  3. Grpc :snowflake:
  4. Websocket :fire:
  5. Graphql :snowflake:
  6. Stream :fire:
  7. Sftp :star:
     
## Distributed System

  1. Microservices
     - Monolith :star:
     - API Driven :star:
     - Event Driven :fire:
       - Pubsub
         - Kafka
       - Queue
         - Rabbit MQ
  2. Database
     - CAP theorem :fire:
     - Eventually Consistency
  3. Race Condition
     - Optimistic Locking
     - Pessimistic Locking
  5. Load Balancer
     - Round robin
     - Worker pool
  6. Thorttling
     - Rate Limiter
     - Circuit Breaker
  7. Fusing
     - Request Coalescing
     - Idempotency
     - Batch Processing
  8. Logging
     - Datadog
     - Logstash
  9. Monitoring
     - Prometheus
     - Grafana
     - Pyroscope
     - Jeager
  
## Test

  1. Unit Test :star:
  2. Functional Test
  3. Integration Test :star:

## DevOps    

  1. Container 
      - Docker :star:
      - Kubernetes :fire:
  2. CI/CD
      - Jenkins :snowflake:
  3. Ops :fire:
      - Git flow 
  4. Serverless :fire:

## Security    

  1. Authentication :star:
  2. Authorization :star:
  3. CSRF :star:
  4. XSS :star:
  5. Validation :star:
  6. Encryption :snowflake:
      - Symetrical
      - Asymetrical
  
## Contributing

Your contributions are always welcome.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
