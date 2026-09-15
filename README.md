# Awesome-Prompt-Management-Platform

## Top Prompt Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Prompt Registries, Versioning, Collaboration, Experiments, Observability & LLM Application Lifecycle*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Prompt Management**. These tools help teams store, version, label, collaborate on, experiment with, and deploy prompts for LLM applications, often combined with tracing, evaluations, and production observability.



**Examples** include Langfuse, Humanloop, PromptLayer, Helicone, Portkey, Braintrust, Lunary, LangSmith, Weights & Biases Prompts, PromptHub, PromptPerfect, Promptitude, Agenta, Keywords AI, and Promptfoo (the category leaders).



**Open-source emphasis**: Prompt management has strong open-source options. **Langfuse** is the leading self-hostable platform with first-class prompt versioning. **Agenta**, **Promptfoo**, and related tools further expand the open ecosystem. This section prioritizes practical open alternatives.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

**Estimated Sector Market Size:** ~$1.5B–$2.5B (2026, within the broader LLMOps & AI Observability market projected at $5B+).  
**Market Dynamics:** Highly fragmented sector transitioning into a moderately concentrated landscape driven by rapid consolidation (acquisitions by OpenAI, Anthropic, Palo Alto Networks, CoreWeave, Elastic, and ClickHouse), with winner-take-most dynamics emerging around full-stack LLMOps and observability suites rather than standalone prompt registries.

