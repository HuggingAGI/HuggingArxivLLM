# 3DGen-Bench：首个全面的3D生成模型基准测试套件

发布时间：2025年03月27日

`LLM应用` `3D生成` `生成模型`

> 3DGen-Bench: Comprehensive Benchmark Suite for 3D Generative Models

# 摘要

> 3D生成技术正以惊人的速度进步，然而3D评估技术的发展却未能跟上步伐。如何让自动评估与人类感知保持公平一致，已成为该领域公认的重大挑战。在语言和图像生成领域，近期的研究已成功探索了人类偏好，并展现出令人瞩目的拟合能力。然而，3D领域至今仍缺乏一个全面的生成模型偏好数据集。为了解决这一问题，我们开发了3DGen-Arena——一个以竞技模式运行的综合平台。通过精心设计多样化的文本和图像提示，并借助3DGen-Arena平台，我们从公共用户和专家标注者那里收集了大量的人类偏好数据，最终构建了大规模的多维度人类偏好数据集3DGen-Bench。基于这一数据集，我们进一步开发了两个创新模型：基于CLIP的评分模型3DGen-Score，以及基于MLLM的自动评估器3DGen-Eval。这两个模型首次实现了文本到3D和图像到3D生成质量评估的统一，并通过各自独特的优势，共同构成了一个功能强大的自动化评估系统。通过大量实验验证，我们的评分模型在预测人类偏好方面表现卓越，与现有评估指标相比，其与人类排名的相关性显著提升。我们相信，3DGen-Bench数据集和自动化评估系统的推出，将为3D生成领域带来更加公平的评估标准，从而进一步推动3D生成模型及其下游应用的发展。

> 3D generation is experiencing rapid advancements, while the development of 3D evaluation has not kept pace. How to keep automatic evaluation equitably aligned with human perception has become a well-recognized challenge. Recent advances in the field of language and image generation have explored human preferences and showcased respectable fitting ability. However, the 3D domain still lacks such a comprehensive preference dataset over generative models. To mitigate this absence, we develop 3DGen-Arena, an integrated platform in a battle manner. Then, we carefully design diverse text and image prompts and leverage the arena platform to gather human preferences from both public users and expert annotators, resulting in a large-scale multi-dimension human preference dataset 3DGen-Bench. Using this dataset, we further train a CLIP-based scoring model, 3DGen-Score, and a MLLM-based automatic evaluator, 3DGen-Eval. These two models innovatively unify the quality evaluation of text-to-3D and image-to-3D generation, and jointly form our automated evaluation system with their respective strengths. Extensive experiments demonstrate the efficacy of our scoring model in predicting human preferences, exhibiting a superior correlation with human ranks compared to existing metrics. We believe that our 3DGen-Bench dataset and automated evaluation system will foster a more equitable evaluation in the field of 3D generation, further promoting the development of 3D generative models and their downstream applications.

[Arxiv](https://arxiv.org/abs/2503.21745)