# # 实证研究：探索与优化 R1 类推理模型

发布时间：2025年03月06日

`LLM应用

理由：这篇论文探讨了强化学习（RL）训练和工具操控在提升大型语言模型推理能力中的应用，属于模型的实际应用和优化，因此归类为LLM应用。` `人工智能`

> An Empirical Study on Eliciting and Improving R1-like Reasoning Models

# 摘要

> # 技术报告
本报告为STILL项目中慢思考模型开发的第三份技术文档。随着技术路径日益清晰，强化学习（RL）训练的扩展已成为实现推理模型的核心技巧。我们系统性地探索了影响强化学习训练的各类因素，并在基础模型与微调模型上进行了实验，详细记录了它们的效果。具体而言，我们的强化学习训练方法显著提升了Qwen2.5-32B基础模型的表现，不仅延长了回答长度，还提高了测试准确率。此外，我们发现，即使像DeepSeek-R1-Distill-Qwen-1.5B这样的高性能模型，通过强化学习训练仍能进一步优化，在AIME 2024上达到了39.33%的准确率。除了强化学习训练，我们还探索了工具操控的运用，发现它能显著提升大型推理模型的推理性能。该方法在AIME 2024上通过贪心搜索实现了86.67%的优异准确率，充分证明了其在增强模型能力方面的有效性。我们的资源已发布在STILL项目网站：https://github.com/RUCAIBox/Slow_Thinking_with_LLMs。

> In this report, we present the third technical report on the development of slow-thinking models as part of the STILL project. As the technical pathway becomes clearer, scaling RL training has become a central technique for implementing such reasoning models. We systematically experiment with and document the effects of various factors influencing RL training, conducting experiments on both base models and fine-tuned models. Specifically, we demonstrate that our RL training approach consistently improves the Qwen2.5-32B base models, enhancing both response length and test accuracy. Furthermore, we show that even when a model like DeepSeek-R1-Distill-Qwen-1.5B has already achieved a high performance level, it can be further refined through RL training, reaching an accuracy of 39.33% on AIME 2024. Beyond RL training, we also explore the use of tool manipulation, finding that it significantly boosts the reasoning performance of large reasoning models. This approach achieves a remarkable accuracy of 86.67% with greedy search on AIME 2024, underscoring its effectiveness in enhancing model capabilities. We release our resources at the STILL project website: https://github.com/RUCAIBox/Slow_Thinking_with_LLMs.

[Arxiv](https://arxiv.org/abs/2503.04548)