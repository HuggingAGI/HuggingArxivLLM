# 多语言数学推理：促进印地语和英语的开源 LLMs 发展

发布时间：2024年12月24日

`LLM应用` `语言模型`

> Multilingual Mathematical Reasoning: Advancing Open-Source LLMs in Hindi and English

# 摘要

> 大型语言模型（LLMs）于语言任务中表现出众，然而在数学推理方面却颇为吃力，尤其在像印地语这类非英语语言里。本研究致力于增强印地语和英语中规模较小、资源利用高效的开源 LLMs 的数学推理能力。我们运用零样本、少样本思维链（CoT）方法以及监督微调，对 OpenHathi 7B、LLaMA-2 7B、WizardMath 7B、Mistral 7B、LLeMMa 7B、MAmmoTH 7B、Gemini Pro 和 GPT-4 等模型进行评估。我们的方法融入了课程学习，逐步在难度渐增的问题上训练模型，采用了新颖的分解策略以简化复杂算术运算，还有将解决方案划分为阶段的结构化解决方案设计。我们的实验带来了显著的性能提升。WizardMath 7B 在英语数据集上的准确率比 Gemini 高 6%，在印地语数据集上与 Gemini 表现持平。采用结合英语和印地语样本的双语方式，所获结果可与单个语言模型媲美，展现出在两种语言中学习数学推理的能力。本研究凸显了提升开源 LLMs 数学推理能力的潜力。

> Large Language Models (LLMs) excel in linguistic tasks but struggle with mathematical reasoning, particularly in non English languages like Hindi. This research aims to enhance the mathematical reasoning skills of smaller, resource efficient open-source LLMs in both Hindi and English. We evaluate models like OpenHathi 7B, LLaMA-2 7B, WizardMath 7B, Mistral 7B, LLeMMa 7B, MAmmoTH 7B, Gemini Pro, and GPT-4 using zero-shot, few-shot chain-of-thought (CoT) methods, and supervised fine-tuning. Our approach incorporates curriculum learning, progressively training models on increasingly difficult problems, a novel Decomposition Strategy to simplify complex arithmetic operations, and a Structured Solution Design that divides solutions into phases. Our experiments result in notable performance enhancements. WizardMath 7B exceeds Gemini's accuracy on English datasets by +6% and matches Gemini's performance on Hindi datasets. Adopting a bilingual approach that combines English and Hindi samples achieves results comparable to individual language models, demonstrating the capability to learn mathematical reasoning in both languages. This research highlights the potential for improving mathematical reasoning in open-source LLMs.

[Arxiv](https://arxiv.org/abs/2412.18415)