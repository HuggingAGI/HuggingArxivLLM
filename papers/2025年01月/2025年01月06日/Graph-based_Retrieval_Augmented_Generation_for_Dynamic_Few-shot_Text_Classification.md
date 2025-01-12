# 基于图的检索增强生成：动态少样本文本分类

发布时间：2025年01月06日

`RAG

理由：这篇论文提出了一个名为GORAG的框架，该框架结合了检索增强生成（RAG）技术，专门用于动态少样本文本分类。GORAG通过构建和维护一个自适应信息图，并利用加权边机制和最小生成树来动态检索相关上下文，从而显著提升了文本分类的效果。因此，这篇论文主要涉及检索增强生成（RAG）技术，应归类为RAG。` `文本分类`

> Graph-based Retrieval Augmented Generation for Dynamic Few-shot Text Classification

# 摘要

> 文本分类是自然语言处理中的核心任务，广泛应用于查询优化、数据集成和模式匹配等领域。尽管CNN和BERT等神经网络模型在文本分类中表现优异，但其效果高度依赖大量标注数据。在动态少样本文本分类场景中，标注数据稀缺且目标标签频繁变化，这些模型的性能大打折扣。近年来，大型语言模型（LLMs）凭借其强大的预训练和上下文理解能力崭露头角。现有方法通过为LLMs提供文本输入、候选标签和辅助信息（如描述）来预测文本标签，但输入规模的增加和辅助信息处理带来的噪声限制了其效果。为此，我们提出了GORAG，一种基于图的在线检索增强生成框架，专为动态少样本文本分类设计。GORAG通过从所有目标文本中提取辅助信息，构建并维护一个自适应信息图，而非孤立处理每个输入。它采用加权边机制，优先考虑信息的重要性和可靠性，并利用为每个文本输入定制的最小生成树动态检索相关上下文。实验表明，GORAG通过提供更全面、准确的上下文信息，显著优于现有方法。

> Text classification is a fundamental task in natural language processing, pivotal to various applications such as query optimization, data integration, and schema matching. While neural network-based models, such as CNN and BERT, have demonstrated remarkable performance in text classification, their effectiveness heavily relies on abundant labeled training data. This dependency makes these models less effective in dynamic few-shot text classification, where labeled data is scarce, and target labels frequently evolve based on application needs. Recently, large language models (LLMs) have shown promise due to their extensive pretraining and contextual understanding. Current approaches provide LLMs with text inputs, candidate labels, and additional side information (e.g., descriptions) to predict text labels. However, their effectiveness is hindered by the increased input size and the noise introduced through side information processing. To address these limitations, we propose a graph-based online retrieval-augmented generation framework, namely GORAG, for dynamic few-shot text classification. GORAG constructs and maintains an adaptive information graph by extracting side information across all target texts, rather than treating each input independently. It employs a weighted edge mechanism to prioritize the importance and reliability of extracted information and dynamically retrieves relevant context using a minimum-cost spanning tree tailored for each text input. Empirical evaluations demonstrate that GORAG outperforms existing approaches by providing more comprehensive and accurate contextual information.

[Arxiv](https://arxiv.org/abs/2501.02844)