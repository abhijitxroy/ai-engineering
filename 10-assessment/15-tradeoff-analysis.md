# Tradeoff Analysis Assessment

## Purpose

Evaluate engineering decision-making skills including identifying constraints, comparing alternatives, understanding impacts, and selecting appropriate solutions.

This assessment validates architecture and system design tradeoff thinking.

---

## Assessment Scope

Topics covered:

- Reliability tradeoffs
- Scalability decisions
- Cost optimization
- Simplicity vs capability
- Performance considerations
- Security tradeoffs
- Platform engineering decisions

---

# Level 1 — Concept Understanding

## Q1. Why is tradeoff analysis important?

Expected thinking:

- Understand consequences of decisions
- Balance competing goals
- Select suitable solutions

---

## Q2. What should be considered before making an engineering decision?

Expected thinking:

- Requirements
- Constraints
- Benefits
- Risks
- Operational impact

---

## Q3. Why can improving one area negatively impact another area?

Expected thinking:

- Engineering systems have competing priorities
- Optimization has limitations

---

# Level 2 — Engineering Scenarios

## Q4. Reliability vs Complexity

A team wants to add multiple retry mechanisms.

Analyze:

Benefits:

- Better failure recovery
- Improved resilience

Tradeoffs:

- Higher complexity
- Additional operational behavior

---

## Q5. Scalability vs Cost

A system requires horizontal scaling.

Analyze:

Benefits:

- Better workload handling
- Improved availability

Tradeoffs:

- Higher infrastructure cost
- More operational management

---

## Q6. Security vs Developer Productivity

A platform team introduces additional approval workflows.

Analyze:

Benefits:

- Better protection
- Reduced security risk

Tradeoffs:

- Slower developer workflows
- Additional process overhead

---

# Level 3 — Engineering Thinking

## Q7. Analyze a system design decision.

Framework:

Requirement

↓

Constraint

↓

Decision

↓

Benefit

↓

Tradeoff

↓

Mitigation

---

## Q8. Design decision:

A team chooses distributed architecture over a simple single service.

Evaluate:

Benefits:

- Better scalability
- Better specialization

Tradeoffs:

- Communication complexity
- Operational overhead

Mitigation:

- Clear boundaries
- Observability
- Automation

---

## Q9. Production decision:

```
Performance: Improved
Cost: Increased
Complexity: Increased
```

Evaluate:

- Is the optimization justified?
- What constraints matter?
- What mitigation can reduce impact?

---

# Answer Key

To be completed after assessment execution.

---

# Score Tracking

| Topic | Score | Status |
|---|---|---|
| Decision Making | | |
| Reliability Tradeoffs | | |
| Scalability Tradeoffs | | |
| Cost Analysis | | |
| Security Decisions | | |

---

# Weak Areas

Identified after assessment completion.

---

# Recommended Resources

Focused resources will be added based on assessment results.

---

# Practical Application

Apply tradeoff analysis during architecture reviews and engineering decisions.

---

# Next Assessment

Next: `10-assessment/16-engineering-principles.md`
