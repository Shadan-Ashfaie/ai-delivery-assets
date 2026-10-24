# Enterprise GenAI Solution Lifecycle

*A generic reference framework for LLM applications, RAG, and agent-enabled enterprise workflows.*

| Stage | Key activities | Example exit evidence |
|---|---|---|
| 1. Discover & prioritize | Clarify workflow, business baseline, users, expected outcomes, risk, and non-AI alternatives | Sponsor, measurable success criteria, initial risk classification |
| 2. Design & assess | Evaluate data readiness, permissions, architecture, integration, human oversight, and model/tool choices | Solution outline, architecture review, cost assumptions |
| 3. Prototype & evaluate | Build a thin slice; test representative scenarios, retrieval coverage, groundedness, tool behavior, and failure modes | Evaluation set, quality thresholds, error analysis |
| 4. Secure & validate | Assess access control, prompt injection, sensitive data, auditability, and approval gates | Security/privacy review, UAT evidence, human-review plan |
| 5. Deploy & operate | Confirm logging, tracing, latency, rollback, reliability, monitoring, ownership, and cost | Runbook, release criteria, operational dashboard |
| 6. Adopt & realize value | Enable users and measure sustained usage, task success, throughput, quality, and business impact | Adoption and process metrics, accountable benefits owner |
| 7. Improve or retire | Review quality, incidents, cost, technology changes, and ongoing value | Improvement backlog, migration or retirement criteria |

## Evaluation questions

- **Correctness:** Does the solution answer accurately or perform the intended action?
- **Grounding:** Can claims be traced to authorized and current sources?
- **Coverage:** Does retrieval find the information needed, including difficult cases?
- **Safety:** Are permissions, sensitive data, and human approvals respected?
- **Reliability:** Are tool errors, timeouts, fallbacks, and failure modes understood?
- **Economics:** Do measured benefits justify implementation and operating costs?
- **Experience:** Can users recognize limitations and recover from errors?

## Value measurement

- **Adoption:** Frequency and breadth of sustained usage.
- **Effectiveness:** Accuracy and usefulness of completed tasks.
- **Operational improvement:** Changes in end-to-end cycle time, throughput, quality, and effort.
- **Financial return:** Validated financial benefit relative to total implementation and operating costs.

Time saved is not automatically cash saved. Validate benefit assumptions with business and finance stakeholders.

## Technology selection

Consider deterministic automation, rules, search, predictive ML, RAG, and human review before selecting autonomous agents. Where tools can act on enterprise systems, apply least-privilege permissions, audit trails, and appropriate human approval.

*Illustrative reference material only. No employer-specific code, architecture, data, or controls are represented.*
