# 为了提升基于AMR（抽象意义表示）的RAG（Retrieval-Augmented Generation，检索增强生成）模型的性能，我们采用了一种压缩长文本的方法。

发布时间：2024年05月05日

`RAG` `信息检索`

> Compressing Long Context for Enhancing RAG with AMR-based Concept Distillation

# 摘要

> 大型语言模型（LLMs）在信息获取上实现了重大突破，但它们对可能存在缺陷的参数知识的过分依赖，常常导致在处理长尾和特定领域查询时出现幻觉和错误。为了克服这一问题，检索增强生成（RAG）引入了外部非参数知识。尽管如此，检索得到的长篇文档中往往混杂着噪声和无关信息，这会削弱LLMs的注意力集中。借鉴关键概念在提升个人阅读理解中的作用，我们提出了一种创新的基于概念的RAG框架，辅以基于抽象语义表示（AMR）的概念蒸馏算法。该算法能够将杂乱无章的原始检索文档精炼为一组关键概念，这些概念是从AMR的信息节点中提取的，依据的是可靠的语言特征。这些概念明确指导LLMs在推理过程中只专注于重要信息。我们在开放域问答数据集上进行了广泛的实验，验证了我们方法的有效性。实验结果表明，我们提出的基于概念的RAG框架在性能上超越了其他基线方法，尤其是在支持文档数量增加时，同时在不同后端LLMs上也显示出了良好的鲁棒性。这表明，通过过滤干扰信息，蒸馏出的概念能够丰富RAG过程的信息量。据我们所知，这是首次将AMR引入RAG以增强其性能，为使用基于语义的上下文压缩来提升推理性能提供了一种可能的解决方案。

> Large Language Models (LLMs) have made significant strides in information acquisition. However, their overreliance on potentially flawed parametric knowledge leads to hallucinations and inaccuracies, particularly when handling long-tail, domain-specific queries. Retrieval Augmented Generation (RAG) addresses this limitation by incorporating external, non-parametric knowledge. Nevertheless, the retrieved long-context documents often contain noisy, irrelevant information alongside vital knowledge, negatively diluting LLMs' attention. Inspired by the supportive role of essential concepts in individuals' reading comprehension, we propose a novel concept-based RAG framework with the Abstract Meaning Representation (AMR)-based concept distillation algorithm. The proposed algorithm compresses the cluttered raw retrieved documents into a compact set of crucial concepts distilled from the informative nodes of AMR by referring to reliable linguistic features. The concepts explicitly constrain LLMs to focus solely on vital information in the inference process. We conduct extensive experiments on open-domain question-answering datasets to empirically evaluate the proposed method's effectiveness. The results indicate that the concept-based RAG framework outperforms other baseline methods, particularly as the number of supporting documents increases, while also exhibiting robustness across various backbone LLMs. This emphasizes the distilled concepts are informative for augmenting the RAG process by filtering out interference information. To the best of our knowledge, this is the first work introducing AMR to enhance the RAG, presenting a potential solution to augment inference performance with semantic-based context compression.

[Arxiv](https://arxiv.org/abs/2405.03085)