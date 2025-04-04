# VEGAS: 从视觉可解释性迈向基于现实的人工社会智能

发布时间：2025年04月02日

`LLM应用` `多模态模型`

> VEGAS: Towards Visually Explainable and Grounded Artificial Social Intelligence

# 摘要

> 社交智能查询（Social-IQ）作为评估模型社交智能水平的主要多模态基准。尽管当前解决方案在多项选择题（MCQ）中表现出了令人印象深刻的准确性，但它们对语言模态的依赖性过高，甚至完全忽视了视觉上下文。此外，封闭式的特性限制了我们对推理路径正确性的探索。为了解决这些限制，我们提出了视觉可解释且基于 grounding 的人工社交智能模型（VEGAS）。作为生成式多模态模型，VEGAS 通过开放式的回答方式提供可解释的回复，从而增强了推理路径的清晰度和可评估性。为了实现视觉 grounding 的回答，我们提出了一种新颖的采样策略，为模型提供更具相关性的视觉帧。随后，我们通过通用指令微调（GIFT）增强了模型对这些帧的解释能力，旨在：i) 学习基本情感社交特征的多模态语言转换，ii) 建立多模态联合推理能力。广泛的实验，包括模态消融、开放式评估和有监督的 MCQ 评估，一致表明 VEGAS 能够有效利用视觉信息进行推理，生成正确且可信的答案。我们希望这项工作能为 Social-IQ 提供新的视角，并推动类人社交 AI 的发展。

> Social Intelligence Queries (Social-IQ) serve as the primary multimodal benchmark for evaluating a model's social intelligence level. While impressive multiple-choice question(MCQ) accuracy is achieved by current solutions, increasing evidence shows that they are largely, and in some cases entirely, dependent on language modality, overlooking visual context. Additionally, the closed-set nature further prevents the exploration of whether and to what extent the reasoning path behind selection is correct. To address these limitations, we propose the Visually Explainable and Grounded Artificial Social Intelligence (VEGAS) model. As a generative multimodal model, VEGAS leverages open-ended answering to provide explainable responses, which enhances the clarity and evaluation of reasoning paths. To enable visually grounded answering, we propose a novel sampling strategy to provide the model with more relevant visual frames. We then enhance the model's interpretation of these frames through Generalist Instruction Fine-Tuning (GIFT), which aims to: i) learn multimodal-language transformations for fundamental emotional social traits, and ii) establish multimodal joint reasoning capabilities. Extensive experiments, comprising modality ablation, open-ended assessments, and supervised MCQ evaluations, consistently show that VEGAS effectively utilizes visual information in reasoning to produce correct and also credible answers. We expect this work to of fer a new perspective on Social-IQ and advance the development of human-like social AI.

[Arxiv](https://arxiv.org/abs/2504.02227)