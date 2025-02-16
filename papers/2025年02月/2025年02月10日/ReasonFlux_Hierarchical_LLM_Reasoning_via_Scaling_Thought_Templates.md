# ReasonFlux: 通过扩展思维模板实现分层LLM推理

发布时间：2025年02月10日

`LLM应用` `数学教育`

> ReasonFlux: Hierarchical LLM Reasoning via Scaling Thought Templates

# 摘要

> 我们提出，通过扩展思维模板实现的层次化LLM推理，能够有效优化推理搜索空间，并显著超越像OpenAI o1-preview和DeepSeek V3这样强大LLMs的数学推理能力。我们仅使用8个GPU训练了ReasonFlux-32B模型，并带来了三项创新：(i)一个结构化且通用的思维模板库，包含约500个高层思维模板，能够推广到相似或相关的推理问题；(ii)在一系列思维模板上进行层次化强化学习，通过优化基础LLM来规划处理复杂问题的最优模板轨迹；(iii)一个全新的推理扩展系统，通过在推理时自适应扩展思维模板，实现层次化LLM推理。借助包含顺序思维模板的模板轨迹，ReasonFlux-32B显著提升了数学推理能力，达到了当前最优水平。在MATH基准测试中，准确率达到91.2%，比o1-preview高出6.7%。在美国数学奥林匹克（AIME）基准测试中，ReasonFlux-32B平均解决了56.7%的问题，分别比o1-preview和DeepSeek-V3高出27%和45%。代码：https://github.com/Gen-Verse/ReasonFlux

> We present that hierarchical LLM reasoning via scaling thought templates can effectively optimize the reasoning search space and outperform the mathematical reasoning capabilities of powerful LLMs like OpenAI o1-preview and DeepSeek V3. We train our ReasonFlux-32B model with only 8 GPUs and introduces three innovations: (i) a structured and generic thought template library, containing around 500 high-level thought templates capable of generalizing to similar or relevant reasoning problems; (ii) performing hierarchical reinforcement learning on a sequence of thought templates instead of long CoTs, optimizing a base LLM to plan out an optimal template trajectory for gradually handling complex problems; (iii) a brand new inference scaling system that enables hierarchical LLM reasoning by adaptively scaling thought templates at inference time. With a template trajectory containing sequential thought templates, our ReasonFlux-32B significantly advances math reasoning capabilities to state-of-the-art levels. Notably, on the MATH benchmark, it achieves an accuracy of 91.2% and surpasses o1-preview by 6.7%. On the USA Math Olympiad (AIME) benchmark, ReasonFlux-32B solves an average of 56.7% of problems, surpassing o1-preview and DeepSeek-V3 by 27% and 45%, respectively. Code: https://github.com/Gen-Verse/ReasonFlux

[Arxiv](https://arxiv.org/abs/2502.06772)