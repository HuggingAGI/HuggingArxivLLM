# 动态分块与选择：大型语言模型中超长上下文的阅读理解

发布时间：2025年05月31日

`LLM应用` `问答系统`

> Dynamic Chunking and Selection for Reading Comprehension of Ultra-Long Context in Large Language Models

# 摘要

> 大型语言模型（LLMs）在处理超长文本时常常力不从心，难以准确理解和解析。现有的改进方法大多通过将长上下文分割为固定长度的块来实现，但这种固定截断方式容易割裂语义相关的内容，从而引发歧义并影响理解的准确性。为了解决这一问题，我们提出了一种简单而有效的动态分割与选择方法，旨在为LLMs提供更流畅的长上下文输入。具体而言，我们通过计算相邻句子间的语义相似度，利用较低的相似度值自适应地将长上下文分割为可变长度的块。此外，我们还引入了一个基于问题感知的分类器，专门用于识别并选择对回答特定问题至关重要的敏感块。实验结果表明，无论是在单跳还是多跳问答任务中，我们的方法都显著优于现有基线模型。特别值得一提的是，该方法在处理不同长度的输入时均表现出色，能够轻松应对长达256k个令牌的超长序列。我们的数据集和代码已开源，感兴趣的朋友可以访问以下链接获取：https://github.com/ECNU-Text-Computing/DCS

> Large language models (LLMs) often struggle to accurately read and comprehend extremely long texts. Current methods for improvement typically rely on splitting long contexts into fixed-length chunks. However, fixed truncation risks separating semantically relevant content, leading to ambiguity and compromising accurate understanding. To overcome this limitation, we propose a straightforward approach for dynamically separating and selecting chunks of long context, facilitating a more streamlined input for LLMs. In particular, we compute semantic similarities between adjacent sentences, using lower similarities to adaptively divide long contexts into variable-length chunks. We further train a question-aware classifier to select sensitive chunks that are critical for answering specific questions. Experimental results on both single-hop and multi-hop question-answering benchmarks show that the proposed approach consistently outperforms strong baselines. Notably, it maintains robustness across a wide range of input lengths, handling sequences of up to 256k tokens. Our datasets and code are available at the following link: https://github.com/ECNU-Text-Computing/DCS

[Arxiv](https://arxiv.org/abs/2506.00773)