# Mastering AI Agents

Practical guide to building AI Agents beyond simple chatbots — covering agent design, prompt engineering, multi-platform orchestration, and real-world data analysis use cases.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Google ADK](https://img.shields.io/badge/Google_ADK-latest-orange?style=flat-square&logo=google)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## What you'll learn

- Distinguish agents from traditional chatbots and understand agentic architectures
- Design effective conversational flows with guardrails and fallbacks
- Build prompts for complex, multi-step reasoning tasks
- Integrate agents with external APIs and data sources
- Apply agents to real business problems (manufacturing, logistics, quality control)
- Govern and secure AI agent deployments

## Prerequisites

| Topic | Level |
|---|---|
| Prompt engineering basics | Basic |
| REST APIs | Basic |
| Python or no-code tools | Any |

---

## Contents

### Demo — Data Analysis with AI Agents
> `Demo_Data_Analysis.ipynb`

End-to-end demo of an AI agent performing cross-dataset analysis in a textile manufacturing scenario. The agent queries, correlates and interprets data across five operational domains.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ahirtonlopes/Mastering-AI-Agents/blob/main/Demo_Data_Analysis.ipynb)

### Datasets

Realistic synthetic datasets for the manufacturing demo:

| File | Domain |
|---|---|
| `producao_textil.csv` | Production metrics |
| `manutencao_maquinas.csv` | Machine maintenance |
| `qualidade_produto.csv` | Quality control |
| `logistica_estoque.csv` | Inventory & logistics |
| `planejamento_producao.csv` | Production planning |

### Prompt Guide
> `Advanced Prompting Analytics.docx`

A curated set of prompts for multi-agent data analysis, compatible with ChatGPT, Copilot Studio, Perplexity AI, and Google ADK.

---

## Getting Started

```bash
git clone https://github.com/ahirtonlopes/Mastering-AI-Agents.git
cd Mastering-AI-Agents
```

Open `Demo_Data_Analysis.ipynb` in Colab or locally with Jupyter. The datasets are already in the repo root.

---

## Key Concepts Covered

- **Agentic loops** — perception → reasoning → action cycles
- **Tool use** — connecting agents to APIs and databases
- **Multi-agent orchestration** — routing, specialization, handoffs
- **Prompt patterns** — chain-of-thought, few-shot, ReAct
- **Governance** — scope control, hallucination mitigation, audit trails

---

## Author

**Prof. Dr. Ahirton Lopes** · [LinkedIn](https://linkedin.com/in/ahirtonlopes) · [Google Scholar](https://scholar.google.com/citations?user=1SQDVrwAAAAJ)

Contributions are welcome — open an issue or submit a pull request.

## License

[MIT](LICENSE)
