# MAGA: 大规模类型-受众重构助力预训练语料库扩展

发布时间：2025年02月06日

`LLM理论

**理由**：这篇论文主要讨论了如何通过MAGA重构方法扩展预训练数据，以解决大型语言模型在扩展过程中面临的高质量数据稀缺问题。论文的核心贡献在于提出了一种新的数据扩展方法，并对其进行了评估和分析。这些内容主要涉及大型语言模型的训练和扩展理论，因此将其分类为LLM理论。` `预训练模型`

> MAGA: MAssive Genre-Audience Reformulation to Pretraining Corpus Expansion

# 摘要

> 尽管大型语言模型在各种任务中表现出色，但其持续扩展面临一个关键挑战：高质量预训练数据的稀缺性。虽然模型架构不断演进，但自然语言数据的扩展却举步维艰。为了解决这一瓶颈，我们提出了	extbf{MA}ssive 	extbf{G}enre-	extbf{A}udience~(MAGA)重构方法，该方法系统地从现有语料库中合成多样化、上下文丰富的预训练数据。本工作有三个主要贡献：(1) 我们提出了MAGA重构方法，这是一种轻量级且可扩展的预训练语料库扩展方法，并构建了一个包含770B tokens的MAGACorpus。(2) 我们使用不同的数据预算扩展策略评估MAGACorpus，展示了在各种模型规模（134M-13B）上的一致改进，证明了下一代大规模合成预训练语言模型的必要性。(3) 通过全面分析，我们研究了提示工程对合成训练崩溃的影响，并揭示了使用验证损失的常规崩溃检测指标的局限性。我们的工作表明，MAGA可以在保持质量的同时大幅扩展训练数据集，为超越数据限制的模型扩展提供了一条可靠的途径。

> Despite the remarkable capabilities of large language models across various tasks, their continued scaling faces a critical challenge: the scarcity of high-quality pretraining data. While model architectures continue to evolve, the natural language data struggles to scale up. To tackle this bottleneck, we propose \textbf{MA}ssive \textbf{G}enre-\textbf{A}udience~(MAGA) reformulation method, which systematic synthesizes diverse, contextually-rich pretraining data from existing corpus. This work makes three main contributions: (1) We propose MAGA reformulation method, a lightweight and scalable approach for pretraining corpus expansion, and build a 770B tokens MAGACorpus. (2) We evaluate MAGACorpus with different data budget scaling strategies, demonstrating consistent improvements across various model sizes (134M-13B), establishing the necessity for next-generation large-scale synthetic pretraining language models. (3) Through comprehensive analysis, we investigate prompt engineering's impact on synthetic training collapse and reveal limitations in conventional collapse detection metrics using validation losses. Our work shows that MAGA can substantially expand training datasets while maintaining quality, offering a reliably pathway for scaling models beyond data limitations.

[Arxiv](https://arxiv.org/abs/2502.04235)