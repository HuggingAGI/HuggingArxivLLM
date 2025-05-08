# OBLIVIATE：强健且实用的大型语言模型机器遗忘方法

发布时间：2025年05月07日

`LLM应用

论文摘要：在大规模语料库上训练的大型语言模型 (LLMs) 可能会记住敏感、受版权保护或有害内容。为解决这一问题，我们提出了 OBLIVIATE，一个强大的遗忘框架，可以在移除特定数据的同时保持模型效用。该框架采用结构化的三步流程：提取目标令牌、构建保留集，并使用包含遮罩、蒸馏和世界事实三个组件的定制损失函数进行微调。通过低秩适配器 (LoRA)，它在保证高效性的同时，不妥协遗忘质量。我们在《哈利·波特》系列、WMDP 和 TOFU 等多个数据集上进行了实验，采用全面的评估指标：遗忘质量（新文档级别记忆分数）、模型效用和流畅度。实验结果表明，该框架在抵御成员推断攻击、最小化对保留数据的影响以及在各种场景中保持鲁棒性方面表现优异。

LLM应用` `数据安全` `隐私保护`

> OBLIVIATE: Robust and Practical Machine Unlearning for Large Language Models

# 摘要

> 在大规模语料库上训练的大型语言模型 (LLMs) 可能会记住敏感、受版权保护或有害内容。为解决这一问题，我们提出了 OBLIVIATE，一个强大的遗忘框架，可以在移除特定数据的同时保持模型效用。该框架采用结构化的三步流程：提取目标令牌、构建保留集，并使用包含遮罩、蒸馏和世界事实三个组件的定制损失函数进行微调。通过低秩适配器 (LoRA)，它在保证高效性的同时，不妥协遗忘质量。我们在《哈利·波特》系列、WMDP 和 TOFU 等多个数据集上进行了实验，采用全面的评估指标：遗忘质量（新文档级别记忆分数）、模型效用和流畅度。实验结果表明，该框架在抵御成员推断攻击、最小化对保留数据的影响以及在各种场景中保持鲁棒性方面表现优异。

> Large language models (LLMs) trained over extensive corpora risk memorizing sensitive, copyrighted, or toxic content. To address this, we propose OBLIVIATE, a robust unlearning framework that removes targeted data while preserving model utility. The framework follows a structured process: extracting target tokens, building retain sets, and fine-tuning with a tailored loss function comprising three components -- masking, distillation, and world fact. Using low-rank adapters (LoRA), it ensures efficiency without compromising unlearning quality. We conduct experiments on multiple datasets, including the Harry Potter series, WMDP, and TOFU, using a comprehensive suite of metrics: forget quality (new document-level memorization score), model utility, and fluency. Results demonstrate its effectiveness in resisting membership inference attacks, minimizing the impact on retained data, and maintaining robustness across diverse scenarios.

[Arxiv](https://arxiv.org/abs/2505.04416)