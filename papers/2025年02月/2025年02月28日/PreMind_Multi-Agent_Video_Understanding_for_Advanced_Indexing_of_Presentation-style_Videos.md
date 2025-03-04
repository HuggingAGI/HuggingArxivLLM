# PreMind：多智能体视频理解，助力演示式视频的高级索引

发布时间：2025年02月28日

`LLM应用

理由：这篇论文提出了一种创新的多智能体多模态框架PreMind，整合了视觉语言模型和其他大型模型来理解和索引演示类视频。该系统通过多模态分析和创新机制，支持问答等下游任务，属于大型语言模型的应用层面。` `视频处理` `信息检索`

> PreMind: Multi-Agent Video Understanding for Advanced Indexing of Presentation-style Videos

# 摘要

> 近年来，在线讲座视频已成为获取新知识的重要资源。能够有效理解和索引讲座视频的系统因此备受期待，它们能支持问答等下游任务，帮助用户高效定位视频中的具体信息。本研究提出PreMind，一个创新的多智能体多模态框架，通过整合各类大型模型实现对演示类视频的深度理解和索引。

PreMind首先借助视觉语言模型（VLM）提升现代镜头检测技术，将视频分割为幻灯片演示片段。随后，通过三个关键步骤分析每个片段以生成多模态索引：（1）提取幻灯片视觉内容，（2）转录语音叙述，（3）整合视觉与语音内容形成综合理解。此外，我们还提出了三项创新机制以提升性能：利用课前知识优化视觉理解，通过VLM检测/修正语音转录错误，以及引入评估智能体在视觉分析中实现动态迭代自我反思。

相较于传统视频索引方法，PreMind能够捕捉丰富可靠的多模态信息，使用户能够搜索仅在幻灯片上显示的缩略语等细节。我们在公开的LPM数据集和内部企业数据集上进行了系统性评估，验证了PreMind的有效性，并辅以详细分析支持结论。

> In recent years, online lecture videos have become an increasingly popular resource for acquiring new knowledge. Systems capable of effectively understanding/indexing lecture videos are thus highly desirable, enabling downstream tasks like question answering to help users efficiently locate specific information within videos. This work proposes PreMind, a novel multi-agent multimodal framework that leverages various large models for advanced understanding/indexing of presentation-style videos. PreMind first segments videos into slide-presentation segments using a Vision-Language Model (VLM) to enhance modern shot-detection techniques. Each segment is then analyzed to generate multimodal indexes through three key steps: (1) extracting slide visual content, (2) transcribing speech narratives, and (3) consolidating these visual and speech contents into an integrated understanding. Three innovative mechanisms are also proposed to improve performance: leveraging prior lecture knowledge to refine visual understanding, detecting/correcting speech transcription errors using a VLM, and utilizing a critic agent for dynamic iterative self-reflection in vision analysis. Compared to traditional video indexing methods, PreMind captures rich, reliable multimodal information, allowing users to search for details like abbreviations shown only on slides. Systematic evaluations on the public LPM dataset and an internal enterprise dataset are conducted to validate PreMind's effectiveness, supported by detailed analyses.

[Arxiv](https://arxiv.org/abs/2503.00162)