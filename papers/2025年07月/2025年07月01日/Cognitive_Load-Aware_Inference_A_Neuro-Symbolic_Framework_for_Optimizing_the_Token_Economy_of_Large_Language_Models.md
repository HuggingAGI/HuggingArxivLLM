# 认知负荷感知推理：一种优化大型语言模型token经济的神经符号框架

发布时间：2025年07月01日

`LLM理论

摘要讨论了大型语言模型（LLM）推理的计算成本问题，并提出了一种基于认知负荷理论的新范式来优化推理过程。这属于对LLM本身的理论研究和改进，因此归类为LLM理论。` `人工智能`

> Cognitive Load-Aware Inference: A Neuro-Symbolic Framework for Optimizing the Token Economy of Large Language Models

# 摘要

> # 摘要
大型语言模型 (LLM) 推理的计算成本不断攀升，已成为其广泛应用和可持续部署的重大障碍。现有优化策略虽有效，但主要依赖统计启发式方法或架构修改，缺乏指导推理过程本身的认知理论。本文提出了一种全新范式——认知负荷感知推理 (CLAI) 框架，将认知负荷理论 (CLT) 和神经科学原理应用于 LLM 推理。我们引入了三个量化指标：内在认知负荷 ($ICL_{LLM}$)、外在认知负荷 ($ECL_{LLM}$) 和 germane 认知负荷 ($GCL_{LLM}$)，将推理过程转化为认知经济学优化问题：基于问题的内在复杂性 ($ICL_{LLM}$)，最小化计算浪费 ($ECL_{LLM}$)，并将令牌预算战略性分配给富有成效的推理 ($GCL_{LLM}$)。我们提出了两种实现路径：CLAI-Prompt，一种零-shot 方法，通过结构化的元提示引导基础 LLM 进行认知控制；以及 CLAI-Tune，一种微调模型，能够内化这些原则以实现认知经济。在复杂推理、长上下文问答和代码生成等基准测试中，我们的方法在不降低准确性的前提下，将令牌消耗减少了高达 45%。此外，CLAI-Tune 展现了自主分解难题的新兴能力，这是人类专家认知的关键特征。这项研究表明，通过模拟大脑的资源管理策略，我们可以构建更高效、健壮和强大的人工智能系统。

> The escalating computational costs of Large Language Model (LLM) inference have become a critical barrier to their widespread and sustainable deployment. While existing optimization strategies are effective, they are predominantly based on statistical heuristics or architectural modifications, lacking a guiding cognitive theory to manage the inference process itself. This paper aims to bridge this gap by introducing a novel paradigm: the Cognitive Load-Aware Inference (CLAI) framework, which operationalizes principles from Cognitive Load Theory (CLT) and neuroscience for LLM inference. We formalize the concepts of Intrinsic Cognitive Load, Extraneous Cognitive Load, and Germane Cognitive Load into quantifiable LLM metrics ($ICL_{LLM}$, $ECL_{LLM}$, and $GCL_{LLM}$), thereby reframing the inference process as a cognitive economics optimization problem: based on the intrinsic complexity of a problem ($ICL_{LLM}$), minimize wasteful computation ($ECL_{LLM}$), and strategically allocate the token budget to productive reasoning ($GCL_{LLM}$). We propose two implementation paths: CLAI-Prompt, a zero-shot method that guides a base LLM through cognitive control steps via a structured meta-prompt, and CLAI-Tune, a fine-tuned model that internalizes these principles for spontaneous cognitive economy. Across a range of benchmarks in complex reasoning, long-context question answering, and code generation, our methods achieve significant reductions in token consumption (up to 45\%) without sacrificing accuracy. Furthermore, CLAI-Tune exhibits an emergent ability to autonomously decompose difficult problems, a key characteristic of human expert cognition. This work demonstrates that by emulating the brain's resource management strategies, we can build more efficient, robust, and capable artificial intelligence systems.

[Arxiv](https://arxiv.org/abs/2507.00653)