# 较弱的大型语言模型（LLM）的意见同样值得关注：多角度意见融合助力提升数学推理能力

发布时间：2025年02月26日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在数学推理能力方面的进展，并提出了一种后训练方法来提升模型的推理性能。论文主要关注模型本身的改进和优化，属于模型理论的范畴，因此归类为LLM理论。` `人工智能`

> Weaker LLMs' Opinions Also Matter: Mixture of Opinions Enhances LLM's Mathematical Reasoning

# 摘要

> 近期大型语言模型（LLMs）的进展激发了对其数学推理能力的兴趣。尽管像GPT-4这样的闭源模型在数学基准测试中表现优异，但小型开源模型的推理能力仍有待验证。为解决这一问题，我们提出了一种后训练方法，通过整合较弱辅助模型的推理结果，提升主模型的推理性能。具体而言，每个训练样本都附加了详细推理步骤和多种答案，帮助模型学习多样化的思考方式。实验结果表明，这种方法在数学推理任务中比传统方法平均提升了5%的准确率，证明了多角度推理的重要性。

> Recent advances in Large Language Models (LLMs) have raised interest in their formal reasoning capabilities, particularly in mathematics. While closed LLMs like GPT-4 perform well on mathematical benchmarks, e.g., GSM8K, it remains unclear whether small to medium-sized open LLMs can achieve similar performance, questioning their reliability. To close this gap, we propose a post-training approach leveraging a mixture of opinions (MoO) from weaker ancillary LLMs to enhance a (relatively) stronger LLM's reasoning. For that, each post-training sample is augmented with Chain-of-Thought (CoT) reasoning steps and answers from ancillary LLMs, enabling the main LLM to learn from diverse perspectives. We compare MoO with standard supervised fine-tuning (SFT), few-shot prompting, and the Mixture of Agents (MoA) method on mathematical reasoning benchmarks. Our results show that incorporating weaker LLMs' opinions improves mathematical reasoning by an average of 5%, highlighting the value of diverse perspectives in reasoning tasks.

[Arxiv](https://arxiv.org/abs/2502.19622)