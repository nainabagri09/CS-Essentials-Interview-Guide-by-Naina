# 🗄️ DBMS — Essential Interview Notes  

This document contains 20+ important DBMS concepts explained in a simple, interview-friendly manner.  
Useful for quick revision and clearing fundamentals.

---

## 1️⃣ What is DBMS?  
DBMS is software used to store, manage, and retrieve data efficiently.  
It provides security, integrity, and controlled access.

**Advantages:**  
- Data integrity & security  
- Fast data retrieval  
- Concurrent access  
- Backup & recovery  

**Real-life:** Banking systems storing transactions.

---

## 2️⃣ What is a Database?  
A structured collection of data stored in an organized way.  
**Example:** Library database containing books & borrower details.

---

## 3️⃣ What is a Database System?  
Database System = DBMS + Database + Applications interacting with it.

**Example:** E-commerce apps handling users, products, orders.

---

## 4️⃣ What is RDBMS?  
Stores data in tables (rows & columns). Follows ACID properties.

**Examples:** MySQL, PostgreSQL, Oracle.

---

## 5️⃣ Types of Database Languages  
- **DDL:** CREATE, ALTER, DROP  
- **DML:** SELECT, INSERT, UPDATE, DELETE  
- **DCL:** GRANT, REVOKE  
- **TCL:** COMMIT, ROLLBACK  

---

## 6️⃣ ACID Properties  
Ensures reliable transaction processing.

| Property | Meaning |
|---------|---------|
| Atomicity | All or none |
| Consistency | Data remains valid |
| Isolation | Transactions don’t interfere |
| Durability | Changes persist permanently |

**Example:** Money transfer in a bank.

---

## 7️⃣ Vertical vs Horizontal Scaling  

| Type | Meaning | Example |
|------|---------|---------|
| Vertical | Add more power to 1 server | Increase RAM/CPU |
| Horizontal | Add more servers | Distributed systems |

---

## 8️⃣ What is Sharding?  
Breaking a large database into smaller pieces (shards).  
Used for high traffic systems like Instagram, Facebook.

---

## 9️⃣ Keys in DBMS  
- **Primary Key** – Unique ID  
- **Foreign Key** – Links tables  
- **Candidate Key** – Possible unique keys  
- **Composite Key** – Multiple columns  
- **Unique Key** – Allows NULL  

---

## 🔟 Types of Relationships  
- **1:1** → Person–Passport  
- **1:N** → Department–Employees  
- **M:N** → Students–Courses  

---

## 1️⃣1️⃣ Data Abstraction  
- **Physical:** How data is stored  
- **Logical:** What data is stored  
- **View:** How data is shown to users  

---

## 1️⃣2️⃣ Indexing  
Improves search speed using structures like B-Trees & Hashing.  
**Pros:** Fast queries  
**Cons:** Slows down writes  

**Example:** Google search indexing.

---

## 1️⃣3️⃣ What is DDL?  
Defines structure (CREATE, ALTER, DROP).  
Used to create new tables or modify schema.

---

## 1️⃣4️⃣ What is DML?  
Used to retrieve or modify data (SELECT, INSERT, UPDATE, DELETE).

---

## 1️⃣5️⃣ Normalization  
Reduces redundancy & improves consistency.

| NF | Meaning |
|----|---------|
| 1NF | No repeating groups |
| 2NF | No partial dependency |
| 3NF | No transitive dependency |
| BCNF | Stronger 3NF |

---

## 1️⃣6️⃣ Denormalization  
Combines tables for faster reads.  
Used in analytics, reporting systems.

---

## 1️⃣7️⃣ Functional Dependency  
Attribute A → determines Attribute B.  
**Example:** StudentID → StudentName.

---

## 1️⃣8️⃣ E-R Model  
Represents data in form of entities, attributes, and relationships.

**Example:**  
Student (Entity) — Enrolls → Course (Entity)

---

## 1️⃣9️⃣ Conflict Serializability  
Ensures concurrent transactions behave like serial execution.  
Used in banking to avoid inconsistent updates.

---

## 2️⃣0️⃣ Concurrency Control Protocols (CCP)  
Ensures safe concurrent transactions.

- Lock-based  
- Timestamp-based  
- Optimistic concurrency  

---

## 2️⃣1️⃣ Entity, Entity Type, Entity Set, Weak Entity  
- **Entity:** Object (Student)  
- **Entity Type:** Category (All students)  
- **Entity Set:** Collection of entities  
- **Weak Entity:** Needs another entity to identify  

---

## 2️⃣2️⃣ SQL Commands Types  
- DDL  
- DML  
- DCL  
- TCL  

---

## 2️⃣3️⃣ Nested Queries  
A query inside another query.

```sql
SELECT name 
FROM employees 
WHERE id IN (
  SELECT employee_id FROM department WHERE name = 'HR'
);

### 🎥 YT Links  
- [Vivek Gupta](https://youtu.be/2LOpVPMiGUw?si=6_RlmMUln4L9ghxq)  
- [Gate Smashers Playlist](https://youtube.com/playlist?list=PLn32mJ8RhQWiIgEoD2U3gHoHC3ApDOHas&si=bfc4luA78RhDiYVl)
