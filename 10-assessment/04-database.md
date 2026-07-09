

# Database Assessment

## Purpose

Evaluate database design knowledge, data modeling skills, query optimization understanding, and production database decision-making.

This assessment validates the ability to design reliable and efficient data systems.

---

## Assessment Scope

Topics covered:

- Data modeling
- Relational databases
- SQL concepts
- Indexing
- Transactions
- ACID properties
- Database performance
- Scaling strategies
- Data consistency
- Production troubleshooting

---

## Assessment Format

Three levels:

### Level 1 — Concept Understanding

Validates database fundamentals.

### Level 2 — Engineering Scenarios

Validates practical database decisions.

### Level 3 — Senior Engineer Decisions

Validates production data architecture thinking.

---

# Level 1 — Concept Understanding

## Q1. What is the purpose of database normalization?

A. Increase duplicate data

B. Reduce redundancy and improve data consistency

C. Remove indexes

D. Replace transactions

---

## Q2. What does ACID represent?

A. Availability, Consistency, Indexing, Distribution

B. Atomicity, Consistency, Isolation, Durability

C. Accuracy, Control, Integration, Deployment

D. Access, Cache, Identity, Data

---

## Q3. What is the purpose of an index?

A. Store application logs

B. Improve query lookup performance

C. Replace database tables

D. Remove constraints

---

# Level 2 — Engineering Scenarios

## Q4. A query that was fast initially becomes slow as the table grows to millions of rows.

What should be investigated?

Expected thinking:

- Query execution plan
- Missing indexes
- Data growth patterns
- Table partitioning options
- Query optimization

---

## Q5. An application updates two related tables. The second update fails after the first succeeds.

What database feature helps maintain consistency?

A. Caching

B. Transaction management

C. Load balancing

D. Replication only

---

## Q6. A read-heavy application experiences database load issues.

Possible improvements:

- Read replicas
- Caching
- Query optimization
- Proper indexing

What should be done first?

Expected thinking:

Measure the bottleneck before applying scaling solutions.

---

# Level 3 — Senior Engineer Decisions

## Q7. Design the database strategy for an expense tracking application.

Consider:

- User data
- Transactions
- Categories
- Reports
- Data growth
- Security
- Backup and recovery

---

## Q8. A globally distributed application requires fast reads across regions.

What trade-offs should be considered?

Expected thinking:

- Replication strategy
- Consistency requirements
- Latency
- Conflict handling
- Operational complexity

---

## Q9. Production issue:

```
Application latency: High
CPU: Normal
Memory: Normal
Database CPU: High
Slow queries increasing
```

Investigation areas:

- Query plans
- Missing indexes
- Lock contention
- Connection pool usage
- Recent schema changes

---

# Answer Key

To be completed after assessment execution.

---

# Explanation

Detailed explanations will be added after answering questions.

---

# Score Tracking

| Topic | Score | Status |
|---|---|---|
| Data Modeling | | |
| SQL | | |
| Transactions | | |
| Performance | | |
| Scaling | | |
| Consistency | | |

---

# Weak Areas

Identified after assessment completion.

---

# Recommended Resources

Focused resources will be added based on assessment results.

---

# Practical Application

Apply database concepts through real engineering projects.

---

# Next Assessment

Next: `10-assessment/05-distributed-systems.md`
