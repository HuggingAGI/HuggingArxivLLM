# # 看见 vs 回忆：使用多模态大语言模型解决可视化问答任务时，视觉作用的合理性检验

发布时间：2025年04月13日

`LLM应用` `人工智能` `可视化`

> See or Recall: A Sanity Check for the Role of Vision in Solving Visualization Question Answer Tasks with Multimodal LLMs

# 摘要

> 近年来，多模态大型语言模型（MLLM）的发展使语言模型能够同时理解和推理视觉与语言信息，从而能够感知并回答多种设计和任务中的数据可视化问题。然而，将MLLM应用于可视化任务的评估发现了一个有趣的现象：在可视化问答（VisQA）任务中，即使没有可视化，模型也能够正确回答相当一部分问题，无论是否提供选项。这表明MLLM的推理方式与人类存在本质差异。

我们提出了一种综合的合理性检查框架，结合基于规则的决策树和合理性检查表，分离“观察”（视觉处理）与“回忆”（依赖知识）的影响。这一框架能够验证VisQA数据集的评估效果，揭示模型真正“观察”的地方，以及它们如何受到事实记忆的正面或负面影响，或依赖归纳偏见来回答问题。这一发现强调了在利用MLLM进行可视化理解研究时，需要更加谨慎地设计评估方法。

> Recent developments in multimodal large language models (MLLM) have equipped language models to reason about vision and language jointly. This permits MLLMs to both perceive and answer questions about data visualization across a variety of designs and tasks. Applying MLLMs to a broad range of visualization tasks requires us to properly evaluate their capabilities, and the most common way to conduct evaluation is through measuring a model's visualization reasoning capability, analogous to how we would evaluate human understanding of visualizations (e.g., visualization literacy). However, we found that in the context of visualization question answering (VisQA), how an MLLM perceives and reasons about visualizations can be fundamentally different from how humans approach the same problem. During the evaluation, even without visualization, the model could correctly answer a substantial portion of the visualization test questions, regardless of whether any selection options were provided. We hypothesize that the vast amount of knowledge encoded in the language model permits factual recall that supersedes the need to seek information from the visual signal. It raises concerns that the current VisQA evaluation may not fully capture the models' visualization reasoning capabilities. To address this, we propose a comprehensive sanity check framework that integrates a rule-based decision tree and a sanity check table to disentangle the effects of "seeing" (visual processing) and "recall" (reliance on prior knowledge). This validates VisQA datasets for evaluation, highlighting where models are truly "seeing", positively or negatively affected by the factual recall, or relying on inductive biases for question answering. Our study underscores the need for careful consideration in designing future visualization understanding studies when utilizing MLLMs.

[Arxiv](https://arxiv.org/abs/2504.09809)