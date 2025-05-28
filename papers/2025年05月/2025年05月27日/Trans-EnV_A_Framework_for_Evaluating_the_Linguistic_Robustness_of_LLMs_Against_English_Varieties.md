# 跨英语变体评估框架——大型语言模型应对英语变体的语义稳健性测评

发布时间：2025年05月27日

`LLM应用` `语言学`

> Trans-EnV: A Framework for Evaluating the Linguistic Robustness of LLMs Against English Varieties

# 摘要

> 大型语言模型（LLMs）的评估长期聚焦于标准美式英语（SAE），却忽视了全球范围内英语变体的多样性。这种过于狭窄的关注点可能引发公平性问题，因为非标准变体上的性能下降可能导致全球用户获得不平等的收益。因此，全面评估LLMs在多种非标准英语变体上的语言稳健性至关重要。

我们引入了Trans-EnV框架，该框架能够自动将SAE数据集转换为多种英语变体，以评估语言稳健性。我们的框架结合了（1）语言学专家知识，从语言学文献和语料库中整理特定变体的特征和转换指南；以及（2）基于LLM的转换，以确保语言的有效性和可扩展性。

借助Trans-EnV，我们将六个基准数据集转换为38种英语变体，并评估了七种最先进的LLMs。结果显示了显著的性能差异，准确率在非标准变体上最多下降了46.3%。这些发现突显了在多种英语变体中进行全面语言稳健性评估的重要性。

Trans-EnV的每个构建都通过严格的统计测试和与第二语言习得领域研究人员的咨询进行了验证，确保了其语言有效性。我们的\href{https://github.com/jiyounglee-0523/TransEnV}{代码}和\href{https://huggingface.co/collections/jiyounglee0523/transenv-681eadb3c0c8cf363b363fb1}{数据集}公开可用。

> Large Language Models (LLMs) are predominantly evaluated on Standard American English (SAE), often overlooking the diversity of global English varieties. This narrow focus may raise fairness concerns as degraded performance on non-standard varieties can lead to unequal benefits for users worldwide. Therefore, it is critical to extensively evaluate the linguistic robustness of LLMs on multiple non-standard English varieties. We introduce Trans-EnV, a framework that automatically transforms SAE datasets into multiple English varieties to evaluate the linguistic robustness. Our framework combines (1) linguistics expert knowledge to curate variety-specific features and transformation guidelines from linguistic literature and corpora, and (2) LLM-based transformations to ensure both linguistic validity and scalability. Using Trans-EnV, we transform six benchmark datasets into 38 English varieties and evaluate seven state-of-the-art LLMs. Our results reveal significant performance disparities, with accuracy decreasing by up to 46.3% on non-standard varieties. These findings highlight the importance of comprehensive linguistic robustness evaluation across diverse English varieties. Each construction of Trans-EnV was validated through rigorous statistical testing and consultation with a researcher in the field of second language acquisition, ensuring its linguistic validity. Our \href{https://github.com/jiyounglee-0523/TransEnV}{code} and \href{https://huggingface.co/collections/jiyounglee0523/transenv-681eadb3c0c8cf363b363fb1}{datasets} are publicly available.

[Arxiv](https://arxiv.org/abs/2505.20875)