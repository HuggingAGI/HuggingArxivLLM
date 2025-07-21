# PRIDE——LLMs中参数高效的公平性身份歧视减少方法

发布时间：2025年07月18日

`LLM应用` `社会公平`

> PRIDE -- Parameter-Efficient Reduction of Identity Discrimination for Equality in LLMs

# 摘要

> 大型语言模型（LLMs）常常会复制训练数据中的性别和性取向偏见，导致边缘化LGBTQIA+用户。因此，减少这类偏见至关重要。我们评估了两种参数高效的微调（PEFT）技术——低秩适配（LoRA）和软提示微调——作为替代全模型微调的轻量化方案，以缓解此类偏见。通过WinoQueer基准测试，我们量化了三个开源LLMs中的偏见，并观察到基线偏见评分在涵盖不同性别和/或性取向的酷儿身份范围内达到98分（满分100分），其中50分表示中立。在经过精心挑选的QueerNews语料库上使用LoRA（新增参数不到0.1%）进行微调，使偏见评分降低了多达50分，并将中立性从几乎0%提升至最高36%。软提示微调（10个虚拟令牌）仅带来微乎其微的改进。这些发现表明，LoRA能够在计算开销极小的情况下实现有意义的公平提升。我们主张更广泛地采用基于社区反馈的PEFT方法，创建更大规模的酷儿作者语料库，并开发超越WinoQueer的更丰富的评估套件，同时进行持续的审核，以确保LLMs的包容性。

> Large Language Models (LLMs) frequently reproduce the gender- and sexual-identity prejudices embedded in their training corpora, leading to outputs that marginalize LGBTQIA+ users. Hence, reducing such biases is of great importance. To achieve this, we evaluate two parameter-efficient fine-tuning (PEFT) techniques - Low-Rank Adaptation (LoRA) and soft-prompt tuning - as lightweight alternatives to full-model fine-tuning for mitigating such biases. Using the WinoQueer benchmark, we quantify bias in three open-source LLMs and observe baseline bias scores reaching up to 98 (out of 100) across a range of queer identities defined by gender and/or sexual orientation, where 50 would indicate neutrality. Fine-tuning with LoRA (< 0.1% additional parameters) on a curated QueerNews corpus reduces those scores by up to 50 points and raises neutrality from virtually 0% to as much as 36%. Soft-prompt tuning (10 virtual tokens) delivers only marginal improvements. These findings show that LoRA can deliver meaningful fairness gains with minimal computation. We advocate broader adoption of community-informed PEFT, the creation of larger queer-authored corpora, and richer evaluation suites beyond WinoQueer, coupled with ongoing audits to keep LLMs inclusive.

[Arxiv](https://arxiv.org/abs/2507.13743)