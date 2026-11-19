# Awesome-AI-Evaluation-Cognitive-Testing

## Top AI Evaluation & Cognitive Testing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on LLM & Agent Evaluation Harnesses, Cognitive & Reasoning Benchmarks, RAG Metrics, LLM-as-a-Judge & Red-Teaming Suites*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Evaluation & Cognitive Testing**. These tools evaluate multi-step AI agents and language models across reasoning, memory, calibration, hallucination resistance, RAG faithfulness, and safety—running unit-test-style assertions in CI/CD and continuous online monitoring in production.



**Examples** include LangSmith, Braintrust, DeepEval, Ragas, Arize Phoenix, Galileo, Humanloop, TruLens, Patronus AI, Fiddler AI, and zadescoxp/calibrain-harness (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for cognitive and agentic evaluation harnesses (`calibrain-harness`, `Inspect AI`, `SWE-bench`), unit-test LLM eval frameworks (`DeepEval`, `Promptfoo`, `Ragas`), OpenTelemetry evaluation suites (`Arize Phoenix`, `Opik`, `TruLens`), and automated red-teaming/safety scanners — ideal for AI researchers, ML engineers, and evaluation teams building rigorous, reproducible test suites.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[LangSmith (LangChain)](https://langchain.com)**  

  All-in-one cloud evaluation, dataset management, and observability platform enabling teams to run offline regression benchmarks and online LLM-as-a-judge checks on agent trajectories.



- **[Braintrust](https://braintrust.dev)**  

  Enterprise AI evaluation, prompt playground, and logging platform designed to score model/agent changes, compare experiments side by side, and gate CI/CD deployments.



- **[Galileo](https://rungalileo.io)**  

  Enterprise AI evaluation and observability suite featuring proprietary hallucination guardrails, agentic trajectory metrics, RAG attribution scoring, and automated error clustering.



- **[Patronus AI](https://patronus.ai)**  

  Automated AI evaluation and safety platform offering adversarial test generation, hallucination detection models (Lynx), and enterprise compliance benchmarking.



- **[Humanloop](https://humanloop.com)**  

  Enterprise LLM evaluation and prompt management workspace combining human-in-the-loop annotation workflows, custom evaluators, and dataset versioning.



- **[Arize AX / Arize Phoenix Cloud](https://arize.com)**  

  Enterprise AI observability and evaluation platform delivering span-level OpenTelemetry tracing, drift detection, and automated LLM evaluation pipelines.



- **[Fiddler AI](https://fiddler.ai)**  

  Enterprise AI observability and governance platform providing hallucination metrics, safety/toxicity scoring, data drift monitoring, and compliance guardrails.



- **[Confident AI (DeepEval Cloud)](https://confident-ai.com)**  

  Managed cloud evaluation platform built around DeepEval offering collaborative dataset curation, hosted red-teaming, and automated regression reporting.



- **[HoneyHive](https://honeyhive.ai)**  

  AI observability and evaluation platform built for compounding agent reliability through production trace curation, human feedback loops, and CI/CD evals.



- **[Vellum](https://vellum.ai)**  

  Cloud AI product development platform featuring quantitative multi-model evaluation matrices, prompt sandboxes, and versioned workflow deployments.





## Open-Source GitHub Projects



- **[zadescoxp/calibrain-harness](https://github.com)**  

  Open-source cognitive calibration and evaluation harness engineered to test AI model confidence calibration, reasoning consistency, epistemic uncertainty, and agentic decision reliability.



- **[DeepEval (`confident-ai/deepeval`)](https://github.com)**  

  Leading open-source (`Apache-2.0`) Pytest-style LLM evaluation framework offering 40+ research-backed metrics for agent tool correctness, task completion, faithfulness, hallucination, and red-teaming.



- **[Ragas (`explodinggradients/ragas`)](https://github.com)**  

  Widely adopted open-source (`Apache-2.0`) evaluation and synthetic test-data generation toolkit specialized in measuring faithfulness, context precision, context recall, and answer relevancy.



- **[Inspect AI (`UKGovernmentBEIS/inspect_ai`)](https://github.com)**  

  Open-source (`MIT`) evaluation framework developed by the UK AI Security Institute (AISI) for testing complex cognitive reasoning, sandboxed agent tool use, and safety benchmarks.



- **[Promptfoo (`promptfoo/promptfoo`)](https://github.com)**  

  Fast open-source (`MIT`) CLI and library for declarative LLM evaluation, side-by-side model comparisons, CI/CD regression gating, and automated adversarial red-teaming.



- **[Arize Phoenix (`Arize-ai/phoenix`)](https://github.com)**  

  Open-source (`ELv2`) OpenTelemetry-native AI observability and evaluation suite featuring pre-built hallucination/relevance evaluators, trace waterfalls, and experiment tracking.



- **[TruLens (`truera/trulens`)](https://github.com)**  

  Open-source (`MIT`) library for systematically evaluating and tracking LLM and RAG applications using programmable Feedback Functions (Groundedness, Context Relevance, Answer Relevance).



- **[Opik (`comet-ml/opik`)](https://github.com)**  

  Open-source (`Apache-2.0`) end-to-end LLM evaluation and tracing platform from Comet built for logging agent trajectories, managing evaluation datasets, and running LLM-as-a-judge metrics.



- **[LM Evaluation Harness (`EleutherAI/lm-evaluation-harness`)](https://github.com)**  

  Industry-standard open-source (`MIT`) framework from EleutherAI powering the Open LLM Leaderboard with 60+ academic cognitive, reasoning, math, and knowledge benchmarks (`MMLU`, `GSM8K`, `ARC`, `HellaSwag`).



- **[OpenAI Evals (`openai/evals`)](https://github.com)**  

  Official open-source (`MIT`) evaluation framework and benchmark registry from OpenAI for authoring custom model-graded and deterministic capability tests.



- **[EvalPlus (`evalplus/evalplus`)](https://github.com)**  

  Open-source (`Apache-2.0`) rigorous code-synthesis evaluation framework extending HumanEval and MBPP with 80x more edge-case test inputs to expose brittle code generation.



- **[LightEval (`huggingface/lighteval`)](https://github.com)**  

  All-in-one open-source (`MIT`) evaluation suite from Hugging Face supporting distributed vLLM/Transformers/Nanotron backends across hundreds of cognitive and domain benchmarks.



- **[Giskard (`Giskard-AI/giskard-oss`)](https://github.com)**  

  Open-source (`Apache-2.0`) automated QA and testing framework for AI agents and RAG pipelines that automatically scans for hallucinations, bias, prompt injection, and robustness flaws.



- **[Garak (`NVIDIA/garak`)](https://github.com)**  

  Open-source (`Apache-2.0`) LLM vulnerability scanner and red-teaming probe suite from NVIDIA testing models for jailbreaks, prompt injection, data leakage, and cognitive edge cases.



- **[Agenta (`Agenta-AI/agenta`)](https://github.com)**  

  Open-source (`MIT`) LLMOps and evaluation platform providing collaborative test-set management, human A/B blind annotation UIs, and automated scoring workflows.



- **[Langfuse (`langfuse/langfuse`)](https://github.com)**  

  Self-hostable open-source LLM engineering platform offering dataset experiment runs, LLM-as-a-judge evaluators, user feedback scoring, and trace-level evaluation analytics.



- **[SWE-bench (`SWE-bench/SWE-bench`)](https://github.com)**  

  Foundational open-source (`MIT`) software-engineering benchmark evaluating autonomous coding agents on their ability to resolve real-world GitHub issues inside Dockerized repositories.



### Additional Strong Open-Source Options



- **[HELM (`stanford-crfm/helm`)](https://github.com)** and **[BIG-bench (`google/BIG-bench`)](https://github.com)** for holistic multi-metric capability, calibration, fairness, and beyond-the-imitation-game cognitive benchmarks.

- **[TAU-bench (`sierra-research/tau-bench`)](https://github.com)** and **[GAIA / AgentBench (`THUDM/AgentBench`)](https://github.com)** for evaluating multi-turn tool-use reliability, database state consistency, and real-world agentic reasoning.

- **[PyRIT (`Azure/PyRIT`)](https://github.com)** for Microsoft's open-source Python Risk Identification Tool automating multi-turn adversarial red-teaming against generative AI systems.

- **[AutoEvals (`braintrustdata/autoevals`)](https://github.com)** and **[Prometheus-Eval (`prometheus-eval/prometheus-eval`)](https://github.com)** for open-source scoring primitives and open-weight judge models that replace proprietary GPT-4 judges.

- **[MLE-bench (`openai/mle-bench`)](https://github.com)** and **[OSWorld (`xlang-ai/OSWorld`)](https://github.com)** for evaluating autonomous ML engineering and desktop computer-use cognitive skills.
