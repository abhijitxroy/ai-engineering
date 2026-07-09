# Software Engineering Assessment

## Purpose

Evaluate software engineering fundamentals, design thinking, and production decision-making.

This assessment validates existing engineering knowledge, identifies weak areas, and guides focused learning.

---

## Assessment Scope

Topics covered:

- Object-oriented programming
- SOLID principles
- Design principles
- Code quality
- API design
- Testing concepts
- Architecture thinking
- Production troubleshooting
- Engineering trade-offs

---

## Assessment Format

Three levels:

### Level 1 — Concept Understanding

Validates fundamental knowledge.

### Level 2 — Engineering Scenarios

Validates practical application.

### Level 3 — Senior Engineer Decisions

Validates architecture thinking and trade-off decisions.

---

# Level 1 — Concept Understanding

## Q1. What is the primary purpose of encapsulation in object-oriented design?

A. Increase code execution speed  
B. Hide internal implementation details and control access  
C. Remove the need for inheritance  
D. Replace interfaces  

---

## Q2. What does high cohesion mean?

A. A module has many dependencies  
B. A module has closely related responsibilities  
C. A module contains many classes  
D. A module uses inheritance extensively  

---

## Q3. What is the main problem with tight coupling?

A. Better performance  
B. Easier testing  
C. Changes in one component affect many others  
D. Reduced memory usage  

---

# Level 2 — Engineering Scenarios

## Q4. A service class has:

- Database access
- Email sending
- Business rules
- Logging
- Validation

What design principle is violated?

A. Open/Closed Principle  
B. Single Responsibility Principle  
C. Dependency Inversion Principle  
D. Interface Segregation Principle  

---

## Q5. A REST API works correctly but response time increases as traffic grows.

First investigation should focus on:

A. Rewrite the application  
B. Increase server memory immediately  
C. Identify bottlenecks using metrics and profiling  
D. Add more features  

---

## Q6. A developer creates a shared utility class used by 50 modules. Every change breaks multiple applications.

What is the likely issue?

A. Excessive abstraction  
B. High coupling  
C. Low cohesion  
D. Poor naming  

---

# Level 3 — Senior Engineer Decisions

## Q7. Production issue:

```
CPU: 100%
Memory: Normal
Database: Healthy
Latency: Increasing
```

What are the first investigation areas?

Expected thinking:

- Thread exhaustion
- CPU-intensive operations
- Blocking calls
- External dependency latency
- Recent deployments

---

## Q8. You are designing a payment processing system.

Which qualities are most important?

Select all:

- Reliability
- Idempotency
- Security
- Observability
- Scalability

---

## Q9. A team wants to split a monolith into microservices.

What should be evaluated before migration?

Expected thinking:

- Business boundaries
- Team ownership
- Deployment complexity
- Operational maturity
- Data ownership

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
| OOP | | |
| SOLID | | |
| Design Patterns | | |
| API Design | | |
| Testing | | |
| Architecture | | |

---

# Weak Areas

Identified after assessment completion.

---

# Recommended Resources

Focused resources will be added based on assessment results.

---

# Practical Application

Apply concepts through real engineering projects.

---

# Next Assessment

Next: `10-assessment/02-system-design.md`
