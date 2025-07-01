# # AI生成的讲座幻灯片，助力提升幻灯片元素的检测与检索技术
AI生成的讲座幻灯片，用于改进幻灯片元素检测和检索。

发布时间：2025年06月30日

`LLM应用` `办公自动化` `内容生成`

> AI-Generated Lecture Slides for Improving Slide Element Detection and Retrieval

# 摘要

> 幻灯片元素检测与检索是理解幻灯片的核心问题。然而，训练有效模型需要大量人工标注，这不仅耗时耗力，还需要专业知识。为解决这一难题，我们开发了基于大型语言模型（LLM）的合成幻灯片生成工具SynLecSlideGen，能够生成高质量、连贯且逼真的幻灯片。我们还通过手动标注1,050张真实幻灯片创建了评估基准RealSlide。实验中，我们在真实数据上测试了基于合成幻灯片预训练的少量样本迁移学习模型。结果表明，与仅用真实数据训练相比，这种迁移学习方法显著提升了模型性能。这证明了合成数据在弥补标注幻灯片不足方面的有效性。我们的代码和资源已公开，访问地址为：https://synslidegen.github.io/。

> Lecture slide element detection and retrieval are key problems in slide understanding. Training effective models for these tasks often depends on extensive manual annotation. However, annotating large volumes of lecture slides for supervised training is labor intensive and requires domain expertise. To address this, we propose a large language model (LLM)-guided synthetic lecture slide generation pipeline, SynLecSlideGen, which produces high-quality, coherent and realistic slides. We also create an evaluation benchmark, namely RealSlide by manually annotating 1,050 real lecture slides. To assess the utility of our synthetic slides, we perform few-shot transfer learning on real data using models pre-trained on them. Experimental results show that few-shot transfer learning with pretraining on synthetic slides significantly improves performance compared to training only on real data. This demonstrates that synthetic data can effectively compensate for limited labeled lecture slides. The code and resources of our work are publicly available on our project website: https://synslidegen.github.io/.

[Arxiv](https://arxiv.org/abs/2506.23605)