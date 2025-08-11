# # 基于增强攻击性的提示进行网络欺凌检测

发布时间：2025年08月08日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型应用于网络欺凌检测，并通过整合辅助任务（攻击检测）来提升模型的泛化能力和检测效果。研究者在实验中使用了多种微调策略，并提出了一种增强提示的管道方法，这些都属于LLM的具体应用和优化。因此，这篇论文应归类为LLM应用。` `社交媒体安全` `网络欺凌检测`

> Cyberbullying Detection via Aggression-Enhanced Prompting

# 摘要

> 社交媒体上的网络欺凌检测是一个复杂而关键的挑战，因其表现形式多样且隐晦。本研究探索了将攻击检测巧妙地整合为辅助任务，能否提升大型语言模型（LLMs）在这一领域的泛化能力和检测效果。通过指令微调的LLMs，我们在五个攻击数据集和一个网络欺凌数据集上进行了深入实验，并评估了零样本、少样本、独立的LoRA微调和多任务学习（MTL）等多种策略。鉴于MTL结果的不稳定性，我们创新性地提出了一种增强提示的管道方法，将攻击预测嵌入到网络欺凌检测的提示中，从而实现上下文的增强。初步结果表明，这种增强提示管道在标准LoRA微调中表现更为出色，充分证明了基于攻击信息的上下文能够显著提升网络欺凌检测的效果。本研究有力地证明了，通过引入辅助任务（如攻击检测），可以有效增强LLMs在社交网络关键安全应用中的泛化能力。

> Detecting cyberbullying on social media remains a critical challenge due to its subtle and varied expressions. This study investigates whether integrating aggression detection as an auxiliary task within a unified training framework can enhance the generalisation and performance of large language models (LLMs) in cyberbullying detection. Experiments are conducted on five aggression datasets and one cyberbullying dataset using instruction-tuned LLMs. We evaluated multiple strategies: zero-shot, few-shot, independent LoRA fine-tuning, and multi-task learning (MTL). Given the inconsistent results of MTL, we propose an enriched prompt pipeline approach in which aggression predictions are embedded into cyberbullying detection prompts to provide contextual augmentation. Preliminary results show that the enriched prompt pipeline consistently outperforms standard LoRA fine-tuning, indicating that aggression-informed context significantly boosts cyberbullying detection. This study highlights the potential of auxiliary tasks, such as aggression detection, to improve the generalisation of LLMs for safety-critical applications on social networks.

[Arxiv](https://arxiv.org/abs/2508.06360)