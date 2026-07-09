# DevOps & Cloud Assessment

## Purpose

Evaluate DevOps practices, cloud concepts, delivery automation, infrastructure management, and production operations knowledge.

This assessment validates the ability to build, deploy, secure, and operate modern software systems.

---

## Assessment Scope

Topics covered:

- CI/CD pipelines
- Build and release engineering
- Containerization
- Kubernetes fundamentals
- Cloud architecture
- Infrastructure as Code
- Monitoring
- Security automation
- Deployment strategies
- Production operations

---

## Assessment Format

Three levels:

### Level 1 — Concept Understanding

Validates DevOps and cloud fundamentals.

### Level 2 — Engineering Scenarios

Validates practical operational decisions.

### Level 3 — Senior Engineer Decisions

Validates production engineering and platform thinking.

---

# Level 1 — Concept Understanding

## Q1. What is the primary goal of CI/CD?

A. Increase manual deployment steps

B. Automate software build, testing, and delivery processes

C. Replace source control

D. Remove testing requirements

---

## Q2. What problem does containerization solve?

A. Eliminates all application bugs

B. Provides consistent application packaging and runtime environments

C. Replaces databases

D. Removes infrastructure requirements

---

## Q3. What is Infrastructure as Code (IaC)?

A. Writing application business logic

B. Managing infrastructure using version-controlled configuration

C. Manual server configuration only

D. Removing cloud resources

---

# Level 2 — Engineering Scenarios

## Q4. A deployment fails after a new release.

What should be investigated first?

Expected thinking:

- Deployment logs
- Application health checks
- Configuration changes
- Dependency changes
- Rollback strategy

---

## Q5. A team manually deploys applications to production and frequently introduces errors.

What improvement is recommended?

A. Add more manual steps

B. Implement automated CI/CD pipelines

C. Remove testing

D. Avoid version control

---

## Q6. A Kubernetes application repeatedly restarts.

Investigation areas:

- Pod logs
- Resource limits
- Application health probes
- Configuration issues
- Dependency availability

Expected thinking:

Identify the failure reason before changing resource limits.

---

# Level 3 — Senior Engineer Decisions

## Q7. Design a production deployment pipeline.

Consider:

- Source control integration
- Build automation
- Automated testing
- Security scanning
- Artifact management
- Deployment strategy
- Monitoring

---

## Q8. A company wants to migrate an application to cloud infrastructure.

What should be evaluated?

Expected thinking:

- Application architecture
- Cost model
- Security requirements
- Availability needs
- Operational ownership
- Migration strategy

---

## Q9. Production incident:

```
Deployment: Successful
Application: Running
Users: Reporting failures
Logs: Increased errors
```

Investigation areas:

- Application changes
- Configuration differences
- Dependency failures
- Feature flags
- Environment differences

---

# Answer Key

To be completed after assessment execution.

---

# Explanation

Detailed explanations will be added after answering questions.

---

# Score Tracking

| Topic | Score | Status |
|---|---|---|
| CI/CD | | |
| Containers | | |
| Kubernetes | | |
| Cloud | | |
| Infrastructure as Code | | |
| Operations | | |

---

# Weak Areas

Identified after assessment completion.

---

# Recommended Resources

Focused resources will be added based on assessment results.

---

# Practical Application

Apply DevOps and cloud concepts through real engineering projects.

---

# Next Assessment

Next: `10-assessment/07-security.md`