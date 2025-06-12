# LLM驱动的表格数据生成中的上下文偏见传播

发布时间：2025年06月11日

`LLM应用` `数据生成` `公平性`

> In-Context Bias Propagation in LLM-Based Tabular Data Generation

# 摘要

> 大型语言模型（LLMs）通过上下文学习（ICL）在合成表格数据生成中得到广泛应用，为数据稀缺场景提供了实用的数据增强方案。尽管此前研究显示，通过增强代表性不足的群体，LLMs能提升下游任务性能，但这些优势通常依赖于访问无偏见且具代表性的上下文示例。然而，现实世界中数据往往噪声大且存在人口统计偏差。本文系统研究了上下文示例中的统计偏见如何影响合成表格数据分布，发现即使轻微偏见也会引发全局统计失真。我们还构建了一个对抗场景，恶意贡献者可通过少量上下文示例将偏见注入合成数据，最终损害特定受保护子群体的下游分类器公平性。这些发现揭示了依赖敏感领域上下文提示的LLM数据生成管道的新漏洞。

> Large Language Models (LLMs) are increasingly used for synthetic tabular data generation through in-context learning (ICL), offering a practical solution for data augmentation in data scarce scenarios. While prior work has shown the potential of LLMs to improve downstream task performance through augmenting underrepresented groups, these benefits often assume access to a subset of unbiased in-context examples, representative of the real dataset. In real-world settings, however, data is frequently noisy and demographically skewed. In this paper, we systematically study how statistical biases within in-context examples propagate to the distribution of synthetic tabular data, showing that even mild in-context biases lead to global statistical distortions. We further introduce an adversarial scenario where a malicious contributor can inject bias into the synthetic dataset via a subset of in-context examples, ultimately compromising the fairness of downstream classifiers for a targeted and protected subgroup. Our findings demonstrate a new vulnerability associated with LLM-based data generation pipelines that rely on in-context prompts with in sensitive domains.

[Arxiv](https://arxiv.org/abs/2506.09630)