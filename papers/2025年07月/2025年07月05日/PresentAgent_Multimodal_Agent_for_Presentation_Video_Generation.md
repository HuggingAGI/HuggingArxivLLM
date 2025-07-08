# PresentAgent：演示视频生成的多模态智能体

发布时间：2025年07月05日

`Agent

理由：这篇论文介绍了PresentAgent，一个多模态智能体，能够将长篇文档转化为带解说的演示视频。它突破了现有方法的限制，生成与语音内容完美同步的视觉内容，效果可与人类风格的演示相媲美。该智能体采用模块化处理流程，结合大型语言模型和语音合成模型，生成情境化的语音解说，并精准对齐音画，无缝合成最终视频。此外，还引入了PresentEval，一个基于视觉语言模型的统一评估框架，从内容忠实度、视觉清晰度和观众理解度三个关键维度对视频进行综合评分。这些特征表明，这篇论文主要关注智能体的设计和应用，因此应归类为Agent。` `演示文稿` `视频生成`

> PresentAgent: Multimodal Agent for Presentation Video Generation

# 摘要

> 我们推出 PresentAgent，一款能够将长篇文档转化为带解说的演示视频的多模态智能体。现有方法通常局限于生成静态幻灯片或文本摘要，而我们的方法突破了这些限制，能够生成与语音内容完美同步的视觉内容，其效果可与人类风格的演示相媲美。为了实现这一整合，PresentAgent采用了一套模块化处理流程，系统性地对输入文档进行分段，规划并呈现幻灯片风格的视觉画面，借助大型语言模型和语音合成模型生成情境化的语音解说，并精准对齐音画，无缝合成最终视频。考虑到多模态输出评估的复杂性，我们引入了PresentEval，一个基于视觉语言模型的统一评估框架，通过提示词驱动的评估方式，从内容忠实度、视觉清晰度和观众理解度三个关键维度对视频进行综合评分。我们在精心整理的30对文档-演示文稿数据集上的实验验证表明，PresentAgent在所有评估指标上都达到了接近人类水平的质量。这些结果凸显了可控多模态智能体在将静态文本材料转化为动态、有效且易于获取的演示格式方面的巨大潜力。代码将在 https://github.com/AIGeeksGroup/PresentAgent 上发布。

> We present PresentAgent, a multimodal agent that transforms long-form documents into narrated presentation videos. While existing approaches are limited to generating static slides or text summaries, our method advances beyond these limitations by producing fully synchronized visual and spoken content that closely mimics human-style presentations. To achieve this integration, PresentAgent employs a modular pipeline that systematically segments the input document, plans and renders slide-style visual frames, generates contextual spoken narration with large language models and Text-to-Speech models, and seamlessly composes the final video with precise audio-visual alignment. Given the complexity of evaluating such multimodal outputs, we introduce PresentEval, a unified assessment framework powered by Vision-Language Models that comprehensively scores videos across three critical dimensions: content fidelity, visual clarity, and audience comprehension through prompt-based evaluation. Our experimental validation on a curated dataset of 30 document-presentation pairs demonstrates that PresentAgent approaches human-level quality across all evaluation metrics. These results highlight the significant potential of controllable multimodal agents in transforming static textual materials into dynamic, effective, and accessible presentation formats. Code will be available at https://github.com/AIGeeksGroup/PresentAgent.

[Arxiv](https://arxiv.org/abs/2507.04036)