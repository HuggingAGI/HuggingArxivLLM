# MMReason：一个开放性多模态多步骤推理基准，面向多语言大语言模型迈向AGI

发布时间：2025年06月30日

`LLM应用` `人工智能`

> MMReason: An Open-Ended Multi-Modal Multi-Step Reasoning Benchmark for MLLMs Toward AGI

# 摘要

> 推理在推动多模态大型语言模型（MLLMs）向人工通用智能迈进的过程中发挥着至关重要的作用。然而，现有的MLLM基准测试在从三个方面精确且全面评估长链推理能力时往往表现不足：(1) 缺乏难度和多样性，(2) 易受猜测性和记忆性影响，(3) 对中间推理步骤的评估不充分。为了填补这一空白，我们引入了MMReason，一个全新的基准测试，旨在通过多样化的、开放式的、具有挑战性的题目，精确且全面地评估MLLM的长链推理能力。首先，我们从多个领域（即6个学科）和多个难度级别（即从大学前到大学，从基础到竞赛水平）中精选需要多步推理的具有挑战性的问题。其次，这些问题被重新表述为开放式的格式，并通过多模型投票技术进行筛选，以消除与猜测和记忆相关的捷径案例，确保对推理能力的稳健评估。第三，我们为问题提供了详细的分步解答，并设计了一个基于参考的三元评分机制，以可靠地评估中间推理步骤。通过MMReason，我们对流行的领先MLLM进行了基准测试，并对其推理能力进行了深入分析。我们希望MMReason能够成为推动MLLM推理研究的宝贵资源。代码将在https://github.com/HJYao00/MMReason上提供。

> Reasoning plays a crucial role in advancing Multimodal Large Language Models (MLLMs) toward Artificial General Intelligence. However, existing MLLM benchmarks often fall short in precisely and comprehensively evaluating long-chain reasoning abilities from three key aspects: (1) lack of difficulty and diversity, (2) susceptibility to guessability and memorization, (3) inadequate assessment of intermediate reasoning steps. To fill this gap, we introduce MMReason, a new benchmark designed to precisely and comprehensively evaluate MLLM long-chain reasoning capability with diverse, open-ended, challenging questions. First, we curate challenging questions requiring multi-step reasoning from various fields (i.e., 6 disciplines) and multiple difficulty levels (i.e., from pre-university to university, and from foundational to competition tiers). Second, these questions are reformulated into an open-ended format and filtered using a multi-model voting technique to eliminate shortcut cases related to guessing and memorization, ensuring robust reasoning evaluations. Third, we annotate the questions with detailed step-by-step solutions, and design a reference-based ternary scoring mechanism to reliably assess intermediate reasoning steps. With MMReason, we benchmark popular leading MLLMs and provide an in-depth analysis of their reasoning capabilities. We hope MMReason will serve as a valuable resource for advancing MLLM reasoning research. Code will be available at https://github.com/HJYao00/MMReason.

[Arxiv](https://arxiv.org/abs/2506.23563)