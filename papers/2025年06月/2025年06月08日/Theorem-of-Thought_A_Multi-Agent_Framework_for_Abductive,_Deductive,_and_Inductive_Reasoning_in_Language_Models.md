# 思想定理：一个多智能体框架，用于语言模型中的溯因、演绎与归纳推理

发布时间：2025年06月08日

`LLM理论` `自然语言推理` `认知推理`

> Theorem-of-Thought: A Multi-Agent Framework for Abductive, Deductive, and Inductive Reasoning in Language Models

# 摘要

> 大型语言模型（LLMs）在自然语言推理任务中表现强劲，但其推理过程仍显脆弱且难以解释。思维链（CoT）等提示技术通过提取中间推理步骤或聚合多个输出来增强可靠性，但缺乏机制来强制逻辑结构并评估内部连贯性。我们引入了思维定理（ToTh），一个将推理建模为三个并行代理协作的新型框架，每个代理分别模拟 abduction、deduction 和 induction 三种推理模式。每个代理生成推理轨迹，并将其结构化为正式的推理图谱。我们采用基于自然语言推理（NLI）的贝叶斯信念传播评估一致性，为每一步骤分配置信度得分。最终选择连贯性最高的图谱来得出答案。在符号推理（WebOfLies）和数值推理（MultiArith）基准测试中，ToTh 在多个 LLM 上始终优于 CoT、Self-Consistency 和 CoT-Decoding，同时生成可解释且逻辑严谨的推理链。我们的研究结果为构建更稳健且认知启发的 LLM 推理指明了方向。实现代码可在 https://github.com/KurbanIntelligenceLab/theorem-of-thought 获取。


> Large language models (LLMs) have shown strong performance across natural language reasoning tasks, yet their reasoning processes remain brittle and difficult to interpret. Prompting techniques like Chain-of-Thought (CoT) enhance reliability by eliciting intermediate reasoning steps or aggregating multiple outputs. However, they lack mechanisms for enforcing logical structure and assessing internal coherence. We introduce Theorem-of-Thought (ToTh), a novel framework that models reasoning as collaboration among three parallel agents, each simulating a distinct mode of inference: abductive, deductive, and inductive. Each agent produces a reasoning trace, which is structured into a formal reasoning graph. To evaluate consistency, we apply Bayesian belief propagation guided by natural language inference (NLI), assigning confidence scores to each step. The most coherent graph is selected to derive the final answer. Experiments on symbolic (WebOfLies) and numerical (MultiArith) reasoning benchmarks show that ToTh consistently outperforms CoT, Self-Consistency, and CoT-Decoding across multiple LLMs, while producing interpretable and logically grounded reasoning chains. Our findings suggest a promising direction for building more robust and cognitively inspired LLM reasoning. The implementation is available at https://github.com/KurbanIntelligenceLab/theorem-of-thought.

[Arxiv](https://arxiv.org/abs/2506.07106)