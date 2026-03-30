# Algorithmic Research Group

ARG studies how software and industrial systems recursively improve themselves in real-world settings, with a focus on measuring progress, building tools, and understanding the behavior and limits of self-improving systems.

Website: [algorithmicresearchgroup.com](https://algorithmicresearchgroup.com/)

This GitHub organization is the open-source home for that work: agentic ML research, evaluation platforms, benchmark generation, and supporting tooling.

## Start Here

- Want benchmark and evaluation repos? Start with [deltaml-bench-public](https://github.com/AlgorithmicResearchGroup/deltaml-bench-public), [aria-public](https://github.com/AlgorithmicResearchGroup/aria-public), and [mlrb-evals-public](https://github.com/AlgorithmicResearchGroup/mlrb-evals-public).
- Want ready-to-run agents and agent libraries? Start with [ML-Research-Agent](https://github.com/AlgorithmicResearchGroup/ML-Research-Agent), [ScoutML-Research-Agent](https://github.com/AlgorithmicResearchGroup/ScoutML-Research-Agent), and [Agent-States](https://github.com/AlgorithmicResearchGroup/Agent-States).
- Want search and optimization experiments? Start with [nas-public](https://github.com/AlgorithmicResearchGroup/nas-public), [aide-parallel-public](https://github.com/AlgorithmicResearchGroup/aide-parallel-public), and [otto-classification-challenge-agent](https://github.com/AlgorithmicResearchGroup/otto-classification-challenge-agent).

## Datasets On Hugging Face

Full catalog: [huggingface.co/AlgorithmicResearchGroup](https://huggingface.co/AlgorithmicResearchGroup)

| Dataset | What it is |
| --- | --- |
| [arxiv_research_code](https://huggingface.co/datasets/AlgorithmicResearchGroup/arxiv_research_code) | Large corpus of source code referenced in arXiv papers, released for research-code and code-model work. |
| [arxiv_s2orc_parsed](https://huggingface.co/datasets/AlgorithmicResearchGroup/arxiv_s2orc_parsed) | Parsed arXiv subset of S2ORC with full paper text and extracted GitHub links. |
| [arxiv_python_research_code](https://huggingface.co/datasets/AlgorithmicResearchGroup/arxiv_python_research_code) | Python-focused slice of research code linked from arXiv papers. |
| [s2orc-cs-enriched](https://huggingface.co/datasets/AlgorithmicResearchGroup/s2orc-cs-enriched) | A 54GB Computer Science subset of S2ORC with additional LLM-generated enrichment fields |


## Benchmarks And Evaluation

| Repo | What it is |
| --- | --- |
| [aria-public](https://github.com/AlgorithmicResearchGroup/aria-public) | Generates AI research benchmark datasets from Papers with Code exports and evaluates them with Inspect AI. |
| [deltaml-bench-public](https://github.com/AlgorithmicResearchGroup/deltaml-bench-public) | Public monorepo for DeltaMLBench task families, Vivaria integration, multiple agent variants, and grading utilities. |
| [mlrb-evals-public](https://github.com/AlgorithmicResearchGroup/mlrb-evals-public) | Evaluation CLI for ML Research Benchmark presets, native metrics, `lm-eval-harness`, and optional Lean workflows. |

## Agents And Research Tooling

| Repo | What it is |
| --- | --- |
| [epsilon](https://github.com/AlgorithmicResearchGroup/epsilon) | Epsilon is infrastructure for structured multi-agent workloads |
| [aide-parallel-public](https://github.com/AlgorithmicResearchGroup/aide-parallel-public) | Runs AIDE experiments locally or on a Ray cluster, with a CPU-friendly attention quickstart and optional GPU KernelBench runs. |
| [ML-Research-Agent](https://github.com/AlgorithmicResearchGroup/mlrb-agent-public) | Baseline agent for ML Research Benchmark tasks, with tool integrations for coding, papers, GitHub access, and experiment workflows. |
| [ScoutML-Research-Agent](https://github.com/AlgorithmicResearchGroup/ScoutML-Research-Agent) | Research assistant that searches academic papers and generates implementation guides from the literature. |
| [Agent-States](https://github.com/AlgorithmicResearchGroup/agent-states-public) | Finite-state-machine library for AI agent state management, persistence, guarded transitions, and visualization. |


## Search And Experiment Repos

| Repo | What it is |
| --- | --- |
| [nas-public](https://github.com/AlgorithmicResearchGroup/nas-public) | Trains a Tiny Recursive Model to predict NAS-Bench-201 performance and uses that predictor for architecture search. |
| [otto-classification-challenge-agent](https://github.com/AlgorithmicResearchGroup/otto-classification-challenge-agent) | Small Kaggle Otto classification challenge repo with a reproducible training and evaluation entry point. |


