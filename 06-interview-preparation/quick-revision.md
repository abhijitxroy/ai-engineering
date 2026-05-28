# Quick Revision

Fast engineering revision notes before interviews.

Objective:

Quick refresh of concepts, workflows, architecture understanding, and discussion areas.

---

# AI Agents

### Definition

Software systems capable of:

- Reasoning
- Planning
- Tool usage
- Execution

toward achieving defined objectives.

---

### Core Components

Model

↓

Memory

↓

Planning

↓

Tools

↓

Execution

---

### Workflow

User Request

↓

Context Collection

↓

Planning

↓

Tool Usage

↓

Execution

↓

Response

---

### Key Interview Points

- Agent vs traditional automation
- Single Agent vs Multi-Agent
- Planning layer responsibility
- Tool interaction model
- Memory considerations
- Reliability approaches

---

### Quick Recall

AI Agent

=

Reason

+

Plan

+

Execute

---

# MCP (Model Context Protocol)

### Definition

Protocol enabling AI systems to connect with external tools, systems, and contextual information sources.

---

### Components

Host

↓

Client

↓

Server

---

### Workflow

AI Application

↓

MCP Client

↓

MCP Server

↓

External Systems

↓

Context Returned

---

### Key Interview Points

- Problem MCP solves
- Architecture components
- Integration benefits
- Context sharing approach
- Platform Engineering relevance

---

### Quick Recall

MCP

=

Connectivity

+

Context

+

Tool Integration

---

# A2A (Agent-to-Agent)

### Definition

Distributed coordination model enabling multiple execution systems to collaborate.

---

### Core Concepts

- Coordination
- Delegation
- Aggregation
- Distributed execution

---

### Workflow

Coordinator

↓

Execution Distribution

↓

Aggregation

↓

Response

---

### Key Interview Points

- Why multi-agent systems
- Communication patterns
- Coordination challenges
- Reliability considerations
- Failure handling

---

### Quick Recall

A2A

=

Coordination

+

Distribution

+

Aggregation

---

# RAG

### Definition

Retrieval-Augmented Generation combines retrieval systems with language models.

---

### Components

Retriever

↓

Knowledge Source

↓

Model

↓

Generation Layer

---

### Workflow

Request

↓

Retrieve Context

↓

Model Processing

↓

Response

---

### Benefits

- Better contextual accuracy
- Reduced hallucination risk
- Dynamic information retrieval
- Better grounding

---

### Quick Recall

RAG

=

Retrieve

+

Generate

---

# Platform Engineering

### Goal

Improve developer productivity and reduce operational friction.

---

### Core Areas

IDP

↓

Developer Experience

↓

Self Service

↓

Automation

↓

Engineering Productivity

---

### Key Interview Points

- Internal Developer Platform
- Developer Experience
- Self-service capabilities
- Operational efficiency
- Standardization

---

### Quick Recall

Platform Engineering

=

Developer Enablement

---

# Internal Developer Platform (IDP)

### Goal

Provide self-service engineering capabilities.

Examples:

- Infrastructure provisioning
- Deployment workflows
- Documentation systems
- Observability capabilities

---

### Quick Recall

IDP

=

Self Service

+

Developer Productivity

---

# DevEx

### Goal

Improve engineering experience.

Focus Areas:

- Documentation
- Automation
- Onboarding
- Developer workflows

---

### Quick Recall

DevEx

=

Reduce Engineering Friction

---

# Reliability Keywords

Retry

Timeout

Fallback

Validation

Observability

Scalability

Governance

Security

---

# Architecture Discussion Framework

Problem

↓

Requirements

↓

High Level Design

↓

Components

↓

Workflow

↓

Reliability

↓

Tradeoffs

↓

Scalability

---

# 30 Second Revision

AI Agent

→ Execute Work

MCP

→ Connectivity

A2A

→ Coordination

RAG

→ Knowledge Retrieval

IDP

→ Self Service Platform

DevEx

→ Developer Productivity

Platform Engineering

→ Developer Enablement