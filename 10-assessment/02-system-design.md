# System Design Principles

Architecture thinking and engineering design reference for interviews.

---

# Reliability

Goal:

System behaves predictably during failures.

Examples:

- Retry strategy
- Timeout protection
- Fallback handling
- Failure isolation

Questions:

- Single point of failure?
- Recovery strategy?
- Graceful degradation approach?

---

# Scalability

Goal:

Support increasing workload.

Approaches:

Vertical Scaling

↓

Horizontal Scaling

↓

Workload Distribution

Questions:

- Traffic growth handling?
- Resource bottlenecks?
- Scaling boundaries?

---

# Observability

Goal:

Understand system behavior.

Signals:

Logs

↓

Metrics

↓

Tracing

Questions:

- Failure visibility?
- Latency visibility?
- Dependency visibility?

---

# Security

Goal:

Protect systems and information.

Areas:

Authentication

↓

Authorization

↓

Secrets Protection

↓

Least Privilege

Questions:

- Access boundaries?
- Credential handling?
- Sensitive data protection?

---

# Performance

Focus:

- Latency
- Throughput
- Resource efficiency

Questions:

- Bottlenecks?
- Slow dependencies?
- Resource optimization?

---

# Tradeoff Thinking

Examples:

Reliability

vs

Complexity

---

Scalability

vs

Cost

---

Flexibility

vs

Operational Overhead

---

# Interview Framework

Problem

↓

Requirements

↓

Architecture

↓

Workflow

↓

Tradeoffs

↓

Reliability

↓

Scalability

↓

Observability

↓

Security

---

# Quick Revision

Reliable

↓

Scalable

↓

Observable

↓

Secure

↓

Maintainable