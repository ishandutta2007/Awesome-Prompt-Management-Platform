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

- **[Langfuse](https://www.langfuse.com/)**  

  Open-source LLM observability and prompt management platform with versioning, labels, experiments, tracing, and evaluations (cloud and self-hosted).



- **[Humanloop](https://humanloop.com/)**  

  Prompt engineering and evaluation platform focused on collaboration and systematic improvement of LLM applications.



- **[PromptLayer](https://www.promptlayer.com/)**  

  Prompt management and observability platform with versioning, release labels, A/B testing, and collaboration features for technical and non-technical users.



- **[Helicone](https://www.helicone.ai/)**  

  LLM observability platform with logging, cost tracking, and prompt-related production visibility (proxy-based).



- **[Portkey](https://portkey.ai/)**  

  AI gateway and observability platform that includes prompt management, routing, guardrails, and production controls.



- **[Braintrust](https://www.braintrust.dev/)**  

  Evaluation-first platform for prompt testing, versioning, datasets, and systematic improvement of LLM applications.



- **[Lunary](https://www.lunary.ai/)**  

  Open-source-friendly LLM observability and prompt management tool for tracking and improving prompts in production.



- **[LangSmith](https://www.langchain.com/langsmith)**  

  LangChain’s platform for tracing, evaluation, prompt management, and experimentation tightly integrated with LangChain/LangGraph.



- **[Weights & Biases Prompts](https://wandb.ai/)**  

  Prompt and LLM experiment tracking capabilities within the broader Weights & Biases MLOps platform.



- **[PromptHub](https://www.prompthub.us/)**  

  Platform focused on sharing, discovering, and managing prompts.



- **[PromptPerfect](https://promptperfect.jina.ai/)**  

  Tool aimed at optimizing and refining prompt quality.



- **[Promptitude](https://www.promptitude.io/)** (or similar)  

  Prompt management and workflow tools for teams building LLM applications.



- **[Agenta](https://agenta.ai/)**  

  Open-source LLMOps platform focused on prompt engineering, versioning, evaluation, and collaboration (also offered as a hosted service).



- **[Keywords AI](https://www.keywordsai.co/)**  

  LLM engineering platform with prompt management, observability, and related production features.



- **[Promptfoo](https://www.promptfoo.dev/)**  

  Open-source LLM evaluation and red-teaming tool with cloud options; supports prompt testing, comparison, and CI/CD integration.



## Open-Source GitHub Projects

- **[Langfuse](https://github.com/langfuse/langfuse)**  

  Leading open-source LLM engineering platform (MIT) with first-class prompt management: versioning, labels, protected releases, experiments, tracing, and evaluations. Fully self-hostable.



- **[Agenta](https://github.com/Agenta-AI/agenta)**  

  Open-source platform for prompt engineering, versioning, evaluation, and collaborative testing of LLM applications.



- **[Promptfoo](https://github.com/promptfoo/promptfoo)**  

  Open-source CLI and library for evaluating and red-teaming prompts, agents, and RAGs with declarative configs and CI/CD support.



- **[Helicone](https://github.com/Helicone/helicone)**  

  Open-source LLM observability proxy that provides logging, analytics, and related production visibility useful alongside prompt workflows.



- **[Portkey / open gateway components](https://github.com/)**  

  Open or partially open AI gateway projects that support prompt routing, management, and observability features.



- **[Prompt registry and versioning open experiments](https://github.com/)**  

  Community tools for storing prompts as versioned artifacts with simple APIs or Git-based workflows.



- **[Evaluation and dataset open frameworks](https://github.com/)**  

  Open evaluation libraries (including DeepEval, Ragas, and others) that pair well with prompt versioning for systematic testing.



- **[LiteLLM and proxy open tools](https://github.com/BerriAI/litellm)**  

  Open proxies that can sit in front of multiple LLM providers and support logging/versioning patterns.



- **[Self-hosted observability stacks for LLMs](https://github.com/)**  

  Combinations of open tracing, logging, and prompt storage that teams assemble for internal use.



- **[Arize Phoenix and related open observability](https://github.com/Arize-ai/phoenix)**  

  Open-source observability and evaluation tools that integrate with prompt management practices.



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
