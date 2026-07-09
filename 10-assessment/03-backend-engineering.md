

# Backend Engineering Assessment

## Purpose

Evaluate backend engineering knowledge including API design, service development, data handling, reliability, and production practices.

This assessment validates the ability to design and build maintainable backend systems.

---

## Assessment Scope

Topics covered:

- Backend architecture
- REST API design
- Service design
- Request processing
- Error handling
- Authentication and authorization
- Database integration
- Testing
- Performance
- Production troubleshooting

---

## Assessment Format

Three levels:

### Level 1 — Concept Understanding

Validates backend fundamentals.

### Level 2 — Engineering Scenarios

Validates practical backend decisions.

### Level 3 — Senior Engineer Decisions

Validates production backend design thinking.

---

# Level 1 — Concept Understanding

## Q1. What is the main purpose of a REST API?

A. Store application source code

B. Provide communication between systems using defined resources and operations

C. Replace databases

D. Remove the need for authentication

---

## Q2. What is idempotency in API design?

A. API always executes faster

B. Repeating the same request produces the same result

C. API does not require validation

D. API stores data permanently

---

## Q3. What is the purpose of dependency injection?

A. Increase code duplication

B. Reduce coupling by providing dependencies externally

C. Remove interfaces

D. Avoid testing

---

# Level 2 — Engineering Scenarios

## Q4. An API endpoint takes 5 seconds to respond.

Investigation areas:

- Database query performance
- External service latency
- Application profiling
- Thread utilization
- Network latency

What should be done first?

Expected thinking:

Measure and identify the bottleneck before changing architecture.

---

## Q5. A backend service receives duplicate payment requests due to client retries.

What design approach prevents duplicate transactions?

A. Increase server memory

B. Idempotency keys

C. Remove retries

D. Add more API endpoints

---

## Q6. A service contains controllers with business logic and database queries directly inside them.

What improvement is recommended?

Expected thinking:

Separate responsibilities using layers:

- Controller layer
- Service layer
- Repository/data layer

---

# Level 3 — Senior Engineer Decisions

## Q7. Design a backend service expected to handle millions of requests daily.

Important considerations:

- API scalability
- Caching strategy
- Database design
- Rate limiting
- Security
- Observability
- Deployment strategy

---

## Q8. A production API starts returning intermittent failures.

Possible investigation areas:

- Application logs
- Error rates
- Dependency health
- Recent deployments
- Infrastructure metrics

---

## Q9. A team wants to introduce asynchronous processing.

When is it appropriate?

Expected thinking:

- Long-running operations
- Independent workflows
- Improved responsiveness
- Event-driven processing

Trade-offs:

- Complexity
- Monitoring requirements
- Event consistency

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
| API Design | | |
| Service Architecture | | |
| Security | | |
| Performance | | |
| Testing | | |
| Reliability | | |

---

# Weak Areas

Identified after assessment completion.

---

# Recommended Resources

Focused resources will be added based on assessment results.

---

# Practical Application

Apply backend engineering concepts through real production projects.

---

# Next Assessment

Next: `10-assessment/04-database.md`
