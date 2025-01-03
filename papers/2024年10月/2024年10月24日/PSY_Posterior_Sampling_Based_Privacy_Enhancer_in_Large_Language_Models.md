# PSY: 大型语言模型中的后验采样隐私增强器

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了在大型语言模型（LLMs）中应用隐私增强技术，特别是通过LoRA（Low-Rank Adaptation）微调LLMs来防止隐私泄露。论文提出的PSY方案是一种应用于LLMs的隐私增强方法，旨在保护数据所有者的隐私。因此，这篇论文属于LLM应用类别，因为它涉及如何在实际应用中增强LLMs的隐私保护能力。` `隐私保护` `机器学习`

> PSY: Posterior Sampling Based Privacy Enhancer in Large Language Models

# 摘要

> # 摘要
LLMs中的隐私漏洞（如记忆泄露）屡见不鲜，各种缓解方案也应运而生。LoRA常用于微调LLMs，是嵌入隐私增强模块的理想选择。在这项研究中，我们推出了PSY——一种基于后验采样的隐私增强器，适用于LoRA。我们通过后验采样实现了一个简单而高效的PSY方案，有效防止了中间信息的隐私泄露，从而保护了数据所有者的隐私。我们测试了扩展PSY的LoRA，对抗最新的成员推断和数据提取攻击。实验在三个不同LLM架构上进行，这些架构使用LoRA在三个数据集上进行了微调。与常用的差分隐私方法相比，我们的方案显著降低了攻击成功率，且对模型微调和最终性能几乎没有影响。最重要的是，PSY为通过潜在空间扩展增强隐私开辟了一条新路径。

> Privacy vulnerabilities in LLMs, such as leakage from memorization, have been constantly identified, and various mitigation proposals have been proposed. LoRA is usually used in fine-tuning LLMs and a good entry point to insert privacy-enhancing modules. In this ongoing research, we introduce PSY, a Posterior Sampling based PrivacY enhancer that can be used in LoRA. We propose a simple yet effective realization of PSY using posterior sampling, which effectively prevents privacy leakage from intermediate information and, in turn, preserves the privacy of data owners. We evaluate LoRA extended with PSY against state-of-the-art membership inference and data extraction attacks. The experiments are executed on three different LLM architectures fine-tuned on three datasets with LoRA. In contrast to the commonly used differential privacy method, we find that our proposed modification consistently reduces the attack success rate. Meanwhile, our method has almost no negative impact on model fine-tuning or final performance. Most importantly, PSY reveals a promising path toward privacy enhancement with latent space extensions.

[Arxiv](https://arxiv.org/abs/2410.18824)