# 📚 Database Course Documentation

Welcome to the **Database Course Documentation** repository. This project explores foundational database concepts through comparative analysis, visual mind mapping, role definitions, and research on modern database architectures. The goal is to develop strong research and analytical reporting skills while presenting findings in a clear, well-documented format.

---

## 📁 Table of Contents

1. [Flat File Systems vs. Relational Databases](#1-flat-file-systems-vs-relational-databases)
2. [DBMS Advantages – Mind Map](#2-dbms-advantages--mind-map)
3. [Roles in a Database System](#3-roles-in-a-database-system)
4. [Types of Databases](#4-types-of-databases)
5. [Cloud Storage and Databases](#5-cloud-storage-and-databases)

---

## 1. 🆚 Flat File Systems vs. Relational Databases

| Feature           | Flat File System                          | Relational Database                          |
|------------------|-------------------------------------------|----------------------------------------------|
| **Structure**     | Simple text or binary files               | Tables with rows and columns (schema-based)  |
| **Data Redundancy** | High – repeated data across files         | Low – normalized data reduces duplication    |
| **Relationships** | None – manual linking                     | Built-in via foreign keys and joins          |
| **Example Usage** | CSV files, log files                      | MySQL, PostgreSQL, Oracle                    |
| **Drawbacks**     | Poor scalability, no integrity checks     | Requires setup and maintenance               |

📌 *Visual comparison diagram available in `assets/diagrams/flat_vs_relational.png`*

---

## 2. 🧠 DBMS Advantages – Mind Map

The following mind map illustrates the key advantages of using a Database Management System (DBMS):

![DBMS Mind Map](/mindmap.png)

**Highlights:**
- 🔒 **Security** – Access control, encryption
- ✅ **Integrity** – Constraints, validation
- 💾 **Backup** – Scheduled backups, recovery tools
- 📉 **Redundancy** – Normalization, efficient storage
- 🔄 **Concurrency** – Transaction management
- 🤝 **Data Sharing** – Multi-user access

---

## 3. 👥 Roles in a Database System

| Role                  | Responsibilities                                                                 |
|-----------------------|----------------------------------------------------------------------------------|
| **System Analyst**        | Gathers requirements, defines system scope, interfaces with stakeholders         |
| **Database Designer**     | Creates ER diagrams, defines schema, normalization                              |
| **Database Developer**    | Implements schema, writes SQL queries, stored procedures                        |
| **Database Administrator (DBA)**| Manages DB performance, backups, security, user roles                           |
| **Application Developer** | Integrates DB with applications, handles API/database calls                     |
| **BI Developer**          | Designs reports, dashboards, queries for insights                               |

---

## 4. 🗃️ Types of Databases

### 🔄 Relational vs. Non-Relational

- **Relational:** Structured, SQL-based (e.g., MySQL, PostgreSQL)
- **Non-Relational:** Flexible schema, document/key-value (e.g., MongoDB, Cassandra)

### 🌐 Centralized vs. Distributed vs. Cloud

| Type         | Description                                | Example Use Case                          |
|--------------|--------------------------------------------|-------------------------------------------|
| **Centralized**  | Single location, easier control            | Small businesses, local apps              |
| **Distributed**  | Multiple nodes, high availability          | Global apps, real-time systems            |
| **Cloud**        | Hosted by providers, scalable              | SaaS platforms, mobile apps               |

📌 *Architecture diagrams available in `assets/diagrams/cloud_db_architecture.png`*

---

## 5. ☁️ Cloud Storage and Databases

### What is Cloud Storage?

Cloud storage refers to remote data storage accessible via the internet. It supports database functionality by hosting DB engines, backups, and scaling infrastructure.

### ✅ Advantages of Cloud-Based Databases

- Scalability and elasticity
- High availability and disaster recovery
- Managed services (e.g., backups, updates)
- Cost-effective for dynamic workloads

### ⚠️ Disadvantages

- Vendor lock-in
- Latency and performance variability
- Data privacy and compliance concerns

**Examples:**
- Azure SQL
- Amazon RDS
- Google Cloud Spanner

---



---
