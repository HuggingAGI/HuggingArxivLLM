# Time-R1：探索LLMs的全面时间推理能力

发布时间：2025年05月16日

`LLM应用` `人工智能` `数据分析`

> Time-R1: Towards Comprehensive Temporal Reasoning in LLMs

# 摘要

> 大型语言模型 (LLMs) 虽然能力出众，但在时间推理方面仍显不足，难以将过去推理与未来预测和生成有效结合。现有方法多专注于单一时间技能，如历史事件问答或基础预测，且泛化能力较弱，尤其在处理知识范围外的事件或需要创造性预见时表现不佳。为此，我们推出 	extit{Time-R1}，首个赋予中型 LLM（30亿参数）全面时间能力的框架：理解、预测与创造性生成。

我们的方法采用三阶段发展路径，前两阶段构成强化学习 (RL) 课程，由精心设计的动态规则奖励系统驱动。该框架逐步构建：(1) 基于历史数据的时间理解与事件时间逻辑映射，(2) 预测超出知识范围的未来事件能力，最终 (3) 实现无需微调的创造性未来场景生成泛化能力。

实验结果惊人，Time-R1 在未来事件预测和创造性场景生成基准测试中，超越了包括6710亿参数最新 DeepSeek-R1 在内的大200倍模型。这表明，精心设计的逐步强化学习微调使小型高效模型在时间推理上表现更优，为实现真正时间感知 AI 提供了实际可行的路径。

为推动研究，我们发布了 	extit{Time-Bench}，一个基于十年新闻数据的大型多任务时间推理数据集，以及 	extit{Time-R1} 检查点系列。

> Large Language Models (LLMs) demonstrate impressive capabilities but lack robust temporal intelligence, struggling to integrate reasoning about the past with predictions and plausible generations of the future. Meanwhile, existing methods typically target isolated temporal skills, such as question answering about past events or basic forecasting, and exhibit poor generalization, particularly when dealing with events beyond their knowledge cutoff or requiring creative foresight. To address these limitations, we introduce \textit{Time-R1}, the first framework to endow a moderate-sized (3B-parameter) LLM with comprehensive temporal abilities: understanding, prediction, and creative generation. Our approach features a novel three-stage development path; the first two constitute a \textit{reinforcement learning (RL) curriculum} driven by a meticulously designed dynamic rule-based reward system. This framework progressively builds (1) foundational temporal understanding and logical event-time mappings from historical data, (2) future event prediction skills for events beyond its knowledge cutoff, and finally (3) enables remarkable generalization to creative future scenario generation without any fine-tuning. Strikingly, experiments demonstrate that Time-R1 outperforms models over 200 times larger, including the state-of-the-art 671B DeepSeek-R1, on highly challenging future event prediction and creative scenario generation benchmarks. This work provides strong evidence that thoughtfully engineered, progressive RL fine-tuning allows smaller, efficient models to achieve superior temporal performance, offering a practical and scalable path towards truly time-aware AI. To foster further research, we also release \textit{Time-Bench}, a large-scale multi-task temporal reasoning dataset derived from 10 years of news data, and our series of \textit{Time-R1} checkpoints.

[Arxiv](https://arxiv.org/abs/2505.13508)