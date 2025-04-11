# 感受的奥秘：多模态大型语言模型如何突破情感推理边界

发布时间：2025年04月10日

`LLM应用` `情感分析`

> Why We Feel: Breaking Boundaries in Emotional Reasoning with Multimodal Large Language Models

# 摘要

> 现有的情感分析大多关注情绪本身（如开心、悲伤、愤怒），却忽视了情绪背后的根本原因。我们提出了一种名为情感解释（EI）的新方法，专注于分析引发情绪的因果因素，这些因素既包括显性的（如可观察的对象、人际互动），也包括隐性的（如文化背景、画外事件）。与传统的情感识别不同，EI不仅需要识别情绪，还需要深入推理情绪产生的触发因素。为了推动这一领域的研究，我们推出了EIBench，这是一个包含1,615个基础案例和50个复杂案例的大型基准数据集，涵盖了多维度的情感分析。每个案例都需要基于原因的详细解释，而不仅仅是简单的分类。我们还提出了一种粗细结合的自问自答（CFSA）注释流程，通过引导视觉语言模型（VLLMs）进行多轮问答迭代，从而生成高质量的标注。在开源和专有大型语言模型的四项实验设置中，广泛的评估结果显示了显著的性能差距，尤其是在更复杂的场景下，这凸显了EI在丰富富有同理心和语境感知的人工智能应用方面的潜力。我们的基准数据集和方法已在GitHub上公开发布：https://github.com/Lum1104/EIBench，为高级多模态因果分析和下一代情感计算奠定了基础。

> Most existing emotion analysis emphasizes which emotion arises (e.g., happy, sad, angry) but neglects the deeper why. We propose Emotion Interpretation (EI), focusing on causal factors-whether explicit (e.g., observable objects, interpersonal interactions) or implicit (e.g., cultural context, off-screen events)-that drive emotional responses. Unlike traditional emotion recognition, EI tasks require reasoning about triggers instead of mere labeling. To facilitate EI research, we present EIBench, a large-scale benchmark encompassing 1,615 basic EI samples and 50 complex EI samples featuring multifaceted emotions. Each instance demands rationale-based explanations rather than straightforward categorization. We further propose a Coarse-to-Fine Self-Ask (CFSA) annotation pipeline, which guides Vision-Language Models (VLLMs) through iterative question-answer rounds to yield high-quality labels at scale. Extensive evaluations on open-source and proprietary large language models under four experimental settings reveal consistent performance gaps-especially for more intricate scenarios-underscoring EI's potential to enrich empathetic, context-aware AI applications. Our benchmark and methods are publicly available at: https://github.com/Lum1104/EIBench, offering a foundation for advanced multimodal causal analysis and next-generation affective computing.

[Arxiv](https://arxiv.org/abs/2504.07521)