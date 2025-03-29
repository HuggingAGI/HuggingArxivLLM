# JiraiBench：双语基准测试，用于评估大型语言模型在Jirai社区中识别人类自我毁灭行为内容的能力。

发布时间：2025年03月27日

`LLM应用` `社交媒体` `内容审核`

> JiraiBench: A Bilingual Benchmark for Evaluating Large Language Models' Detection of Human Self-Destructive Behavior Content in Jirai Community

# 摘要

> 本文介绍了JiraiBench，首个用于评估大型语言模型在中日社交媒体中检测自我毁灭内容的双语基准测试。聚焦于涵盖药物过量、饮食失调和自我伤害等多种行为的跨国“Jirai”网络亚文化，我们提出了一种结合语言和文化维度的全面评估框架。我们的数据集包含10,419条中文帖子和5,000条日文帖子，按照三个行为类别进行了多维度标注，实现了显著的标注者间一致。对四个最先进的模型进行的实验评估显示，基于指令语言的性能存在显著差异，令人意外的是，日语提示在处理中文内容时表现优于中文提示。这种新兴的跨文化迁移表明，在检测任务中，文化相近性有时可能超过语言相似性。使用微调模型进行的跨语言迁移实验进一步证明了在无需显式目标语言训练的情况下，这些语言系统之间存在知识迁移的潜力。这些发现凸显了在多语言内容审核中采取文化 informed 方法的必要性，并为开发更有效的在线脆弱社区检测系统提供了实证依据，证明文化背景的重要性。

> This paper introduces JiraiBench, the first bilingual benchmark for evaluating large language models' effectiveness in detecting self-destructive content across Chinese and Japanese social media communities. Focusing on the transnational "Jirai" (landmine) online subculture that encompasses multiple forms of self-destructive behaviors including drug overdose, eating disorders, and self-harm, we present a comprehensive evaluation framework incorporating both linguistic and cultural dimensions. Our dataset comprises 10,419 Chinese posts and 5,000 Japanese posts with multidimensional annotation along three behavioral categories, achieving substantial inter-annotator agreement. Experimental evaluations across four state-of-the-art models reveal significant performance variations based on instructional language, with Japanese prompts unexpectedly outperforming Chinese prompts when processing Chinese content. This emergent cross-cultural transfer suggests that cultural proximity can sometimes outweigh linguistic similarity in detection tasks. Cross-lingual transfer experiments with fine-tuned models further demonstrate the potential for knowledge transfer between these language systems without explicit target language training. These findings highlight the need for culturally-informed approaches to multilingual content moderation and provide empirical evidence for the importance of cultural context in developing more effective detection systems for vulnerable online communities.

[Arxiv](https://arxiv.org/abs/2503.21679)