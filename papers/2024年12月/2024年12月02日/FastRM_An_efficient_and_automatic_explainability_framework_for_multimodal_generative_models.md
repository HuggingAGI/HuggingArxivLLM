# FastRM：一个针对多模态生成模型的高效且自动的解释框架

发布时间：2024年12月02日

`LLM应用` `人工智能` `视觉语言模型`

> FastRM: An efficient and automatic explainability framework for multimodal generative models

# 摘要

> 尽管大型视觉语言模型（LVLMs）在对人类提示和视觉输入进行推理时表现出色，但仍易给出含错误信息的回应。识别无证据支撑的错误回应已成为构建可信人工智能的关键任务。像基于梯度的 LVLMs 输出相关性图这类可解释性方法能洞察模型的决策过程，然而这些方法往往计算成本高，不适用于对输出的即时验证。在本研究中，我们提出了 FastRM，这是预测 LVLM 模型可解释相关性图的有效方式。实验结果显示，使用 FastRM 使相关性图生成的计算时间减少 99.8%，所评估的 LVLM 的内存占用减少 44.4%，让可解释的人工智能更高效实用，从而有利于其在实际应用中的部署。

> While Large Vision Language Models (LVLMs) have become masterly capable in reasoning over human prompts and visual inputs, they are still prone to producing responses that contain misinformation. Identifying incorrect responses that are not grounded in evidence has become a crucial task in building trustworthy AI. Explainability methods such as gradient-based relevancy maps on LVLM outputs can provide an insight on the decision process of models, however these methods are often computationally expensive and not suited for on-the-fly validation of outputs. In this work, we propose FastRM, an effective way for predicting the explainable Relevancy Maps of LVLM models. Experimental results show that employing FastRM leads to a 99.8% reduction in compute time for relevancy map generation and an 44.4% reduction in memory footprint for the evaluated LVLM, making explainable AI more efficient and practical, thereby facilitating its deployment in real-world applications.

[Arxiv](https://arxiv.org/abs/2412.01487)