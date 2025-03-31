# 突破传统微调：多阶段、多语言与领域定制方法助力低资源机器翻译

发布时间：2025年03月28日

`LLM应用` `机器翻译`

> Beyond Vanilla Fine-Tuning: Leveraging Multistage, Multilingual, and Domain-Specific Methods for Low-Resource Machine Translation

# 摘要

> 微调多语言序列到序列大型语言模型（msLLMs）在开发低资源语言（LRLs）的神经机器翻译（NMT）系统方面展现出潜力。然而，传统的单阶段微调方法在极低资源的NMT设置下效果不佳，因为训练数据非常有限。本文提出两种方法，用于在这些具有挑战性的场景中适应msLLMs：（1）持续预训练（CPT），通过特定领域的单语数据进一步训练msLLM，弥补LRLs的代表性不足；（2）中间任务迁移学习（ITTL），通过同时使用领域内和领域外的平行数据微调msLLM，增强其在各种领域和任务中的翻译能力。这些方法被应用于僧加罗语、泰米尔语和英语（六种语言对）的NMT系统，在特定领域的、极低资源设置（数据集包含少于100,000个样本）下运行。实验结果表明，与标准的单阶段微调基线相比，这些方法在所有翻译方向上平均提高了+1.47的双语评估 understudy（BLEU）分数。此外，多模型集成进一步提升了性能，增加了BLEU分数。

> Fine-tuning multilingual sequence-to-sequence large language models (msLLMs) has shown promise in developing neural machine translation (NMT) systems for low-resource languages (LRLs). However, conventional single-stage fine-tuning methods struggle in extremely low-resource NMT settings, where training data is very limited. This paper contributes to artificial intelligence by proposing two approaches for adapting msLLMs in these challenging scenarios: (1) continual pre-training (CPT), where the msLLM is further trained with domain-specific monolingual data to compensate for the under-representation of LRLs, and (2) intermediate task transfer learning (ITTL), a method that fine-tunes the msLLM with both in-domain and out-of-domain parallel data to enhance its translation capabilities across various domains and tasks. As an application in engineering, these methods are implemented in NMT systems for Sinhala, Tamil, and English (six language pairs) in domain-specific, extremely low-resource settings (datasets containing fewer than 100,000 samples). Our experiments reveal that these approaches enhance translation performance by an average of +1.47 bilingual evaluation understudy (BLEU) score compared to the standard single-stage fine-tuning baseline across all translation directions. Additionally, a multi-model ensemble further improves performance by an additional BLEU score.

[Arxiv](https://arxiv.org/abs/2503.22582)