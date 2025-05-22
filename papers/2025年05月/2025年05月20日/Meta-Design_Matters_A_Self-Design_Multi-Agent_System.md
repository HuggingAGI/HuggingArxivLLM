# # 元设计的重要性：自我设计的多智能体系统

发布时间：2025年05月20日

`Agent` `软件工程`

> Meta-Design Matters: A Self-Design Multi-Agent System

# 摘要

> 多智能体系统（MAS）借助大型语言模型（LLMs）的强大能力，在处理复杂任务方面展现出巨大潜力。然而，当前大多数MAS依赖人工设计的智能体角色和通信协议，这些设计往往难以充分发挥LLMs的优势，也难以适应新任务。近期的自动MAS方法虽试图解决这些问题，但通常需要验证集进行调整，且生成的MAS设计在推理过程中缺乏灵活性。我们提出SELF-MAS，这是首个用于自动MAS设计的自监督、仅推理时间框架。通过元级别设计，SELF-MAS针对每个问题实例迭代生成、评估和优化MAS配置，无需验证集。更重要的是，它通过可解性和完整性的元反馈实现了动态智能体组合和问题分解。在数学、研究生水平问答和软件工程基准测试中，使用不同规模的闭源和开源LLM模型进行的实验表明，SELF-MAS在性能上超越了手动和自动MAS基线，相比最强基线平均准确率提升了7.44%，同时保持了成本效益。这些发现凸显了元级别自监督设计在创建有效且适应性强的MAS方面的潜力。

> Multi-agent systems (MAS) leveraging the impressive capabilities of Large Language Models (LLMs) hold significant potential for tackling complex tasks. However, most current MAS depend on manually designed agent roles and communication protocols. These manual designs often fail to align with the underlying LLMs' strengths and struggle to adapt to novel tasks. Recent automatic MAS approaches attempt to mitigate these limitations but typically necessitate a validation-set for tuning and yield static MAS designs lacking adaptability during inference. We introduce SELF-MAS, the first self-supervised, inference-time only framework for automatic MAS design. SELF-MAS employs meta-level design to iteratively generate, evaluate, and refine MAS configurations tailored to each problem instance, without requiring a validation set. Critically, it enables dynamic agent composition and problem decomposition through meta-feedback on solvability and completeness. Experiments across math, graduate-level QA, and software engineering benchmarks, using both closed-source and open-source LLM back-bones of varying sizes, demonstrate that SELF-MAS outperforms both manual and automatic MAS baselines, achieving a 7.44% average accuracy improvement over the next strongest baseline while maintaining cost-efficiency. These findings underscore the promise of meta-level self-supervised design for creating effective and adaptive MAS.

[Arxiv](https://arxiv.org/abs/2505.14996)