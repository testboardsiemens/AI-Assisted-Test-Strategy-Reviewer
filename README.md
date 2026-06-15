# AI-Assisted Test Strategy Reviewer

An AI-assisted evaluation bot designed to assess software test strategy documents from a Test Architect and Quality Governance perspective.

The system evaluates software test strategies against six operationally critical dimensions:

* Entry / Exit Criteria
* Risk Management
* Schedule
* Test Environment
* Test Scope
* Test Levels

The primary goal of the project is not to generate test strategies, but to evaluate their completeness, practicality, and governance readiness.

## Motivation

In many enterprise software organizations, test strategy reviews are performed manually by senior QA professionals or Test Architects.

This process is often:

* Time consuming
* Reviewer dependent
* Difficult to scale
* Inconsistent across projects

This project explores how Large Language Models (LLMs) can be used to provide faster, more consistent, and more objective reviews of software test strategy documents.

## Key Features

* Automated document evaluation
* Criterion-based scoring
* Structured improvement recommendations
* Evidence-based assessment model
* Governance-oriented feedback
* Conversational AI interface

## Evaluation Dimensions

| Dimension             | Purpose                                                  |
| --------------------- | -------------------------------------------------------- |
| Entry / Exit Criteria | Assess release readiness and test completion conditions  |
| Risk Management       | Evaluate risk identification, mitigation, and monitoring |
| Schedule              | Review planning and milestone definitions                |
| Test Environment      | Assess test infrastructure readiness                     |
| Test Scope            | Evaluate coverage boundaries and focus areas             |
| Test Levels           | Review definition of test levels and responsibilities    |

## Evolution of the Evaluation Approach

The system was developed through four major iterations.

### Iteration 1 — Independent Criterion Evaluation

Each criterion was evaluated through a dedicated prompt.

Challenges:

* Long execution times
* High score variability
* Repeated context processing

### Iteration 2 — Unified Evaluation Prompt

All evaluation criteria were merged into a single evaluation workflow.

Benefits:

* Significant runtime reduction
* Improved coherence
* Lower operational cost

### Iteration 3 — Scoring Calibration

The scoring model was refined through:

* Criterion weighting
* Scope simplification
* Practical governance alignment

### Iteration 4 — Evidence-Based Evaluation

A three-level evidence model was introduced:

* Referenced
* Defined
* Operational

This reduced superficial scoring and improved evaluation realism.

## Repository Structure

```text
.
├── prompts/
├── examples/
├── docs/
├── evaluation-criteria/
└── outputs/
```

## Disclaimer

This repository is intended for research and educational purposes.

The prompts, criteria, and examples reflect one specific industrial approach to software test strategy evaluation and may require adaptation for different organizations.

