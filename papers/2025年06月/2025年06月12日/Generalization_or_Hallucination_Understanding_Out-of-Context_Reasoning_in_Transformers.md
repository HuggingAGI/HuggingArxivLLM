# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月12日

`LLM理论` `人工智能`

> Generalization or Hallucination? Understanding Out-of-Context Reasoning in Transformers

# 摘要

> 大型语言模型（LLMs）在微调过程中展现出一种令人费解的双重性：它们既能从新事实中进行卓越的推广，又容易编造错误信息。然而，这一现象背后的原因尚不明确。我们提出，这两种行为源于同一机制——“出上下文推理”（OCR），即通过关联概念（即使这些概念之间不存在因果关系）来推断其隐含意义的能力。我们对五个主流LLM的实验表明，OCR确实驱动了这种双重行为：当相关概念存在因果关系时，模型能实现有效推广；而当相关概念仅存在相关关系时，模型则容易产生错误信息。为了建立对这一现象的严谨理论理解，我们将OCR形式化为一种合成事实回忆任务。通过实证研究，我们发现，仅具备单层单头注意力机制且输出矩阵和值矩阵经过分解的Transformer模型能够学习解决这一任务，而具备合并权重的模型则无法做到，这凸显了矩阵分解的关键作用。我们的理论分析表明，OCR能力源于梯度下降的隐式偏差，这种偏差倾向于选择使合并输出-值矩阵的核范数最小化的解。这一数学结构解释了为何模型能够高效地学习关联事实与隐含意义，无论这种关联是因果性的还是仅仅是一种巧合。最终，我们的研究为理解OCR现象提供了理论基础，为分析和缓解知识注入带来的不良行为提供了新的视角。

> Large language models (LLMs) can acquire new knowledge through fine-tuning, but this process exhibits a puzzling duality: models can generalize remarkably from new facts, yet are also prone to hallucinating incorrect information. However, the reasons for this phenomenon remain poorly understood. In this work, we argue that both behaviors stem from a single mechanism known as out-of-context reasoning (OCR): the ability to deduce implications by associating concepts, even those without a causal link. Our experiments across five prominent LLMs confirm that OCR indeed drives both generalization and hallucination, depending on whether the associated concepts are causally related. To build a rigorous theoretical understanding of this phenomenon, we then formalize OCR as a synthetic factual recall task. We empirically show that a one-layer single-head attention-only transformer with factorized output and value matrices can learn to solve this task, while a model with combined weights cannot, highlighting the crucial role of matrix factorization. Our theoretical analysis shows that the OCR capability can be attributed to the implicit bias of gradient descent, which favors solutions that minimize the nuclear norm of the combined output-value matrix. This mathematical structure explains why the model learns to associate facts and implications with high sample efficiency, regardless of whether the correlation is causal or merely spurious. Ultimately, our work provides a theoretical foundation for understanding the OCR phenomenon, offering a new lens for analyzing and mitigating undesirable behaviors from knowledge injection.

[Arxiv](https://arxiv.org/abs/2506.10887)