# AI Agents - Scenario Based

Architecture discussions and system design preparation.

---

# Scenario 1

## Design an AI Deployment Troubleshooting Agent

### Problem Statement

Engineering teams spend significant time investigating deployment failures.

The objective is to reduce troubleshooting effort and improve operational efficiency.

---

## Requirements

### Functional Requirements

- Retrieve deployment logs
- Collect monitoring metrics
- Validate configuration
- Identify failure patterns
- Generate remediation guidance

---

### Non Functional Requirements

- Reliability
- Scalability
- Security
- Observability

---

## High Level Design

Developer

↓

Agent Layer

↓

Planning Layer

↓

Tool Layer

├── Deployment Logs

├── Monitoring Platform

├── Configuration Store

└── Documentation System

↓

Analysis Layer

↓

Recommendation Engine

↓

Developer Response

---

## Mid Level Components

### Planning Layer

Break investigation into executable steps.

---

### Tool Layer

Retrieve operational information.

Examples:

- Logs
- Metrics
- Configuration

---

### Analysis Layer

Identify patterns.

Examples:

- Failed deployment
- Configuration mismatch
- Resource issue

---

## Low Level Workflow

Step 1

Developer reports issue.

↓

Step 2

Planning layer creates execution strategy.

↓

Step 3

Collect operational signals.

↓

Step 4

Analyze findings.

↓

Step 5

Generate remediation recommendation.

---

## Reliability Considerations

Examples:

- Retry strategy
- Timeout handling
- Validation layer

---

## Platform Engineering Perspective

Potential Internal Developer Platform integration:

- Self-service troubleshooting
- Developer productivity
- Operational diagnostics

---

# Scenario 2

## Design AI-enabled Internal Developer Platform

### Problem Statement

Engineering teams require faster access to platform capabilities.

Objective:

Improve Developer Experience and reduce operational friction.

---

## Functional Requirements

- Knowledge retrieval
- Deployment guidance
- Infrastructure recommendations
- Documentation access

---

## High Level Design

Developer

↓

Internal Developer Platform

↓

Agent Layer

↓

Knowledge Systems

↓

Infrastructure Systems

↓

Response Layer

---

## Discussion Areas

Tradeoffs:

- Reliability vs complexity
- Security vs accessibility
- Cost vs operational capability

---

# Common Interview Questions

1. Design deployment troubleshooting workflow.

2. Failure handling strategy?

3. Scaling considerations?

4. Security boundaries?

5. Observability approach?

---

# Quick Revision

Problem

↓

Requirements

↓

High Level Design

↓

Mid Level Components

↓

Workflow

↓

Tradeoffs

↓

Platform Engineering Integration
