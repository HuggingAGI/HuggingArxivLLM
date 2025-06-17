# 借助LLMs识别软件仓库中的硬编码凭证

发布时间：2025年06月16日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）生成的嵌入向量来检测代码中的硬编码凭证，属于将LLMs应用于实际问题的范畴。` `软件安全`

> Detecting Hard-Coded Credentials in Software Repositories via LLMs

# 摘要

> 软件开发人员常常在代码库中硬编码密码、私钥等敏感信息，尽管这会严重威胁软件安全，但这种做法依然屡见不鲜。这些硬编码的凭证为潜在攻击者提供了可乘之机，使他们能够发起诸如后门攻击等恶意行为。现有的检测方法通常采用嵌入模型将文本凭证转化为向量，再交由分类器进行预测。然而，这些模型在处理上下文相关且结构复杂的凭证时表现不佳，常常出现较高的误报率。基于上下文的预训练语言模型，如生成性预训练变换器（GPT），通过运用Transformer架构的自注意力机制，成功捕捉到了输入序列中词汇间的上下文关联。得益于此，GPT在多项自然语言理解任务中取得了显著成就。基于上述分析，我们将LLMs生成的嵌入向量输入深度学习分类器，用于检测代码中的硬编码凭证。在基准数据集上，我们的模型在F1值上比现有最佳方法高出13%。为了方便研究复现，我们已公开全部源代码和数据集。

> Software developers frequently hard-code credentials such as passwords, generic secrets, private keys, and generic tokens in software repositories, even though it is strictly advised against due to the severe threat to the security of the software. These credentials create attack surfaces exploitable by a potential adversary to conduct malicious exploits such as backdoor attacks. Recent detection efforts utilize embedding models to vectorize textual credentials before passing them to classifiers for predictions. However, these models struggle to discriminate between credentials with contextual and complex sequences resulting in high false positive predictions. Context-dependent Pre-trained Language Models (PLMs) or Large Language Models (LLMs) such as Generative Pre-trained Transformers (GPT) tackled this drawback by leveraging the transformer neural architecture capacity for self-attention to capture contextual dependencies between words in input sequences. As a result, GPT has achieved wide success in several natural language understanding endeavors. Hence, we assess LLMs to represent these observations and feed extracted embedding vectors to a deep learning classifier to detect hard-coded credentials. Our model outperforms the current state-of-the-art by 13% in F1 measure on the benchmark dataset. We have made all source code and data publicly available to facilitate the reproduction of all results presented in this paper.

[Arxiv](https://arxiv.org/abs/2506.13090)