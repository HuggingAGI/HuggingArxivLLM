# RAMQA: 检索增强多模态问答的统一框架

发布时间：2025年01月22日

`RAG

理由：这篇论文主要讨论了多模态检索增强问答（MRAQA）框架，该框架结合了文本与图像的多模态信息，并通过检索增强生成（RAG）技术来提升问答系统的性能。论文中提到的RAMQA框架，特别是其生成式排序模型，属于RAG技术的应用范畴，因为它通过检索和生成相结合的方式来提升问答系统的效果。因此，这篇论文应被分类为RAG。` `信息检索`

> RAMQA: A Unified Framework for Retrieval-Augmented Multi-Modal Question Answering

# 摘要

> # 多模态检索增强问答（MRAQA）
多模态检索增强问答（MRAQA）融合了文本与图像，在信息检索（IR）和自然语言处理（NLP）领域备受瞩目。传统排序方法依赖小型编码器语言模型，难以与现代基于解码器的生成式大型语言模型（LLMs）兼容，而后者已在NLP任务中展现出强大能力。为此，我们提出了RAMQA框架，将学习排序与生成式排列增强排序技术相结合。我们首先以LLaVA为骨干训练点对点多模态排序器，随后通过指令微调训练LLaMA模型，采用创新的自回归多任务学习方法对前k个文档进行重排序。我们的生成式排序模型不仅能生成重排序的文档ID，还能从多种排列的候选文档中提取具体答案。在WebQA和MultiModalQA两个MRAQA基准上的实验表明，该方法显著超越了现有基线，验证了其有效性。代码和数据已开源：https://github.com/TonyBY/RAMQA

> Multi-modal retrieval-augmented Question Answering (MRAQA), integrating text and images, has gained significant attention in information retrieval (IR) and natural language processing (NLP). Traditional ranking methods rely on small encoder-based language models, which are incompatible with modern decoder-based generative large language models (LLMs) that have advanced various NLP tasks. To bridge this gap, we propose RAMQA, a unified framework combining learning-to-rank methods with generative permutation-enhanced ranking techniques. We first train a pointwise multi-modal ranker using LLaVA as the backbone. Then, we apply instruction tuning to train a LLaMA model for re-ranking the top-k documents using an innovative autoregressive multi-task learning approach. Our generative ranking model generates re-ranked document IDs and specific answers from document candidates in various permutations. Experiments on two MRAQA benchmarks, WebQA and MultiModalQA, show significant improvements over strong baselines, highlighting the effectiveness of our approach. Code and data are available at: https://github.com/TonyBY/RAMQA

[Arxiv](https://arxiv.org/abs/2501.13297)