| Product | Description | Company Scale (Valuation / Revenue) | Starting Price | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[LangSmith](https://www.langchain.com/langsmith)** | LangChain’s platform for tracing, evaluation, prompt management, and experimentation tightly integrated with LangChain/LangGraph. | ~$1.25B Valuation (LangChain) / ~$16M ARR | $39/seat/mo (Plus plan) | 5,000 traces/mo, 14 days retention, 1 seat |
| **[Weights & Biases Prompts](https://wandb.ai/)** | Prompt and LLM experiment tracking capabilities within the broader Weights & Biases MLOps platform. | ~$1.25B Valuation (Acquired by CoreWeave) / ~$60M Revenue | $60/mo (Pro plan) | 5 seats, 5 GB storage, 1 GB/mo Weave ingestion |
| **[Braintrust](https://www.braintrust.dev/)** | Evaluation-first platform for prompt testing, versioning, datasets, and systematic improvement of LLM applications. | ~$800M Valuation / $121M Funding | $249/mo (Pro plan) | 1 GB processed data/mo, 10,000 scores/mo, $10 model credits/mo |
| **[Promptfoo](https://www.promptfoo.dev/)** | Open-source LLM evaluation and red-teaming tool with cloud options; supports prompt testing, comparison, and CI/CD integration. | ~$86M Valuation (Acquired by OpenAI) | $50/mo (Team plan) | 10,000 red team probes/mo & free unlimited local CLI usage |
| **[Portkey](https://portkey.ai/)** | AI gateway and observability platform that includes prompt management, routing, guardrails, and production controls. | ~$18M Funding (Acquisition announced by Palo Alto Networks) / ~$5M ARR | $49/mo (Pro plan) | 10,000 recorded logs/mo, 3 days log retention |
| **[Humanloop](https://humanloop.com/)** | Prompt engineering and evaluation platform focused on collaboration and systematic improvement of LLM applications. | ~$7.9M Funding (Acqui-hired by Anthropic) / ~$3.8M ARR | Contact for Custom Enterprise pricing | Free Trial: 10,000 logs/mo, 50 eval runs, 2 seats |
| **[Langfuse](https://www.langfuse.com/)** | Open-source LLM observability and prompt management platform with versioning, labels, experiments, tracing, and evaluations (cloud and self-hosted). | ~$4.5M Funding (Acquired by ClickHouse) / ~$1.1M ARR | $29/mo (Core plan) | 50,000 units/mo, 30 days retention, 2 users |
| **[PromptLayer](https://www.promptlayer.com/)** | Prompt management and observability platform with versioning, release labels, A/B testing, and collaboration features for technical and non-technical users. | ~$4.8M Funding / ~$1.9M Est. ARR | $49/mo (Pro plan) | 2,500 requests/mo, unlimited logging, core versioning |
| **[Keywords AI](https://www.keywordsai.co/)** | LLM engineering platform with prompt management, observability, and related production features. | ~$1.1M Est. ARR / $500K Funding (YC) | Pay-as-you-go / Custom | Free starter tier: 100,000 logs, 1,000 scores, 5 datasets |
| **[Helicone](https://www.helicone.ai/)** | LLM observability platform with logging, cost tracking, and prompt-related production visibility (proxy-based). | ~$1M ARR (Acquired by Mintlify) / $500K Funding | $79/mo (Pro plan) | 10,000 requests/mo, 7 days retention, 1 GB storage, 1 seat |
| **[Promptitude](https://www.promptitude.io/)** | Prompt management and workflow tools for teams building LLM applications. | ~$1.2M Est. ARR (Bootstrap / Seed) | $39/mo | 100 generations/mo, 200 tool calls/mo, 5 prompts, 2 seats, 50k tokens |
| **[Agenta](https://agenta.ai/)** | Open-source LLMOps platform focused on prompt engineering, versioning, evaluation, and collaboration (also offered as a hosted service). | ~$1.1M Est. ARR / Seed stage | $29/mo (Pro plan) | 5,000 agent runs/mo, 2 seats |
| **[PromptHub](https://www.prompthub.us/)** | Platform focused on sharing, discovering, and managing prompts. | ~$170K Est. ARR (Bootstrap / Seed) | $12/user/mo (Pro plan) | Free forever plan with unlimited public prompts & 2,000 requests/mo |
| **[PromptPerfect](https://promptperfect.jina.ai/)** | Tool aimed at optimizing and refining prompt quality. | Product of Jina AI ($36M Funding, Acquired by Elastic) | $9.99/mo (Lite plan) | Free signup credit allowance / 1 prompt optimization per day |
| **[Lunary](https://www.lunary.ai/)** | Open-source-friendly LLM observability and prompt management tool for tracking and improving prompts in production. | Bootstrap / Early stage | $20/user/mo (Team plan) | 1,000 events/day (or 10k/mo), 30 days retention, 1 seat |



## Open-Source GitHub Projects

- **[LiteLLM](https://github.com/BerriAI/litellm)** [![GitHub stars](https://img.shields.io/github/stars/BerriAI/litellm?style=social&color=white)](https://github.com/BerriAI/litellm/stargazers)  
  High-performance AI Gateway with prompt management, logging, cost tracking, guardrails, and unified access to 100+ LLM APIs.

- **[Langfuse](https://github.com/langfuse/langfuse)** [![GitHub stars](https://img.shields.io/github/stars/langfuse/langfuse?style=social&color=white)](https://github.com/langfuse/langfuse/stargazers)  
  Leading open-source LLM engineering platform (MIT) featuring complete prompt management: versioning, release labels, evaluations, tracing, and prompt experiments.

- **[Promptfoo](https://github.com/promptfoo/promptfoo)** [![GitHub stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social&color=white)](https://github.com/promptfoo/promptfoo/stargazers)  
  Open-source CLI and library for automated testing, red-teaming, and benchmarking prompts, agents, and RAG architectures with CI/CD integration.

- **[DeepEval](https://github.com/confident-ai/deepeval)** [![GitHub stars](https://img.shields.io/github/stars/confident-ai/deepeval?style=social&color=white)](https://github.com/confident-ai/deepeval/stargazers)  
  Open-source LLM evaluation framework for unit testing prompts, RAG pipelines, and agent behaviors with synthetic data generation.

- **[Ragas](https://github.com/explodinggradients/ragas)** [![GitHub stars](https://img.shields.io/github/stars/explodinggradients/ragas?style=social&color=white)](https://github.com/explodinggradients/ragas/stargazers)  
  Framework for evaluating Retrieval-Augmented Generation (RAG) and prompt quality using automated metric scoring.

- **[Portkey Gateway](https://github.com/Portkey-AI/gateway)** [![GitHub stars](https://img.shields.io/github/stars/Portkey-AI/gateway?style=social&color=white)](https://github.com/Portkey-AI/gateway/stargazers)  
  Fast open-source AI gateway supporting prompt routing, fallbacks, load balancing, and production guardrails.

- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** [![GitHub stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=social&color=white)](https://github.com/Arize-ai/phoenix/stargazers)  
  Open-source AI observability and evaluation platform for tracking prompt performance, traces, and dataset metrics.

- **[OpenLLMetry](https://github.com/traceloop/openllmetry)** [![GitHub stars](https://img.shields.io/github/stars/traceloop/openllmetry?style=social&color=white)](https://github.com/traceloop/openllmetry/stargazers)  
  Open-source OpenTelemetry-based observability for GenAI apps, enabling prompt and model interaction tracing across services.

- **[Helicone](https://github.com/Helicone/helicone)** [![GitHub stars](https://img.shields.io/github/stars/Helicone/helicone?style=social&color=white)](https://github.com/Helicone/helicone/stargazers)  
  Open-source LLM observability proxy for logging requests, monitoring prompt performance, costs, and request latency.

- **[Agenta](https://github.com/Agenta-AI/agenta)** [![GitHub stars](https://img.shields.io/github/stars/Agenta-AI/agenta?style=social&color=white)](https://github.com/Agenta-AI/agenta/stargazers)  
  Open-source LLMOps workspace for prompt engineering, collaborative prompt testing, versioning, and evaluation.

- **[TruLens](https://github.com/truera/trulens)** [![GitHub stars](https://img.shields.io/github/stars/truera/trulens?style=social&color=white)](https://github.com/truera/trulens/stargazers)  
  Instrumentation and evaluation library for tracking and scoring prompt performance in LLM applications.

- **[OpenLIT](https://github.com/OpenLIT/openlit)** [![GitHub stars](https://img.shields.io/github/stars/OpenLIT/openlit?style=social&color=white)](https://github.com/OpenLIT/openlit/stargazers)  
  Open-source OpenTelemetry-native AI application observability and prompt performance monitoring suite.

### Additional Strong Open-Source Options

- Starting with **Langfuse** for a complete, self-hostable prompt management + observability solution.

- Using **Agenta** when prompt-centric collaboration and evaluation are the primary needs.

- Applying **Promptfoo** for rigorous testing, red-teaming, and CI gates on prompts.

- Combining open proxies (Helicone-style or LiteLLM) with a prompt registry for lighter-weight setups.

- Treating prompts as code in Git for simple versioning when a full platform is not yet required.

- Accepting that polished non-technical editors, advanced traffic-splitting, and enterprise collaboration features still favor commercial platforms (PromptLayer, LangSmith, Braintrust, etc.).



**Frameworks for building custom systems**: Deploy Langfuse (self-hosted or cloud) → store and version prompts with labels → link prompts to traces and evaluations → run experiments against datasets → promote versions to production via labels. Optionally add Promptfoo for automated testing and red-teaming. This provides an open, production-grade prompt lifecycle. Commercial platforms remain attractive when teams want managed services, specialized UI for non-engineers, or deep integration with specific frameworks.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Prompt management tools handle application logic and often production traffic data. Self-hosted solutions require proper security, access control, and operational practices. Always evaluate tools against your data sensitivity and compliance needs. This list is not security or operational advice.



---

**Made for AI engineers, LLM application teams, and prompt engineers who want reliable version control and observability.**

Let's keep prompt management systematic, measurable, and as open as practical.
