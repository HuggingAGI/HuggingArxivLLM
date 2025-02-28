# Med-RLVR：借助强化学习，从30亿参数基础模型中实现医学推理能力的突破

发布时间：2025年02月26日

`LLM应用` `问答系统`

> Med-RLVR: Emerging Medical Reasoning from a 3B base model via reinforcement Learning

# 摘要

> 基于可验证奖励的强化学习（RLVR）因其无需显式推理监督即可激发基础语言模型自我演进推理能力的特点而备受关注。DeepSeek-R1的研究即为此提供了有力证明。尽管先前关于RLVR的研究主要集中在数学和编程领域，但其在其他任务和领域的适用性尚未得到充分探索。本研究旨在探究RLVR是否能够实现医学推理能力的涌现。我们提出了Med-RLVR，这是将RLVR应用于医学领域的初步尝试，利用医学多选题（Medical Multiple-Choice Question Answering, MCQA）数据作为可验证标签。实验结果表明，RLVR不仅在数学和编程领域表现优异，而且成功扩展至医学问答领域。值得注意的是，Med-RLVR在分布内任务上的表现可与传统监督微调（SFT）相媲美，同时在分布外泛化能力方面实现了8个百分点的显著提升。进一步的训练动态分析表明，即使没有显式的推理监督，推理能力也能从3B参数的基础模型中自然涌现。这些发现凸显了RLVR在数学和编程以外领域的潜力，为该技术在医学等知识密集型领域的应用开辟了新的可能性。


> Reinforcement learning from verifiable rewards (RLVR) has recently gained attention for its ability to elicit self-evolved reasoning capabilitie from base language models without explicit reasoning supervisions, as demonstrated by DeepSeek-R1. While prior work on RLVR has primarily focused on mathematical and coding domains, its applicability to other tasks and domains remains unexplored. In this work, we investigate whether medical reasoning can emerge from RLVR. We introduce Med-RLVR as an initial study of RLVR in the medical domain leveraging medical multiple-choice question answering (MCQA) data as verifiable labels. Our results demonstrate that RLVR is not only effective for math and coding but also extends successfully to medical question answering. Notably, Med-RLVR achieves performance comparable to traditional supervised fine-tuning (SFT) on in-distribution tasks while significantly improving out-of-distribution generalization, with an 8-point accuracy gain. Further analysis of training dynamics reveals that, with no explicit reasoning supervision, reasoning emerges from the 3B-parameter base model. These findings underscore the potential of RLVR in domains beyond math and coding, opening new avenues for its application in knowledge-intensive fields such as medicine.

[Arxiv](https://arxiv.org/abs/2502.19655)