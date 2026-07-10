# Prompt Patterns

Prompt patterns are reusable approaches for designing effective instructions for Large Language Models.

They help engineers create consistent, maintainable, and reliable interactions with LLM systems.

---

# Purpose

Understand:

- Common prompt design patterns
- When to apply different prompting approaches
- How patterns improve LLM application quality
- Engineering considerations for prompt reuse

---

# Core Concepts

## Zero-Shot Prompting

Provides instructions without examples.

Useful when:

- The task is simple
- The model already understands the required behavior
- Fast experimentation is needed

---

## Few-Shot Prompting

Provides examples to guide the model response.

Benefits:

- Improves consistency
- Demonstrates expected output style
- Helps handle specialized tasks

---

## Role-Based Prompting

Defines the role or perspective the model should follow.

Examples:

- Software engineer assistant
- Technical reviewer
- Data analyst

---

## Structured Prompting

Organizes prompts using clear sections.

Common structure:

- Goal
- Context
- Instructions
- Constraints
- Expected output

---

## Output Control Patterns

Defines how responses should be generated.

Examples:

- JSON format
- Tables
- Bullet points
- Specific templates

---

# Prompt Pattern Flow

```text
Application Requirement

↓

Select Prompt Pattern

↓

Design Prompt

↓

Test Response

↓

Improve Prompt
```

---

# AI Engineering Perspective

Prompt patterns should be treated as engineering assets.

Production systems require:

- Version control
- Testing
- Evaluation
- Reusability
- Continuous improvement

---

# Goal

Understand reusable prompt patterns and apply them effectively when building reliable LLM-powered applications.