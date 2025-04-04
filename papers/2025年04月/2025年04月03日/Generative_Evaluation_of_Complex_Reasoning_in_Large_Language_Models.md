# # 复杂推理能力的生成式评估

发布时间：2025年04月03日

`LLM理论` `人工智能` `通用领域`

> Generative Evaluation of Complex Reasoning in Large Language Models

# 摘要

> 当大型语言模型（LLMs）展现出超越人类的推理能力时，一个关键问题浮现：它们是真正推理，还是仅仅从庞大的训练数据中检索答案？现有的公开基准测试一旦被纳入后续模型训练，就会失去评估价值。为解决这一难题，我们推出KUMO——专为评估LLMs推理能力设计的生成框架。KUMO巧妙结合LLMs与符号引擎，动态生成多样化、多轮、难度可调且部分可观测的推理任务。通过自动化流水线，KUMO持续在开放领域生成新任务，逼迫模型展现真正的泛化而非记忆能力。我们在KUMO创建的100个领域、5,000个任务上测试了23个顶尖LLMs，并将其推理能力与大学生对比。结果显示：LLMs在简单推理任务中已超越大学水平，推理增强的LLMs更在复杂推理中达到大学水准。此外，LLMs在KUMO任务上的表现与新发布的真实推理基准高度相关，证明了KUMO作为可靠评估工具的持久价值。

> With powerful large language models (LLMs) demonstrating superhuman reasoning capabilities, a critical question arises: Do LLMs genuinely reason, or do they merely recall answers from their extensive, web-scraped training datasets? Publicly released benchmarks inevitably become contaminated once incorporated into subsequent LLM training sets, undermining their reliability as faithful assessments. To address this, we introduce KUMO, a generative evaluation framework designed specifically for assessing reasoning in LLMs. KUMO synergistically combines LLMs with symbolic engines to dynamically produce diverse, multi-turn reasoning tasks that are partially observable and adjustable in difficulty. Through an automated pipeline, KUMO continuously generates novel tasks across open-ended domains, compelling models to demonstrate genuine generalization rather than memorization. We evaluated 23 state-of-the-art LLMs on 5,000 tasks across 100 domains created by KUMO, benchmarking their reasoning abilities against university students. Our findings reveal that many LLMs have outperformed university-level performance on easy reasoning tasks, and reasoning-scaled LLMs reach university-level performance on complex reasoning challenges. Moreover, LLM performance on KUMO tasks correlates strongly with results on newly released real-world reasoning benchmarks, underscoring KUMO's value as a robust, enduring assessment tool for genuine LLM reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2504.02810)