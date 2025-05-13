# 你的多模态大语言模型能胜任科学辅导老师吗？

发布时间：2025年05月09日

`LLM应用

理由：该论文主要探讨了多模态大型语言模型在教育领域的应用，特别是如何通过评估框架和微调方法提升其作为科学辅导系统的能力。研究集中在模型的实际应用和性能优化，属于LLM应用的范畴。` `辅导系统`

> Is your multimodal large language model a good science tutor?

# 摘要

> 多模态大型语言模型（MLLMs）在科学推理任务（如ScienceQA）中表现出色，但现有评估基准往往只关注最终答案的准确性，忽视了其他关键指标。特别是在教育领域，MLLMs不仅要准确，更要具备教学能力。本文提出了一种全新框架，通过全面的教育评分标准和模拟学生模型，将MLLMs作为科学辅导系统进行评估。针对一系列候选MLLM科学辅导系统，我们利用基于评分标准的学生评价生成辅导表现分数，精准识别出优秀和不足的辅导系统。基于ScienceQA数据集的训练部分，我们构建了一个对比数据集，将优秀和不足辅导系统的输出进行配对比较。这使我们能够应用多种偏好优化方法，对表现不佳的辅导模型（如Qwen2-VL-2B）进行微调，使其教学效果显著提升。研究发现，强大的问题解决能力并不必然带来高质量的教学，而基于性能优化的改进可以生成更具教育意义的辅导模型。这一方法为构建MLLMs开辟了新途径，使其不仅能够解决问题，还能成为真正有益的教育助手。

> Multimodal large language models (MLLMs) demonstrate impressive performance on scientific reasoning tasks (e.g., ScienceQA). However, most existing benchmarks focus narrowly on the accuracy of the final answer while ignoring other metrics. In particular, when applying MLLMs to educational contexts, the goal is not only correctness but also the ability to teach. In this paper, we propose a framework that evaluates MLLMs as science tutors using a comprehensive educational rubric and a simulated student model that judges the teaching performance of the tutors. Given a list of candidate MLLM science tutors, we use rubric-based student judgments to produce a range of tutor performance scores, identifying both strong and weak tutors. Using the training section of the ScienceQA dataset, we then construct a data set of pairwise comparisons between the outputs of strong and weak tutors. This enables us to apply multiple preference optimization methods to fine-tune an underperforming tutor model (Qwen2-VL-2B) into more effective ones. Our results also show that strong problem-solving skills do not guarantee high-quality tutoring and that performance optimization-guided refinements can yield more educationally aligned tutor models. This approach opens avenues for building MLLMs that serve not only as problem solvers, but as genuinely helpful educational assistants.

[Arxiv](https://arxiv.org/abs/2505.06418)