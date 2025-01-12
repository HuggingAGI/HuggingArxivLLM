# Centurio: 大型视觉-语言模型多语言能力的驱动因素探究

发布时间：2025年01月09日

`LLM应用

**理由**：这篇论文主要探讨了大规模多语言视觉-语言模型（LVLMs）的训练策略，特别是如何通过调整训练数据的语言分布和引入多语言OCR数据来提升模型在多语言环境下的性能。虽然涉及多语言和视觉-语言模型，但其核心关注点是如何优化和提升LLM在多语言任务中的应用效果，因此应归类为LLM应用。` `多语言处理`

> Centurio: On Drivers of Multilingual Ability of Large Vision-Language Model

# 摘要

> 目前大多数大型视觉-语言模型（LVLMs）主要依赖英语数据进行训练，导致其在处理非英语输入和生成目标语言输出时表现欠佳。现有方法通过增加多语言训练数据来缓解这一问题，但缺乏对不同训练组合如何影响不同语言群体的深入理解。本研究全面探讨了大规模多语言LVLMs的训练策略。我们通过一系列多阶段实验，覆盖13个视觉-语言任务和43种语言，系统研究了：（1）在不影响英语性能的前提下可包含的训练语言数量，（2）预训练数据的最佳语言分布，以及（3）指令调优数据的最佳语言分布。此外，我们还（4）探索了如何提升多语言图像中的文本理解能力，并为此引入了一个新的基准。令人惊讶的是，分析表明，可以（i）同时包含多达100种训练语言，（ii）仅使用25-50%的非英语数据，即可显著提升多语言性能，同时保持强大的英语能力。我们还发现，（iii）在预训练和指令调优中加入非英语OCR数据对提升多语言图像中的文本理解至关重要。最终，我们整合所有发现，训练了支持100种语言的LVLM——Centurio，其在涵盖14个任务和56种语言的评估中展现了最先进的性能。

> Most Large Vision-Language Models (LVLMs) to date are trained predominantly on English data, which makes them struggle to understand non-English input and fail to generate output in the desired target language. Existing efforts mitigate these issues by adding multilingual training data, but do so in a largely ad-hoc manner, lacking insight into how different training mixes tip the scale for different groups of languages. In this work, we present a comprehensive investigation into the training strategies for massively multilingual LVLMs. First, we conduct a series of multi-stage experiments spanning 13 downstream vision-language tasks and 43 languages, systematically examining: (1) the number of training languages that can be included without degrading English performance and (2) optimal language distributions of pre-training as well as (3) instruction-tuning data. Further, we (4) investigate how to improve multilingual text-in-image understanding, and introduce a new benchmark for the task. Surprisingly, our analysis reveals that one can (i) include as many as 100 training languages simultaneously (ii) with as little as 25-50\% of non-English data, to greatly improve multilingual performance while retaining strong English performance. We further find that (iii) including non-English OCR data in pre-training and instruction-tuning is paramount for improving multilingual text-in-image understanding. Finally, we put all our findings together and train Centurio, a 100-language LVLM, offering state-of-the-art performance in an evaluation covering 14 tasks and 56 languages.

[Arxiv](https://arxiv.org/abs/2501.05122)