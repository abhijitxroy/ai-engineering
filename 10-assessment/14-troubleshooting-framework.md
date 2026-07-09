# Troubleshooting Framework

Operational troubleshooting reference for engineering interviews and production environments.

---

# Goal

Identify issues systematically.

Reduce investigation time.

Improve operational efficiency.

---

# Troubleshooting Process

Problem Reported

↓

Scope Validation

↓

Signal Collection

↓

Hypothesis Formation

↓

Validation

↓

Root Cause Identification

↓

Resolution

↓

Prevention

---

# Step 1 — Scope Validation

Questions:

- What changed?
- Impacted systems?
- Single service or multiple services?
- Recent deployment happened?

Examples:

- Deployment failure
- Latency increase
- Infrastructure issue

---

# Step 2 — Signal Collection

Primary signals:

Logs

↓

Metrics

↓

Tracing

Examples:

Logs:

- Exceptions
- Errors
- Deployment failures

Metrics:

- CPU
- Memory
- Latency
- Error rate

Tracing:

- Dependency visibility
- Service interaction

---

# Step 3 — Hypothesis Formation

Examples:

Deployment Failure

Possible causes:

- Configuration issue
- Infrastructure issue
- Dependency issue
- Resource exhaustion

Goal:

Avoid random debugging.

Use evidence.

---

# Step 4 — Validation

Questions:

Can issue reproduce?

↓

Can issue isolate?

↓

Can evidence support assumption?

---

# Step 5 — Root Cause Analysis

Goal:

Identify underlying reason.

Examples:

Incorrect:

Restart service repeatedly.

Correct:

Find why service failed.

Potential causes:

- Configuration drift
- Infrastructure failure
- Deployment defect
- Dependency issue

---

# Step 6 — Resolution

Examples:

- Configuration correction
- Infrastructure remediation
- Deployment rollback
- Capacity adjustment

---

# Step 7 — Prevention

Questions:

How prevent recurrence?

Examples:

- Monitoring improvements
- Validation automation
- Better alerting
- Documentation updates

---

# Platform Engineering Perspective

Potential improvements:

- Self-service diagnostics
- Automated troubleshooting
- Operational visibility
- Knowledge discovery

---

# Interview Framework

Problem

↓

Signals

↓

Hypothesis

↓

Validation

↓

Root Cause

↓

Resolution

↓

Prevention

---

# Quick Revision

Logs

+

Metrics

+

Tracing

↓

Evidence

↓

Root Cause

↓

Fix

↓

Prevent Recurrence