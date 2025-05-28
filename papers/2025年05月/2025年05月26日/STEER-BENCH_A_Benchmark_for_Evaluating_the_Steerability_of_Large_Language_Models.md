# STEER-BENCH：用于评估大型语言模型可控性的基准测试

发布时间：2025年05月26日

`LLM应用

摘要中讨论了大型语言模型（LLMs）在引导不同社区规范、视角和沟通风格方面的能力，并提出了一种基准测试方法Steer-Bench来评估这一能力。这属于LLM在实际应用中的评估和改进，因此归类为LLM应用。` `社交媒体` `社区管理`

> STEER-BENCH: A Benchmark for Evaluating the Steerability of Large Language Models

# 摘要

> 可引导性，即大型语言模型（LLMs）调整输出以适应不同社区规范、视角和沟通风格的能力，对于实际应用至关重要，但尚未得到充分评估。我们推出Steer-Bench，这是一个通过对比Reddit社区来评估特定人群引导能力的基准。涵盖19个领域内的30对鲜明对比的子社区，Steer-Bench包含10,000多个指令-响应对，并通过5,500个验证过的多项选择题及其银标签，测试与多样化社区规范的对齐程度。使用Steer-Bench对13个流行LLMs的评估显示，尽管人类专家在银标签下达到了81%的准确率，但表现最佳的模型仅能达到约65%的准确率，具体取决于领域和配置。部分模型在与人类级别的对齐方面落后超过15个百分点，凸显了在社区敏感引导能力上的显著差距。Steer-Bench旨在系统性评估LLMs对特定社区指令的理解能力、抵御对抗性引导尝试的鲁棒性，以及准确表达多元文化和意识形态观点的能力。

> Steerability, or the ability of large language models (LLMs) to adapt outputs to align with diverse community-specific norms, perspectives, and communication styles, is critical for real-world applications but remains under-evaluated. We introduce Steer-Bench, a benchmark for assessing population-specific steering using contrasting Reddit communities. Covering 30 contrasting subreddit pairs across 19 domains, Steer-Bench includes over 10,000 instruction-response pairs and validated 5,500 multiple-choice question with corresponding silver labels to test alignment with diverse community norms. Our evaluation of 13 popular LLMs using Steer-Bench reveals that while human experts achieve an accuracy of 81% with silver labels, the best-performing models reach only around 65% accuracy depending on the domain and configuration. Some models lag behind human-level alignment by over 15 percentage points, highlighting significant gaps in community-sensitive steerability. Steer-Bench is a benchmark to systematically assess how effectively LLMs understand community-specific instructions, their resilience to adversarial steering attempts, and their ability to accurately represent diverse cultural and ideological perspectives.

[Arxiv](https://arxiv.org/abs/2505.20645)