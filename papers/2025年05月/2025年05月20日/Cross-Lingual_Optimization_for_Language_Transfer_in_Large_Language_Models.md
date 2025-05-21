# 大型语言模型中的跨语言优化与语言迁移研究

发布时间：2025年05月20日

`LLM应用` `多语言处理`

> Cross-Lingual Optimization for Language Transfer in Large Language Models

# 摘要

> 将大型语言模型适应其他语言通常采用监督微调（SFT）作为标准方法。然而，这种方法常常过于侧重英语表现，这一现象在数据受限的环境中尤为明显。为了解决这些挑战，我们提出	extbf{跨语言优化（CLO）}，它能够在保持英语能力的同时，高效地将英语中心的LLM迁移到目标语言。CLO利用公开的英语SFT数据和一个翻译模型来实现跨语言迁移。我们在六种资源水平各异的语言上使用五种模型进行了实验。我们的结果显示，CLO在掌握目标语言能力和保持英语性能方面都优于SFT。值得注意的是，在低资源语言中，仅使用3,200个样本的CLO就超过了使用6,400个样本的SFT，证明CLO能够以更少的数据实现更优的性能。此外，我们发现SFT在中低资源语言中对数据量特别敏感，而CLO则保持了较强的稳定性。我们的全面分析强调了SFT的局限性，并在CLO中加入了额外的训练策略以提高效率。

> Adapting large language models to other languages typically employs supervised fine-tuning (SFT) as a standard approach. However, it often suffers from an overemphasis on English performance, a phenomenon that is especially pronounced in data-constrained environments. To overcome these challenges, we propose \textbf{Cross-Lingual Optimization (CLO)} that efficiently transfers an English-centric LLM to a target language while preserving its English capabilities. CLO utilizes publicly available English SFT data and a translation model to enable cross-lingual transfer. We conduct experiments using five models on six languages, each possessing varying levels of resource. Our results show that CLO consistently outperforms SFT in both acquiring target language proficiency and maintaining English performance. Remarkably, in low-resource languages, CLO with only 3,200 samples surpasses SFT with 6,400 samples, demonstrating that CLO can achieve better performance with less data. Furthermore, we find that SFT is particularly sensitive to data quantity in medium and low-resource languages, whereas CLO remains robust. Our comprehensive analysis emphasizes the limitations of SFT and incorporates additional training strategies in CLO to enhance efficiency.

[Arxiv](https://arxiv.org/abs/2505.14297)