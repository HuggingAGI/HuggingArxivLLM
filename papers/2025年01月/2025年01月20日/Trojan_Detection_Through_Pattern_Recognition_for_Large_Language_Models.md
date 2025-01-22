# 基于模式识别的大型语言模型木马检测

发布时间：2025年01月20日

`LLM理论

理由：这篇论文主要讨论了在大型语言模型（LLM）中检测特洛伊木马触发器的方法，涉及到模型的预训练、微调和上下文学习等阶段。研究提出了一个多阶段框架，包括令牌过滤、触发器识别和触发器验证，并探讨了现有方法的改进。这些内容主要关注LLM的内部机制和安全性问题，属于对LLM的理论研究和改进，因此分类为“LLM理论”。` `网络安全` `人工智能`

> Trojan Detection Through Pattern Recognition for Large Language Models

# 摘要

> # 摘要
特洛伊木马后门可在LLM的预训练、微调和上下文学习等阶段被注入，严重威胁模型的对齐。由于因果语言建模的特性，在庞大的搜索空间中检测这些触发器极具挑战。本研究提出了一种多阶段框架，用于检测LLM中的特洛伊木马触发器，包括令牌过滤、触发器识别和触发器验证。我们探讨了现有触发器识别方法，并提出了两种基于输出logits的黑盒触发器反演方法变体，分别采用束搜索和贪婪解码。验证阶段至关重要，我们通过语义保留提示和特殊扰动，有效区分了实际特洛伊木马触发器与其他类似特征的对抗性字符串。在TrojAI和RLHF中毒模型数据集上的评估结果验证了该方法的有效性。

> Trojan backdoors can be injected into large language models at various stages, including pretraining, fine-tuning, and in-context learning, posing a significant threat to the model's alignment. Due to the nature of causal language modeling, detecting these triggers is challenging given the vast search space. In this study, we propose a multistage framework for detecting Trojan triggers in large language models consisting of token filtration, trigger identification, and trigger verification. We discuss existing trigger identification methods and propose two variants of a black-box trigger inversion method that rely on output logits, utilizing beam search and greedy decoding respectively. We show that the verification stage is critical in the process and propose semantic-preserving prompts and special perturbations to differentiate between actual Trojan triggers and other adversarial strings that display similar characteristics. The evaluation of our approach on the TrojAI and RLHF poisoned model datasets demonstrates promising results.

[Arxiv](https://arxiv.org/abs/2501.11621)