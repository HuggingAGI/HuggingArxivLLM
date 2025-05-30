# VAU-R1：利用强化微调提升视频异常理解能力

发布时间：2025年05月29日

`LLM应用` `智慧城市` `安全监控`

> VAU-R1: Advancing Video Anomaly Understanding via Reinforcement Fine-Tuning

# 摘要

> 视频异常理解（VAU）在智慧城市、安全监控和灾害预警系统等场景中发挥着关键作用，但因其对时空感知的精准要求和模糊情境下的稳健推理需求，这一任务仍具挑战性。尽管异常检测技术不断进步，现有方法却常因缺乏可解释性而难以捕捉异常事件中的因果关系和情境信息。加之缺乏全面的异常推理能力评估基准，这一问题更加凸显。为应对这些挑战，我们推出了VAU-R1——一个基于多模态大型语言模型（MLLMs）的数据高效框架，通过强化微调（RFT）提升异常推理能力。同时，我们开发了VAU-Bench——首个专注于视频异常推理的Chain-of-Thought基准测试，包含多选问答、详尽推理、时间标注和描述性字幕。实验证明，VAU-R1在问答准确度、时间定位和推理连贯性等多方面均有显著提升。我们的方法和基准测试共同为视频异常理解的可解释性和推理能力奠定了坚实基础。代码已开源，访问https://github.com/GVCLab/VAU-R1即可获取。

> Video Anomaly Understanding (VAU) is essential for applications such as smart cities, security surveillance, and disaster alert systems, yet remains challenging due to its demand for fine-grained spatio-temporal perception and robust reasoning under ambiguity. Despite advances in anomaly detection, existing methods often lack interpretability and struggle to capture the causal and contextual aspects of abnormal events. This limitation is further compounded by the absence of comprehensive benchmarks for evaluating reasoning ability in anomaly scenarios. To address both challenges, we introduce VAU-R1, a data-efficient framework built upon Multimodal Large Language Models (MLLMs), which enhances anomaly reasoning through Reinforcement Fine-Tuning (RFT). Besides, we propose VAU-Bench, the first Chain-of-Thought benchmark tailored for video anomaly reasoning, featuring multiple-choice QA, detailed rationales, temporal annotations, and descriptive captions. Empirical results show that VAU-R1 significantly improves question answering accuracy, temporal grounding, and reasoning coherence across diverse contexts. Together, our method and benchmark establish a strong foundation for interpretable and reasoning-aware video anomaly understanding. Our code is available at https://github.com/GVCLab/VAU-R1.

[Arxiv](https://arxiv.org/abs/2505.23504)