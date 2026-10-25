# Internet of Cognition

The Internet of Cognition (IoC) project builds the agentic cognitive layer that lets
autonomous agents effectively collaborate. Agent transports like A2A, MCP and SLIM
already deliver messages reliably. They do not establish shared intent, shared context
or shared reasoning, and without those, several capable agents assigned to one task
will exchange messages correctly and still produce a poor outcome, often worse than
what any of them would produce alone: contradictory findings committed to shared
state, the same intermediate result interpreted differently, a session closed without
a validated agreement. None of it raises an exception, so conventional monitoring
never sees it.

IoC addresses this with four components. The **Cognition Protocols** operate above the
transport under a stronger success condition than delivery — alignment, of intents,
roles and opinions. The **Cognition Fabric** recomposes a multi-agent interaction into
a single trajectory and knowledge graph, and persists the insights derived from it,
with **SCOPE** supplying that sensing and comprehension layer and detecting the
cognitive failures that would otherwise go unseen. The **Cognition Engines** act on
those insights to make collective behavior more capable and trustworthy. **MAS-Lab**
spans all of them, providing an environment in which any component is declared,
executed, observed and measured against a baseline, so that the claims made about it
are results rather than assertions.

This project is maintained by [Outshift by Cisco](https://outshift.cisco.com/internet-of-cognition).

## Documentation

Full documentation — motivation, architecture, component guides and tutorials — is
published at **[ioc-project.github.io](https://ioc-project.github.io/)**.

| Start here | |
|---|---|
| Why the project exists | [Motivation](https://ioc-project.github.io/overview/motivation/) |
| How the pieces fit together | [Architecture](https://ioc-project.github.io/overview/architecture/) |
| How to adopt it in an existing multi-agent system | [Getting Started](https://ioc-project.github.io/how-to/) |

## Repositories

* [cognition-protocols](https://github.com/ioc-project/cognition-protocols) — ACCORD
  (shared intent by coverage) and CONCORD (deciding under the conflict that remains)
* [scope](https://github.com/ioc-project/scope) — System for Cognitive Observability,
  Provenance and Explainability: instrumentation, trajectory recomposition, and the
  analysis that detects cognitive failures and explains them
* [mas-lab](https://github.com/ioc-project/mas-lab) — specification-driven multi-agent
  systems with OpenTelemetry observability, agent traces, benchmarking, MCP and A2A
* [ioc-project.github.io](https://ioc-project.github.io/) — the documentation site

## Related reading

* [Internet of Cognition](https://outshift.cisco.com/internet-of-cognition) — the
  vision, and the *Scaling Out Superintelligence* whitepaper
* [Silent Failures, Loud Consequences](https://outshift.cisco.com/blog/ai-ml/cognitive-challenges-in-multi-agent-systems)
  — the empirical study behind the problem statement
