# 苏格拉底式提问：掌握多模态推理的自我引导技巧

发布时间：2025年01月06日

`LLM应用

理由：这篇论文主要讨论的是如何通过创新的多轮训练和推理框架（命名为“苏格拉底式提问”）来提升轻量级多模态大型语言模型（MLLMs）在复杂视觉推理和问答任务中的表现。论文还提到创建了一个多模态小型数据集CapQA用于视觉指令调优和评估。这些内容主要涉及如何应用和改进大型语言模型（LLM）来解决实际问题，因此应归类为“LLM应用”。` `计算机视觉`

> Socratic Questioning: Learn to Self-guide Multimodal Reasoning in the Wild

# 摘要

> # 摘要
复杂的视觉推理仍是当前的一大挑战。通常，人们通过思维链（COT）和视觉指令调优等方法来应对这一挑战。然而，如何有机地结合这两种方法以取得更大成功，仍是一个未解之谜。此外，幻觉和高训练成本等问题也亟待解决。为此，我们设计了一个创新的多轮训练和推理框架，专为轻量级多模态大型语言模型（MLLMs）量身打造。我们的自我提问方法启发式地引导MLLMs聚焦于与目标问题相关的视觉线索，减少幻觉并提升模型描述细粒度图像细节的能力，从而使其在复杂的视觉推理和问答任务中表现出色。我们将这一框架命名为“苏格拉底式提问”（SQ）。为了推动未来研究，我们还创建了一个名为CapQA的多模态小型数据集，包含1k张细粒度活动图像，用于视觉指令调优和评估。实验表明，SQ方法在幻觉评分上提升了31.2%。我们在多个基准上的广泛实验进一步验证了SQ在启发式自我提问、零-shot视觉推理和幻觉缓解方面的卓越能力。我们的模型和代码将公开分享。

> Complex visual reasoning remains a key challenge today. Typically, the challenge is tackled using methodologies such as Chain of Thought (COT) and visual instruction tuning. However, how to organically combine these two methodologies for greater success remains unexplored. Also, issues like hallucinations and high training cost still need to be addressed. In this work, we devise an innovative multi-round training and reasoning framework suitable for lightweight Multimodal Large Language Models (MLLMs). Our self-questioning approach heuristically guides MLLMs to focus on visual clues relevant to the target problem, reducing hallucinations and enhancing the model's ability to describe fine-grained image details. This ultimately enables the model to perform well in complex visual reasoning and question-answering tasks. We have named this framework Socratic Questioning(SQ). To facilitate future research, we create a multimodal mini-dataset named CapQA, which includes 1k images of fine-grained activities, for visual instruction tuning and evaluation, our proposed SQ method leads to a 31.2% improvement in the hallucination score. Our extensive experiments on various benchmarks demonstrate SQ's remarkable capabilities in heuristic self-questioning, zero-shot visual reasoning and hallucination mitigation. Our model and code will be publicly available.

[Arxiv](https://arxiv.org/abs/2501.02964)