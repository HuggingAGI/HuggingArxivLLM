# LettuceDetect: 一款专为 RAG 应用设计的幻觉识别框架

发布时间：2025年02月24日

`RAG` `问答系统`

> LettuceDetect: A Hallucination Detection Framework for RAG Applications

# 摘要

> 尽管检索增强生成（RAG）系统引入了外部知识源，但幻觉答案的问题依然存在。我们提出了LettuceDetect框架，针对现有方法的两大关键问题：传统编码器方法的上下文窗口限制，以及基于LLM方法的计算低效。该框架凭借ModernBERT的长上下文处理能力（支持长达8k tokens），并基于RAGTruth基准数据集进行训练。与所有之前的基于编码器模型相比，我们的方法表现出更优性能，同时规模仅为最优模型的1/30。此外，在与大多数基于提示的方法对比中，LettuceDetect同样表现优异。LettuceDetect是一个基于token分类的模型，能够处理上下文-问题-答案三元组，从而在token级别识别无支持的声明。在RAGTruth语料库上的评估显示，示例级别检测的F1分数达到79.22%，较之前最优的基于编码器架构Luna提升了14.8%。此外，该系统在单个GPU上每秒可处理30至60个示例，使其更适用于实际RAG应用场景。

> Retrieval Augmented Generation (RAG) systems remain vulnerable to hallucinated answers despite incorporating external knowledge sources. We present LettuceDetect a framework that addresses two critical limitations in existing hallucination detection methods: (1) the context window constraints of traditional encoder-based methods, and (2) the computational inefficiency of LLM based approaches. Building on ModernBERT's extended context capabilities (up to 8k tokens) and trained on the RAGTruth benchmark dataset, our approach outperforms all previous encoder-based models and most prompt-based models, while being approximately 30 times smaller than the best models. LettuceDetect is a token-classification model that processes context-question-answer triples, allowing for the identification of unsupported claims at the token level. Evaluations on the RAGTruth corpus demonstrate an F1 score of 79.22% for example-level detection, which is a 14.8% improvement over Luna, the previous state-of-the-art encoder-based architecture. Additionally, the system can process 30 to 60 examples per second on a single GPU, making it more practical for real-world RAG applications.

[Arxiv](https://arxiv.org/abs/2502.17125)