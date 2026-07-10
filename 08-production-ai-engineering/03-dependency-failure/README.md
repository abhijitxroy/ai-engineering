# Dependency Failure Investigation

Production AI Engineering scenario focused on dependency failures affecting AI applications, model services, external AI APIs, and recovery strategies.

Objective:

Build systematic dependency investigation capability for production AI systems.

---

## Scenario

Engineering team reports:

Application unstable.

Symptoms:

- API timeout increase
- Request failures
- Partial functionality unavailable
- Increased retry events

Goal:

Identify dependency issue.

Restore stability.

Prevent recurrence.

---

## Investigation Framework

Failure Reported

↓

Scope Validation

↓

Dependency Identification

↓

Metrics Investigation

↓

Tracing Analysis

↓

Logs Validation

↓

Infrastructure Validation

↓

Hypothesis Formation

↓

Validation

↓

Root Cause

↓

Recovery

↓

Prevention

---

## Step 1 — Scope Validation

Questions:

Single feature impacted?

↓

Multiple features impacted?

↓

Entire platform impacted?

Examples:

- AI workflow unavailable
- Model service issue
- External AI API unavailable
- Data source instability

Questions:

Recent changes happened?

Examples:

- Deployment
- Infrastructure modification
- Dependency upgrade

---

## Step 2 — Dependency Identification

Potential dependencies:

AI Application

↓

Model Service

↓

Data Sources

↓

External AI APIs

↓

Authentication Services

↓

Supporting Services

Questions:

Which dependency failing?

Goal:

Identify impacted component.

---

## Step 3 — Metrics Investigation

Validate:

Error Rate

↓

Latency

↓

Retry Count

↓

Timeout Count

↓

Request Failure Rate

Examples:

Timeout increase

↓

Dependency responsiveness issue

Retry increase

↓

Transient failures

---

## Step 4 — Tracing Investigation

Workflow:

Request

↓

Gateway

↓

Application

↓

Dependency

↓

Response

Examples:

Application healthy.

↓

Database response delayed.

↓

Dependency bottleneck identified.

Goal:

Identify slow or unavailable component.

---

## Step 5 — Logs Validation

Examples:

Application Logs:

- Connection timeout
- Authentication failure
- Retry events

Infrastructure Logs:

- Resource pressure
- Network issues

Dependency Logs:

- Availability issue
- Service instability

Questions:

Dependency reachable?

↓

Error pattern visible?

---

## Step 6 — Infrastructure Validation

Validate:

AI Application Resources

↓

Model Service Availability

↓

Data Access

↓

Network Communication

Examples:

Network saturation.

↓

Dependency communication impact.

Resource exhaustion.

↓

Dependency instability.

---

## Step 7 — Hypothesis Formation

Potential causes:

- External API unavailable
- Database instability
- Cache failure
- Authentication service issue
- Infrastructure dependency problem

Goal:

Evidence driven investigation.

Avoid random debugging.

---

## Step 8 — Recovery Approaches

Examples:

Retry

↓

Fallback

↓

Circuit Breaker

↓

Graceful Degradation

↓

Dependency Recovery

Goal:

Restore safely.

Reduce impact.

---

## Step 9 — Prevention

Examples:

- Better alerting
- Dependency monitoring
- Circuit breaker protection
- Timeout handling
- Retry strategy validation

Goal:

Reduce recurrence.

Improve resilience.

---

## Reliability Patterns

Useful approaches:

Retry Pattern

↓

Timeout Pattern

↓

Circuit Breaker

↓

Fallback Strategy

↓

Graceful Degradation

---

## Interview Questions

1. Dependency timeout handling?

2. Circuit breaker purpose?

3. Retry tradeoffs?

4. Graceful degradation benefits?

5. Dependency visibility improvements?

---

## Quick Revision

Dependency Failure

↓

Metrics

↓

Tracing

↓

Logs

↓

Validation

↓

Recovery

↓

Prevention