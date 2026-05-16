# Advanced Database Management System

## Overview

Advanced Database Management System (ADBMS) is a project focused on implementing and understanding advanced concepts of database systems including normalization, indexing, transactions, concurrency control, query optimization, and file organization techniques.

This repository contains implementations, experiments, SQL queries, system-level concepts, and lab exercises related to advanced database management systems.

---

## Features

- Relational Database Design
- SQL Query Processing
- Transaction Management
- Concurrency Control
- Deadlock Handling
- Indexing Techniques
- File Organization
- Query Optimization
- Normalization (1NF → BCNF)
- Joins and Nested Queries
- Stored Procedures and Triggers
- Locking Mechanisms
- Recovery Techniques
- System Call Based File Handling
- Database Lab Experiments

---

## Technologies Used

- C++
- SQL
- MySQL / PostgreSQL
- Linux
- Git & GitHub

---

## Project Structure

```bash
.
├── Lab_01.cpp
├── Lab_01.txt
├── sql_queries/
├── reports/
├── experiments/
├── docs/
└── README.md
```

---

## Concepts Covered

### Database Fundamentals

- ER Model
- Relational Model
- Functional Dependencies
- Schema Design

### Advanced Topics

- ACID Properties
- Two Phase Locking
- Serializability
- B+ Trees
- Hash Indexing
- Query Execution Plans
- Buffer Management
- Disk Scheduling
- Recovery Algorithms

---

## System Call Based File Handling

This project also explores low-level Linux file handling using raw system calls such as:

```cpp
open()
read()
write()
close()
```

Topics covered:

- File Descriptors
- Kernel Space vs User Space
- Inodes
- VFS (Virtual File System)
- `strace` Analysis
- Page Cache
- Raw System Calls

---

## Compilation

Compile C++ programs using:

```bash
g++ filename.cpp -o output
```

Example:

```bash
g++ Lab_01.cpp -o lab1
```

---

## Execution

Run the executable:

```bash
./lab1
```

---

## Git Workflow

```bash
git init
git add .
git commit -m "ADBMS lab completed"
git push origin main
```

---

## Learning Outcomes

Through this project, the following skills are developed:

- Understanding database internals
- Query optimization techniques
- Linux system programming
- File system architecture
- Transaction and recovery mechanisms
- Practical SQL implementation
- Kernel level file interaction

---

## Future Improvements

- Mini SQL Engine
- Query Parser
- Buffer Pool Manager
- Custom Storage Engine
- Distributed Database Simulation
- WAL (Write Ahead Logging)
- MVCC Implementation

---

## References

- Database System Concepts — Korth
- Operating System Concepts — Galvin
- Linux Manual Pages
- MySQL Documentation
- PostgreSQL Documentation

---

## Author

Prince Kumar

Undergraduation in  Computer Science  
BITS Pilani

---

## License

This project is for educational and learning purposes.
