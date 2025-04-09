# 高性能的大型语言模型能否保持道德性？——量化网络爬虫退出选项的影响

发布时间：2025年04月08日

`LLM应用` `数据合规` `版权法律`

> Can Performant LLMs Be Ethical? Quantifying the Impact of Web Crawling Opt-Outs

# 摘要

> 越来越多的在线内容版权持有者采用网络爬取退出机制，这一趋势引发了关于数据合规性对大型语言模型（LLM）性能影响的重要讨论。然而，目前尚不清楚这些限制（以及由此导致的预训练数据集过滤）如何影响使用这些语料库训练的模型的能力。在本研究中，我们将这种影响概念化为【数据合规性差距】（DCG），它量化了在符合网络爬取退出机制的数据集上训练的模型与不符合的数据集上训练的模型之间的性能差异。我们通过两种设置衡量数据合规性差距：从头开始预训练模型，以及从现有合规模型进行持续预训练（模拟在预训练后期可能集成受版权保护数据的场景）。我们的15亿参数规模模型实验表明，截至2025年1月，遵守网络数据退出机制并未显著降低通用知识获取能力（接近0\%的DCG）。然而，在生物医学研究等专业领域，排除主要出版商会导致性能下降。这些发现表明，虽然通用型LLM可以使用完全开放的数据训练出同样优秀的性能，但在专业领域，训练后期访问高质量的版权资料可能有助于提升性能。本研究为长期争论的数据合规性与下游模型性能之间的权衡提供了实证见解，为未来关于AI训练实践和政策决策的讨论提供了参考。


> The increasing adoption of web crawling opt-outs by copyright holders of online content raises critical questions about the impact of data compliance on large language model (LLM) performance. However, little is known about how these restrictions (and the resultant filtering of pretraining datasets) affect the capabilities of models trained using these corpora. In this work, we conceptualize this effect as the $\textit{data compliance gap}$ (DCG), which quantifies the performance difference between models trained on datasets that comply with web crawling opt-outs, and those that do not. We measure the data compliance gap in two settings: pretraining models from scratch and continual pretraining from existing compliant models (simulating a setting where copyrighted data could be integrated later in pretraining). Our experiments with 1.5B models show that, as of January 2025, compliance with web data opt-outs does not degrade general knowledge acquisition (close to 0\% DCG). However, in specialized domains such as biomedical research, excluding major publishers leads to performance declines. These findings suggest that while general-purpose LLMs can be trained to perform equally well using fully open data, performance in specialized domains may benefit from access to high-quality copyrighted sources later in training. Our study provides empirical insights into the long-debated trade-off between data compliance and downstream model performance, informing future discussions on AI training practices and policy decisions.

[Arxiv](https://arxiv.org/abs/2504.06219)