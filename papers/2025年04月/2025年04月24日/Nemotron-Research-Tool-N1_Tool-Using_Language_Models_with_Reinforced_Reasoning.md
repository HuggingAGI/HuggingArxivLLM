# # Nemotron-Research-Tool-N1: 具备工具增强推理能力的语言模型工具

发布时间：2025年04月24日

`LLM理论` `文本生成`

> Nemotron-Research-Tool-N1: Tool-Using Language Models with Reinforced Reasoning

# 摘要

> 为大型语言模型赋予外部工具能力已成为突破文本生成任务限制的关键策略。此前研究主要通过监督微调（SFT）强制工具调用的正确性，或从更强模型中提取推理轨迹用于SFT来增强工具使用能力。然而，这两种方法均有不足：前者完全省略推理过程，后者则产生限制泛化的模仿推理。受DeepSeek-R1通过基于规则的强化学习成功激发推理的启发，我们采用类似训练范式，开发了Nemotron-Research-Tool-N1系列工具使用语言模型。与从更强模型中严格监督蒸馏中间推理轨迹的方法不同，Nemotron-Research-Tool-N1通过评估工具调用的结构有效性和功能性正确性的二元奖励机制进行优化。这种轻量级监督使模型能够自主内化推理策略，无需依赖标注推理轨迹。在BFCL和API-Bank基准测试中，基于Qwen-2.5-7B/14B-Instruct构建的Nemotron-Research-Tool-N1-7B和Nemotron-Research-Tool-N1-14B实现了最先进结果，在两项评估中均超越GPT-4o。

> Enabling large language models with external tools has become a pivotal strategy for extending their functionality beyond text generation tasks. Prior work typically enhances tool-use abilities by either applying supervised fine-tuning (SFT) to enforce tool-call correctness or distilling reasoning traces from stronger models for SFT. However, both approaches fall short, either omitting reasoning entirely or producing imitative reasoning that limits generalization. Inspired by the success of DeepSeek-R1 in eliciting reasoning through rule-based reinforcement learning, we develop the Nemotron-Research-Tool-N1 series of tool-using language models using a similar training paradigm. Instead of restrictively supervising intermediate reasoning traces distilled from stronger models, Nemotron-Research-Tool-N1 is optimized with a binary reward that evaluates only the structural validity and functional correctness of tool invocations. This lightweight supervision allows the model to autonomously internalize reasoning strategies, without the need for annotated reasoning trajectories. Experiments on the BFCL and API-Bank benchmarks show that Nemotron-Research-Tool-N1-7B and Nemotron-Research-Tool-N1-14B, built on Qwen-2.5-7B/14B-Instruct, achieve state-of-the-art results, outperforming GPT-4o on both evaluations.

[Arxiv](https://arxiv.org/abs/2505.00024)