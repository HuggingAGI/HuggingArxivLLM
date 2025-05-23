# # CUB：语言模型上下文利用技术的基准测试

发布时间：2025年05月22日

`RAG` `问答系统` `检索增强生成`

> CUB: Benchmarking Context Utilisation Techniques for Language Models

# 摘要

> 在问答和事实核查等知识密集型任务中，整合外部知识至关重要。然而，语言模型可能会忽略与过时参数记忆相冲突的相关信息，也可能被无关的上下文分散注意力。尽管最近提出了许多上下文利用操控技术（CMTs）来缓解这些问题，但系统性的比较仍然有限。本文中，我们开发了CUB（上下文利用基准），旨在帮助检索增强生成（RAG）领域的从业者找到最适合其需求的CMT。CUB允许在三种不同的上下文类型上进行严格测试，这些类型捕捉到了现实上下文利用场景中的关键挑战。我们借助CUB，在三个多样化数据集和任务上评估了七种代表CMTs主要类别的最新方法，并应用于九种不同的语言模型。结果显示，大多数现有的CMTs难以处理现实世界检索增强场景中的所有上下文类型。此外，与包含自然样本的更现实数据集相比，许多CMTs在简单的合成数据集上表现过于理想。总体而言，我们的研究强调了对CMTs进行全面测试的必要性，并呼吁开发能够处理多种上下文类型的CMTs。

> Incorporating external knowledge is crucial for knowledge-intensive tasks, such as question answering and fact checking. However, language models (LMs) may ignore relevant information that contradicts outdated parametric memory or be distracted by irrelevant contexts. While many context utilisation manipulation techniques (CMTs) that encourage or suppress context utilisation have recently been proposed to alleviate these issues, few have seen systematic comparison. In this paper, we develop CUB (Context Utilisation Benchmark) to help practitioners within retrieval-augmented generation (RAG) identify the best CMT for their needs. CUB allows for rigorous testing on three distinct context types, observed to capture key challenges in realistic context utilisation scenarios. With this benchmark, we evaluate seven state-of-the-art methods, representative of the main categories of CMTs, across three diverse datasets and tasks, applied to nine LMs. Our results show that most of the existing CMTs struggle to handle the full set of types of contexts that may be encountered in real-world retrieval-augmented scenarios. Moreover, we find that many CMTs display an inflated performance on simple synthesised datasets, compared to more realistic datasets with naturally occurring samples. Altogether, our results show the need for holistic tests of CMTs and the development of CMTs that can handle multiple context types.

[Arxiv](https://arxiv.org/abs/2505.16518)