# Latency Investigation

Production troubleshooting scenario focused on latency investigation, bottleneck identification, and performance analysis.

Objective:

Build systematic investigation capability for performance problems.

---

## Scenario

Engineering team reports:

Application response time increased.

Symptoms:

- Slow API response
- User experience degradation
- Timeout increase
- Throughput reduction

Goal:

Identify bottleneck.

Improve performance.

Prevent recurrence.

---

## Investigation Framework

Latency Reported

↓

Scope Validation

↓

Metrics Investigation

↓

Tracing Analysis

↓

Logs Validation

↓

Dependency Investigation

↓

Infrastructure Validation

↓

Hypothesis Formation

↓

Validation

↓

Root Cause

↓

Optimization

↓

Monitoring

---

## Step 1 — Scope Validation

Questions:

When latency started?

Examples:

- After deployment
- Traffic increase
- Infrastructure change

Questions:

Single API affected?

↓

Multiple services affected?

↓

Regional impact?

Examples:

- Single endpoint
- Multiple endpoints
- Entire application

---

## Step 2 — Metrics Investigation

Validate:

Latency

↓

CPU Utilization

↓

Memory Utilization

↓

Request Throughput

↓

Error Rate

Examples:

High CPU

↓

Compute bottleneck

Memory pressure

↓

Garbage collection impact

Traffic spike

↓

Capacity issue

---

## Step 3 — Tracing Investigation

Workflow:

Request

↓

Gateway

↓

Service A

↓

Service B

↓

Database

↓

Response

Questions:

Which component slow?

Examples:

Database latency high.

↓

Database bottleneck.

Dependency API slow.

↓

External dependency bottleneck.

---

## Step 4 — Logs Validation

Examples:

Application logs:

- Exceptions
- Retry events
- Timeout events

Infrastructure logs:

- Resource pressure
- Network issues

Questions:

Errors increasing?

↓

Retries increasing?

↓

Timeout events present?

---

## Step 5 — Dependency Validation

Examples:

Database

↓

Cache

↓

External APIs

↓

Infrastructure dependencies

Questions:

Dependency latency increased?

↓

Connection failures?

↓

Timeout increase?

---

## Step 6 — Infrastructure Validation

Validate:

CPU

↓

Memory

↓

Disk

↓

Network

Examples:

High CPU utilization.

↓

Infrastructure bottleneck.

Network saturation.

↓

Response degradation.

---

## Step 7 — Hypothesis Formation

Examples:

Potential causes:

- Infrastructure bottleneck
- Dependency latency
- Traffic growth
- Database pressure
- Inefficient processing

Goal:

Use evidence.

Avoid random optimization.

---

## Step 8 — Validation

Questions:

Can issue reproduce?

↓

Can bottleneck isolate?

↓

Evidence supports assumption?

---

## Step 9 — Optimization

Examples:

- Capacity increase
- Query optimization
- Cache improvement
- Infrastructure scaling
- Dependency optimization

Goal:

Reduce latency safely.

---

## Step 10 — Prevention

Examples:

- Better alerting
- Capacity planning
- Performance monitoring
- Load testing

Goal:

Reduce recurrence.

---

## Platform Engineering Perspective

Potential improvements:

- Performance dashboards
- Self-service diagnostics
- Automated visibility
- Capacity insights

---

## Interview Questions

1. First step during latency investigation?

2. Metrics vs tracing usage?

3. CPU high but latency normal possible?

4. Dependency bottleneck identification?

5. Optimization approaches?

---

## Quick Revision

Latency

↓

Metrics

↓

Tracing

↓

Logs

↓

Dependencies

↓

Root Cause

↓

Optimization