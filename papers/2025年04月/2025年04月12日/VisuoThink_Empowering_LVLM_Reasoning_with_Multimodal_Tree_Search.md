# VisuoThink：通过多模态树搜索赋能 LVLM 推理

发布时间：2025年04月12日

`LLM应用

理由：这篇论文探讨了大型视觉-语言模型在复杂任务中的应用，提出了一个新的框架VisuoThink，通过多模态慢思考和推理时间扩展来提升模型的推理能力。这属于对LLM的应用研究，特别是将其应用于视觉推理任务中。`

> VisuoThink: Empowering LVLM Reasoning with Multimodal Tree Search

# 摘要

> 大型视觉-语言模型的最新进展令人瞩目，但面对需要视觉辅助和逐步推理的复杂任务时，这些模型往往力不从心。现有方法虽尝试了基于文本的慢思考或基础视觉辅助，却未能完全捕捉人类视觉-语言推理过程的复杂交织性。受人类认知中慢思考机制启发，我们推出了VisuoThink——一个无缝整合视觉空间与语言领域的创新框架。它通过逐步的视觉-文本推理实现多模态慢思考，并借助前瞻式树搜索引入推理时间扩展。实验结果表明，VisuoThink显著提升了推理能力，即便未经微调，亦能在几何与空间推理任务中达到顶尖水平。

> Recent advancements in Large Vision-Language Models have showcased remarkable capabilities. However, they often falter when confronted with complex reasoning tasks that humans typically address through visual aids and deliberate, step-by-step thinking. While existing methods have explored text-based slow thinking or rudimentary visual assistance, they fall short of capturing the intricate, interleaved nature of human visual-verbal reasoning processes. To overcome these limitations and inspired by the mechanisms of slow thinking in human cognition, we introduce VisuoThink, a novel framework that seamlessly integrates visuospatial and linguistic domains. VisuoThink facilitates multimodal slow thinking by enabling progressive visual-textual reasoning and incorporates test-time scaling through look-ahead tree search. Extensive experiments demonstrate that VisuoThink significantly enhances reasoning capabilities via inference-time scaling, even without fine-tuning, achieving state-of-the-art performance in tasks involving geometry and spatial reasoning.

[Arxiv](https://arxiv.org/abs/2504.09130)