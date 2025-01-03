# Architectural Patterns and Solutions

This repository showcases five architectural patterns and their solutions, followed by a transition from monolithic to microservices using **Pipe and Filter** and **Observer** patterns.

## 1. Monolithic Architecture Limitations
Transition to **Microservices Architecture** for independent services.

## 2. Database Bottleneck
Use **Distributed Databases** or **Database Sharding**.

## 3. Single Point of Failure
Implement **Redundancy** and **Load Balancing**.

## 4. Legacy Code and Incompatibility
Facilitate migration using **APIs** and **Middleware**.

## 5. Performance Issues in Real-Time Systems
Use **Event-Driven Architecture** and tools like **Apache Kafka**.

---

# Monolithic to Microservices Transition

The transition from a monolithic e-commerce system to microservices is demonstrated using **Pipe and Filter** and **Observer** patterns:

- **Pipe and Filter**: Separates responsibilities into filters for **inventory**, **orders**, and **search**.
- **Observer**: Implements a **Subject** (inventory) and **Observers** (order and search) that react to changes.

## Benefits:
- **Scalability**: Independent scaling of services.
- **Maintainability**: Easier updates and debugging.
- **Fault Isolation**: Failures in one service don't affect others.

This repository demonstrates the power of microservices through modular designs, enhancing scalability, maintainability, and fault tolerance.
## Video Demonstration
https://drive.google.com/drive/folders/1JkhzrCqKa2SgFfjrRYBB9MmgNdJ0S1mX?usp=sharing
