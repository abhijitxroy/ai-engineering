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

# AI Agents Assessment — Scenario Based

## Purpose

Evaluate AI agent architecture design, production decision-making, reliability thinking, and system design skills through real engineering scenarios.

This assessment focuses on applying agent concepts to practical engineering problems.

---

## Scenario 1 — Design an AI Deployment Troubleshooting Agent

### Problem Statement

Engineering teams spend significant time investigating deployment failures.

The objective is to reduce troubleshooting effort and improve operational efficiency using AI agents.

---

## Requirements

### Functional Requirements

- Retrieve deployment logs
- Collect monitoring metrics
- Validate configuration
- Identify failure patterns
- Generate remediation guidance

### Non Functional Requirements

- Reliability
- Scalability
- Security
- Observability
- Auditability

---

## High Level Design

Developer

↓

AI Agent Layer

↓

Planning Layer

↓

Tool Integration Layer

├── Deployment Logs

├── Monitoring Platform

├── Configuration Store

└── Documentation System

↓

Analysis Layer

↓

Recommendation Layer

↓

Developer Response

---

## Architecture Discussion

### Planning Layer

Responsibilities:

- Understand troubleshooting goal
- Break problem into steps
- Select required tools
- Manage execution flow

---

### Tool Layer

Responsibilities:

- Retrieve operational information
- Execute approved actions
- Provide system context

Examples:

- Logs
- Metrics
- Configuration
- Deployment metadata

---

### Analysis Layer

Responsibilities:

- Identify failure patterns
- Correlate signals
- Generate possible causes

Examples:

- Configuration mismatch
- Dependency failure
- Resource exhaustion

---

## Workflow

Step 1

Developer reports deployment issue.

↓

Step 2

Agent collects required context.

↓

Step 3

Planning layer creates investigation workflow.

↓

Step 4

Tools retrieve operational information.

↓

Step 5

Agent analyzes results and generates recommendation.

---

## Reliability Considerations

Important areas:

- Retry handling
- Timeout management
- Tool failure handling
- Result validation
- Human approval for sensitive actions

---

# Scenario 2 — Design AI-enabled Internal Developer Platform

## Problem Statement

Engineering teams need faster access to platform capabilities and operational knowledge.

Objective:

Improve developer productivity through AI-assisted platform workflows.

---

## Functional Requirements

- Knowledge retrieval
- Deployment guidance
- Infrastructure recommendations
- Documentation assistance
- Self-service troubleshooting

---

## High Level Design

Developer

↓

Internal Developer Platform

↓

AI Agent Layer

↓

Knowledge Systems

↓

Infrastructure Systems

↓

Response Layer

---

## Platform Engineering Perspective

Potential integrations:

- Developer productivity workflows
- Operational diagnostics
- Engineering knowledge systems
- Self-service automation

---

## Trade-off Discussion

| Area | Consideration |
|---|---|
| Reliability | Predictable agent behavior vs flexibility |
| Security | Capability access vs user productivity |
| Cost | Model usage vs operational value |
| Complexity | Simple workflow vs autonomous capability |

---

# Common Scenario Questions

1. How would you design a production AI agent workflow?

2. How would you handle tool failures?

3. How would you secure agent access?

4. How would you scale agent execution?

5. How would you monitor agent behavior?

---

# Quick Revision

Problem

↓

Requirements

↓

Agent Architecture

↓

Tools

↓

Workflow

↓

Reliability

↓

Security

↓

Observability

---

# Next Assessment

Next: `10-assessment/10-agent-engineering/02-mcp/beginner.md`