# 从稀缺到能力：借助LLMs提升低资源语言的假新闻检测能力

发布时间：2025年01月16日

`LLM应用

**理由**：这篇论文主要讨论了如何利用基于Transformer架构的模型（包括微调的双向编码器表示和大型语言模型）来检测低资源语言（如孟加拉语）中的假新闻。虽然论文中提到了数据集和模型的开发，但其核心应用场景是利用LLM（大型语言模型）来解决实际问题（假新闻检测），因此应归类为LLM应用。` `新闻媒体`

> From Scarcity to Capability: Empowering Fake News Detection in Low-Resource Languages with LLMs

# 摘要

> 假新闻的快速传播已成为全球性挑战，尤其是在孟加拉语等低资源语言中，这些语言缺乏足够的数据集和检测工具。虽然手动事实核查准确，但成本高且速度慢，难以阻止假新闻的传播。为此，我们推出了BanFakeNews-2.0，这是一个强大的数据集，旨在提升孟加拉语假新闻的检测能力。该版本新增了11,700篇经过精心筛选的假新闻文章，均来自可信来源，构建了一个包含47,000篇真实新闻和13,000篇假新闻的比例数据集，涵盖13个类别。此外，我们还创建了一个手动筛选的独立测试集，包含460篇假新闻和540篇真实新闻，用于严格评估。我们致力于从可信来源收集假新闻，并手动验证，同时保留了语言的丰富性。我们开发了一个基于Transformer架构的基准系统，包括微调的双向编码器表示（F1-87%）和带有量化低秩近似的大型语言模型（F1-89%），这些方法显著优于传统方法。BanFakeNews-2.0为低资源语言的假新闻检测研究和应用提供了宝贵资源。我们在Github上公开发布了数据集和模型，以推动这一领域的研究。

> The rapid spread of fake news presents a significant global challenge, particularly in low-resource languages like Bangla, which lack adequate datasets and detection tools. Although manual fact-checking is accurate, it is expensive and slow to prevent the dissemination of fake news. Addressing this gap, we introduce BanFakeNews-2.0, a robust dataset to enhance Bangla fake news detection. This version includes 11,700 additional, meticulously curated fake news articles validated from credible sources, creating a proportional dataset of 47,000 authentic and 13,000 fake news items across 13 categories. In addition, we created a manually curated independent test set of 460 fake and 540 authentic news items for rigorous evaluation. We invest efforts in collecting fake news from credible sources and manually verified while preserving the linguistic richness. We develop a benchmark system utilizing transformer-based architectures, including fine-tuned Bidirectional Encoder Representations from Transformers variants (F1-87\%) and Large Language Models with Quantized Low-Rank Approximation (F1-89\%), that significantly outperforms traditional methods. BanFakeNews-2.0 offers a valuable resource to advance research and application in fake news detection for low-resourced languages. We publicly release our dataset and model on Github to foster research in this direction.

[Arxiv](https://arxiv.org/abs/2501.09604)