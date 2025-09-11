# 使用LLMs生成有毒文本的经验教训

发布时间：2025年09月10日

`LLM应用` `媒体与娱乐`

> <think> So let's replace this phrase with insult... </think> Lessons learned from generation of toxic texts with LLMs

# 摘要

> 现代大型语言模型（LLMs）在合成数据生成方面表现卓越。然而，在文本去毒这类敏感领域，其性能表现尚未引起科学界的足够重视。本文尝试将LLM生成的合成有毒数据作为人类生成数据的替代品，用于训练去毒模型。研究中，我们借助Llama 3与Qwen激活修补模型，针对ParaDetox和SST-2数据集的中性文本，生成了对应的合成有毒文本。实验结果显示，基于合成数据微调的模型性能始终不及人类数据训练的模型，联合指标降幅最高达30%。其根源在于严重的词汇多样性不足：LLM生成有毒内容时，仅依赖少量重复的侮辱性词汇，无法捕捉人类毒性表达的细微差别与丰富多样性。这些发现揭示了当前LLM在该领域的局限性，同时也凸显了多样化的人类标注数据对构建稳健去毒系统的持续重要性。

> Modern Large Language Models (LLMs) are excellent at generating synthetic data. However, their performance in sensitive domains such as text detoxification has not received proper attention from the scientific community. This paper explores the possibility of using LLM-generated synthetic toxic data as an alternative to human-generated data for training models for detoxification. Using Llama 3 and Qwen activation-patched models, we generated synthetic toxic counterparts for neutral texts from ParaDetox and SST-2 datasets. Our experiments show that models fine-tuned on synthetic data consistently perform worse than those trained on human data, with a drop in performance of up to 30% in joint metrics. The root cause is identified as a critical lexical diversity gap: LLMs generate toxic content using a small, repetitive vocabulary of insults that fails to capture the nuances and variety of human toxicity. These findings highlight the limitations of current LLMs in this domain and emphasize the continued importance of diverse, human-annotated data for building robust detoxification systems.

[Arxiv](https://arxiv.org/abs/2509.08358)