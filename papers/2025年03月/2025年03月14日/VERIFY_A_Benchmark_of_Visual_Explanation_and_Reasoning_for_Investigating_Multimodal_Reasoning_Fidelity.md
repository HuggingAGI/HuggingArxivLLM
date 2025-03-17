# VERIFY: 探究多模态推理保真度的视觉解释与推理基准测试

发布时间：2025年03月14日

`LLM应用

理由：这篇论文探讨了多模态大语言模型（MLLMs）在视觉推理任务中的应用，提出了新的基准测试VERIFY，用于评估模型的视觉推理能力。这属于将LLM应用于特定任务的范畴。` `基准测试`

> VERIFY: A Benchmark of Visual Explanation and Reasoning for Investigating Multimodal Reasoning Fidelity

# 摘要

> 视觉推理是人类认知的关键能力，使我们能够理解和抽象地解读周围环境。尽管近期的多模态大语言模型（MLLMs）在语言和视觉-语言任务中表现卓越，但现有评估基准主要关注基于识别的技能，未能充分考察真正的视觉推理能力。为弥补这一重要缺口，我们推出了VERIFY，首个专注于分离和严格评估先进MLLMs视觉推理能力的基准测试。VERIFY要求模型主要依赖视觉信息进行推理，仅提供少量文本上下文，以减少对特定领域知识和语言偏见的依赖。每个问题都附有经人工标注的推理路径，使其成为首个深入剖析模型决策过程的基准测试。我们还提出了超越传统准确性的新颖评估指标，揭示了当前模型推理模式中的关键失衡。对领先MLLMs的全面评估揭示了其重大局限性，凸显了在感知与推理间寻求平衡、采取整体方法的必要性。更多详情与测试，请访问我们的项目页面（https://verify-eqh.pages.dev/）。

> Visual reasoning is central to human cognition, enabling individuals to interpret and abstractly understand their environment. Although recent Multimodal Large Language Models (MLLMs) have demonstrated impressive performance across language and vision-language tasks, existing benchmarks primarily measure recognition-based skills and inadequately assess true visual reasoning capabilities. To bridge this critical gap, we introduce VERIFY, a benchmark explicitly designed to isolate and rigorously evaluate the visual reasoning capabilities of state-of-the-art MLLMs. VERIFY compels models to reason primarily from visual information, providing minimal textual context to reduce reliance on domain-specific knowledge and linguistic biases. Each problem is accompanied by a human-annotated reasoning path, making it the first to provide in-depth evaluation of model decision-making processes. Additionally, we propose novel metrics that assess visual reasoning fidelity beyond mere accuracy, highlighting critical imbalances in current model reasoning patterns. Our comprehensive benchmarking of leading MLLMs uncovers significant limitations, underscoring the need for a balanced and holistic approach to both perception and reasoning. For more teaser and testing, visit our project page (https://verify-eqh.pages.dev/).

[Arxiv](https://arxiv.org/abs/2503.11557)