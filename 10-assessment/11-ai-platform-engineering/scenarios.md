# AI Platform Engineering Assessment — Scenario Based

## Purpose

Evaluate AI platform engineering architecture skills through realistic platform design scenarios covering Internal Developer Platforms, AI-assisted workflows, reliability, security, and operational tradeoffs.

This assessment focuses on architecture thinking and engineering decision-making.

---

## Assessment Scope

Topics covered:

- Internal Developer Platform (IDP)
- Developer Experience (DevEx)
- Platform architecture
- Self-service workflows
- AI-enabled engineering platforms
- Reliability
- Security
- Observability
- Engineering tradeoffs

---

# Scenario 1 — Design Internal Developer Platform (IDP)

## Problem Statement

Engineering teams experience operational bottlenecks:

- Manual infrastructure provisioning
- Slow developer onboarding
- Fragmented documentation
- Inconsistent deployment workflows
- Heavy dependency on platform teams

Objective:

Improve Developer Experience and engineering productivity through a standardized Internal Developer Platform.

---

## Requirements

### Functional Requirements

Platform should provide:

- Self-service infrastructure provisioning
- Service templates
- Deployment workflows
- Documentation discovery
- CI/CD integration
- Operational visibility
- Environment management

---

### Non-Functional Requirements

#### Reliability

Platform should provide predictable and reliable developer workflows.

#### Scalability

Support multiple engineering teams and services.

#### Security

Protect platform capabilities and infrastructure access.

#### Standardization

Reduce workflow differences across teams.

---

# High Level Design

Developer

↓

Developer Portal

↓

Platform APIs

↓

Provisioning Layer

↓

Infrastructure Layer

↓

Delivery Layer

↓

Observability Layer

↓

Operations

---

# Component Design

## Developer Portal

Capabilities:

- Service catalog
- Templates
- Documentation
- Self-service workflows

---

## Provisioning Layer

Capabilities:

- Infrastructure creation
- Environment management
- Configuration management

---

## Delivery Layer

Capabilities:

- CI/CD automation
- Validation
- Release workflows
- Deployment management

---

## Observability Layer

Capabilities:

- Metrics
- Logs
- Tracing
- Alerts

---

# Low Level Workflow

Developer requests service creation.

↓

Template selected.

↓

Infrastructure provisioned.

↓

CI/CD configured.

↓

Deployment executed.

↓

Observability enabled.

↓

Service available.

---

# Reliability Considerations

Consider:

- Validation controls
- Retry mechanisms
- Failure recovery
- Operational monitoring
- Dependency management

---

# Security Considerations

Consider:

- Authentication
- Authorization
- Role-based access control
- Secret management
- Audit logging

---

# Scenario 2 — Design AI-enabled Developer Platform

## Problem Statement

Engineering teams spend significant time searching documentation, troubleshooting failures, and understanding operational systems.

Goal:

Reduce engineering friction using AI-assisted platform capabilities.

---

## Functional Requirements

Platform should support:

- Documentation assistance
- Troubleshooting guidance
- Infrastructure recommendations
- Knowledge retrieval
- Operational insights

---

# High Level Design

Developer

↓

Developer Portal

↓

AI Layer

↓

Knowledge Layer

↓

Operational Systems

↓

Response Layer

---

# AI Integration Examples

## Knowledge Discovery

Developer asks:

How deployment workflow operates.

↓

Relevant knowledge retrieved.

↓

AI response generated.

---

## Troubleshooting Assistance

Developer reports deployment issue.

↓

Operational signals collected.

↓

AI analyzes context.

↓

Recommendation generated.

---

# Engineering Decisions

Consider:

- AI model integration
- Knowledge quality
- Data access boundaries
- Response accuracy
- Human approval requirements

---

# Tradeoffs

| Area | Consideration |
|---|---|
| Simplicity | Faster implementation vs limited capability |
| Capability | More automation vs higher complexity |
| Security | More access vs stronger restrictions |
| Cost | AI processing vs productivity improvement |

---

# Common Scenario Questions

1. Design an Internal Developer Platform architecture.

2. How does platform engineering improve developer productivity?

3. What reliability mechanisms are required?

4. How can AI improve developer workflows?

5. What security controls are required for AI-enabled platforms?

6. How do you measure platform success?

---

# Quick Revision

Problem

↓

Requirements

↓

Architecture

↓

Workflow

↓

Reliability

↓

Security

↓

Tradeoffs

↓

Developer Experience

---

# Next Assessment

Next: `10-assessment/12-production-ai-engineering.md`
