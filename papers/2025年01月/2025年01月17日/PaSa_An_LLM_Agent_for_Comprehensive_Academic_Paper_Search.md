# PaSa: 全面学术论文搜索的LLM智能体

发布时间：2025年01月17日

`Agent

理由：这篇论文介绍了一个由大型语言模型驱动的高级论文搜索代理PaSa，它能够自主执行一系列决策，如调用搜索工具、阅读论文和筛选相关文献。这表明PaSa是一个具有自主决策能力的智能代理，因此应归类为Agent。` `学术搜索` `人工智能`

> PaSa: An LLM Agent for Comprehensive Academic Paper Search

# 摘要

> 我们推出了PaSa，一个由大型语言模型驱动的高级论文搜索代理。PaSa能够自主执行一系列决策，如调用搜索工具、阅读论文和筛选相关文献，从而为复杂的学术查询提供全面且精准的结果。我们通过强化学习优化PaSa，使用了一个包含35k细粒度学术查询和顶级AI会议论文的合成数据集AutoScholarQuery。此外，我们还开发了RealScholarQuery基准，收集真实世界的学术查询，以评估PaSa在更贴近实际场景中的表现。尽管基于合成数据训练，PaSa在RealScholarQuery上的表现远超现有基线，包括Google、Google Scholar、Google与GPT-4改写查询、chatGPT（启用搜索的GPT-4o）、GPT-o1以及PaSa-GPT-4o（通过提示GPT-4o实现的PaSa）。特别值得一提的是，PaSa-7B在recall@20和recall@50上分别比基于Google的最佳基线Google with GPT-4o高出37.78%和39.90%，并在recall和precision上分别比PaSa-GPT-4o高出30.36%和4.25%。模型、数据集和代码已开源，详见https://github.com/bytedance/pasa。

> We introduce PaSa, an advanced Paper Search agent powered by large language models. PaSa can autonomously make a series of decisions, including invoking search tools, reading papers, and selecting relevant references, to ultimately obtain comprehensive and accurate results for complex scholarly queries. We optimize PaSa using reinforcement learning with a synthetic dataset, AutoScholarQuery, which includes 35k fine-grained academic queries and corresponding papers sourced from top-tier AI conference publications. Additionally, we develop RealScholarQuery, a benchmark collecting real-world academic queries to assess PaSa performance in more realistic scenarios. Despite being trained on synthetic data, PaSa significantly outperforms existing baselines on RealScholarQuery, including Google, Google Scholar, Google with GPT-4 for paraphrased queries, chatGPT (search-enabled GPT-4o), GPT-o1, and PaSa-GPT-4o (PaSa implemented by prompting GPT-4o). Notably, PaSa-7B surpasses the best Google-based baseline, Google with GPT-4o, by 37.78% in recall@20 and 39.90% in recall@50. It also exceeds PaSa-GPT-4o by 30.36% in recall and 4.25% in precision. Model, datasets, and code are available at https://github.com/bytedance/pasa.

[Arxiv](https://arxiv.org/abs/2501.10120)