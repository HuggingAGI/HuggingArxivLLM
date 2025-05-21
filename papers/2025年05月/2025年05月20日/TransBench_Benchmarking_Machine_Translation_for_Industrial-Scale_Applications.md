# TransBench：为工业级应用打造的机器翻译评测基准

发布时间：2025年05月20日

`LLM应用` `跨境电商` `全球化行业`

> TransBench: Benchmarking Machine Translation for Industrial-Scale Applications

# 摘要

> 机器翻译（MT）已成为跨境电商、金融和法律服务等全球化行业中不可或缺的跨语言沟通工具。随着大型语言模型（LLMs）的突破性进展，翻译质量得到了显著提升。然而，将通用型MT模型应用于工业场景时，由于缺乏特定领域的术语、文化细微差别和风格习惯，暴露出关键局限性。现有评估框架未能充分评估专业场景下的性能，导致学术基准与实际效果之间存在差距。

为解决这一问题，我们提出一个三层翻译能力框架：（1）基础语言能力，（2）领域专业能力，（3）文化适应能力，强调在这些维度进行全面评估的必要性。我们引入TransBench，一个专为工业MT设计的基准测试，初期专注于国际电商，包含17,000个专业翻译句子，涵盖4个主要场景和33种语言组合。TransBench将传统指标（BLEU、TER）与领域特定评估模型Marco-MOS相结合，并提供可重复基准构建的指导原则。

我们的贡献包括：（1）工业MT评估的结构化框架，（2）首个公开的电商翻译基准测试，（3）探究多层级翻译质量的新指标，（4）开源评估工具。这项工作填补了评估空白，使研究者和实践者能够系统地评估和提升MT系统，以满足行业特定需求。

> Machine translation (MT) has become indispensable for cross-border communication in globalized industries like e-commerce, finance, and legal services, with recent advancements in large language models (LLMs) significantly enhancing translation quality. However, applying general-purpose MT models to industrial scenarios reveals critical limitations due to domain-specific terminology, cultural nuances, and stylistic conventions absent in generic benchmarks. Existing evaluation frameworks inadequately assess performance in specialized contexts, creating a gap between academic benchmarks and real-world efficacy. To address this, we propose a three-level translation capability framework: (1) Basic Linguistic Competence, (2) Domain-Specific Proficiency, and (3) Cultural Adaptation, emphasizing the need for holistic evaluation across these dimensions. We introduce TransBench, a benchmark tailored for industrial MT, initially targeting international e-commerce with 17,000 professionally translated sentences spanning 4 main scenarios and 33 language pairs. TransBench integrates traditional metrics (BLEU, TER) with Marco-MOS, a domain-specific evaluation model, and provides guidelines for reproducible benchmark construction. Our contributions include: (1) a structured framework for industrial MT evaluation, (2) the first publicly available benchmark for e-commerce translation, (3) novel metrics probing multi-level translation quality, and (4) open-sourced evaluation tools. This work bridges the evaluation gap, enabling researchers and practitioners to systematically assess and enhance MT systems for industry-specific needs.

[Arxiv](https://arxiv.org/abs/2505.14244)