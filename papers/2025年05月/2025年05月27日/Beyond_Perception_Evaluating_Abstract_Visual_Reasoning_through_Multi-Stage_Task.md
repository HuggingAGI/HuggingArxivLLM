# 超越感知：深入探索多阶段任务中的抽象视觉推理能力

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型在抽象视觉推理任务中的应用，提出了新的基准和评估指标，属于对模型应用的研究。` `计算机视觉` `视觉推理`

> Beyond Perception: Evaluating Abstract Visual Reasoning through Multi-Stage Task

# 摘要

> 当前的多模态大型语言模型（MLLMs）在通用视觉推理方面表现出色，但在抽象视觉推理（AVR）领域仍有待深入探索。AVR需要更高阶的推理能力，以识别超越简单感知的抽象规则。现有的AVR基准主要集中在单步推理上，强调最终结果，但忽视了推理过程的多阶段性质。以往研究发现MLLMs在这些基准上表现不佳，但并未解释它们为何失败。为了解决这一差距，我们引入了MultiStAR，一个多阶段AVR基准，基于RAVEN设计，旨在评估不同复杂度水平的推理能力。此外，现有的指标如准确性仅关注最终结果，而未考虑中间步骤的正确性。因此，我们提出了一种新的指标MSEval，它不仅考虑最终结果，还考虑中间步骤的正确性。我们使用17个具有代表性的闭源和开源MLLMs在MultiStAR上进行了全面实验。结果显示，尽管现有的MLLMs在基本感知任务上表现尚可，但他们在更复杂的规则检测阶段仍然面临挑战。

> Current Multimodal Large Language Models (MLLMs) excel in general visual reasoning but remain underexplored in Abstract Visual Reasoning (AVR), which demands higher-order reasoning to identify abstract rules beyond simple perception. Existing AVR benchmarks focus on single-step reasoning, emphasizing the end result but neglecting the multi-stage nature of reasoning process. Past studies found MLLMs struggle with these benchmarks, but it doesn't explain how they fail. To address this gap, we introduce MultiStAR, a Multi-Stage AVR benchmark, based on RAVEN, designed to assess reasoning across varying levels of complexity. Additionally, existing metrics like accuracy only focus on the final outcomes while do not account for the correctness of intermediate steps. Therefore, we propose a novel metric, MSEval, which considers the correctness of intermediate steps in addition to the final outcomes. We conduct comprehensive experiments on MultiStAR using 17 representative close-source and open-source MLLMs. The results reveal that while existing MLLMs perform adequately on basic perception tasks, they continue to face challenges in more complex rule detection stages.

[Arxiv](https://arxiv.org/abs/2505.21850)