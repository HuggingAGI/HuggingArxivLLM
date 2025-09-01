# 强化学习微调大型语言模型：隐私保护合成重写

发布时间：2025年08月25日

`强化学习` `基础理论`

> RL-Finetuned LLMs for Privacy-Preserving Synthetic Rewriting

# 摘要

> 现代机器学习系统的性能依赖于大型高质量数据集的获取，这些数据常来自用户生成内容或专有领域语料库。然而，这些海量数据本身蕴含敏感个人信息，引发了对隐私保护、数据安全及合规性的高度关注。尽管传统匿名化技术能去除显式标识，但这可能会降低下游机器学习任务的性能。更关键的是，简单匿名化难以抵御利用写作风格、主题倾向或人口统计学特征等隐式信号的推理攻击，这凸显了模型训练中亟需更可靠的隐私保护机制。为解决用户隐私与数据效用的平衡难题，我们提出一种强化学习框架，通过复合奖励函数微调大型语言模型（LLM），联合优化显式/隐式隐私、语义保真度及输出多样性。为有效捕捉群体层面的规律，隐私奖励融合了语义线索与基于潜在表示的最小生成树（MST）导出的结构模式。该方法通过在分布层面建模这些隐私敏感信号，引导模型生成合成改写文本，在保护隐私的同时保留数据效用。实证结果显示，该方法在不降低语义质量的前提下，显著提升了作者匿名性和隐私指标，为大语言模型时代的隐私保护数据生成提供了可扩展、模型无关的解决方案。

> The performance of modern machine learning systems depends on access to large, high-quality datasets, often sourced from user-generated content or proprietary, domain-specific corpora. However, these rich datasets inherently contain sensitive personal information, raising significant concerns about privacy, data security, and compliance with regulatory frameworks. While conventional anonymization techniques can remove explicit identifiers, such removal may result in performance drop in downstream machine learning tasks. More importantly, simple anonymization may not be effective against inference attacks that exploit implicit signals such as writing style, topical focus, or demographic cues, highlighting the need for more robust privacy safeguards during model training. To address the challenging issue of balancing user privacy and data utility, we propose a reinforcement learning framework that fine-tunes a large language model (LLM) using a composite reward function that jointly optimizes for explicit and implicit privacy, semantic fidelity, and output diversity. To effectively capture population level regularities, the privacy reward combines semantic cues with structural patterns derived from a minimum spanning tree (MST) over latent representations. By modeling these privacy-sensitive signals in their distributional context, the proposed approach guides the model to generate synthetic rewrites that preserve utility while mitigating privacy risks. Empirical results show that the proposed method significantly enhances author obfuscation and privacy metrics without degrading semantic quality, providing a scalable and model-agnostic solution for privacy preserving data generation in the era of large language models.

[Arxiv](https://arxiv.org/abs/2508.19286)