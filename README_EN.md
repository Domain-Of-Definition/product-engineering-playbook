# Product Engineering Playbook

[中文版](./README.md)

This repository is a personal knowledge base for continuously documenting practical experience in product design, feature design, system design, and software development.

It records the design thinking, technical solutions, decision-making processes, engineering practices, and lessons learned from real product development work, covering the full lifecycle from understanding requirements and shaping product solutions to system architecture and final software implementation.

Rather than simply documenting **how to use a technology**, this repository focuses more on:

* Why a problem occurred
* How I analyzed the problem
* What possible solutions were considered
* Why the final solution was chosen
* What trade-offs existed between different approaches
* What happened after implementation
* What lessons can be generalized into reusable methods

The goal is to gradually transform fragmented project experience into my own reusable **Product Engineering Playbook**.

---

## Contents

### [Product Design](./product-design/)

Focuses on **what should be built, why it should be built, and what problems the product should solve**.

Topics may include:

* Requirement analysis
* User and scenario analysis
* Product goal decomposition
* Product workflow design
* MVP scope definition
* Feature prioritization
* Product feedback loops
* Product decision-making
* Product trade-offs

Core question:

> What product should we build, and why?

---

### [Feature Design](./feature-design/)

Focuses on how an individual feature **should work once the overall product direction has been defined**.

Topics may include:

* User flows
* Feature state design
* Business rules
* Happy paths
* Exception flows
* Edge cases
* Permission rules
* Loading / Empty / Error states
* Frontend-backend interactions
* Feature-level design trade-offs

Core question:

> How should this feature actually work?

---

### [System Design](./system-design/)

Focuses on how to design a technical architecture that **effectively supports product and feature requirements**.

Topics may include:

* System architecture
* Service and module boundaries
* API design
* Database design
* Data modeling
* Data flow
* Authentication and authorization architecture
* Caching
* Message queues
* File storage
* Third-party service integrations
* AI / LLM system architecture
* Scalability
* Performance
* Reliability
* Security
* Architectural trade-offs

Core question:

> How should the technical system be designed to properly support the product?

---

### [Software Development](./software-development/)

Focuses on how to **implement, test, debug, deploy, and maintain** the designed solution in practice.

Topics may include:

* Backend development
* Frontend development
* Database development
* Coding practices
* Framework usage
* Debugging methods
* Git workflows
* Automated testing
* CI/CD
* Docker and deployment
* Logging and exception handling
* Database migrations
* Performance optimization
* AI / LLM API integration
* Engineering productivity

Core question:

> How can the solution be implemented with high engineering quality?

---

## How I Document Experience

Articles in this repository will generally follow the structure below.

### 1. Context

What project, business scenario, or development situation led to this work?

### 2. Problem

What specific problem needed to be solved?

### 3. Constraints

What business, product, technical, time, or resource constraints affected the solution?

### 4. Analysis

How did I understand and analyze the problem?

### 5. Solution

What product design, technical approach, or implementation was ultimately chosen?

### 6. Alternatives Considered

What other approaches were evaluated?

### 7. Trade-offs

Why was the final approach selected?

What benefits did it provide, and what costs or additional complexity did it introduce?

### 8. Result

What happened after the solution was implemented?

### 9. Lessons Learned

What did I learn from this experience?

### 10. Reusable Principles

What lessons can be generalized into reusable methods or principles for similar problems in the future?

---

## From Project Experience to Methodology

This repository is intended to support a continuous learning process like this:

```text
Real Project
    ↓
Specific Problem
    ↓
Analysis & Solution
    ↓
Design Decisions
    ↓
Implementation Result
    ↓
Lessons Learned
    ↓
Reusable Principles
    ↓
Personal Methodology
```

As more project experience accumulates, the content in this repository will continue to evolve and be refined.

The ultimate goal is not simply to build a collection of development notes, but to develop a personal **Product Engineering Playbook** that demonstrates a complete product and engineering thinking process.
