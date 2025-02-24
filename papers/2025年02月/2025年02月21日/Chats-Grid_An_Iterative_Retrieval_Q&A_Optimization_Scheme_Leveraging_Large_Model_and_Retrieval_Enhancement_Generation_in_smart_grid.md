# Chats-Grid：一种结合大型模型与检索增强生成技术的迭代式检索问答优化方案，应用于智能电网领域

发布时间：2025年02月21日

`RAG` `智能电网` `问答系统`

> Chats-Grid: An Iterative Retrieval Q&A Optimization Scheme Leveraging Large Model and Retrieval Enhancement Generation in smart grid

# 摘要

> 人工智能的快速发展使问答系统在智能搜索引擎、虚拟助手和客服平台中发挥着不可或缺的作用。但在智能电网等动态领域，传统的检索增强生成（RAG）问答系统面临检索质量不足、回答不相关及处理大规模实时数据流效率低下的挑战。本文提出了一种专为智能电网环境设计的优化迭代检索式问答框架——Chats-Grid。该框架在预检索阶段通过高级查询扩展技术，全面覆盖传感器读数、电表记录和控制系统参数等多样化数据源。在检索过程中，Chats-Grid结合BM25稀疏检索和BGE稠密检索技术，有效处理海量异构数据集。在后检索阶段，经过微调的大型语言模型利用提示工程评估相关性，过滤无关结果，并根据上下文准确性重新排序文档。模型进一步生成精准且上下文感知的答案，遵循质量标准，并采用自我检查机制以提升可靠性。实验结果显示，Chats-Grid在保真度、上下文召回率、相关性和准确性方面分别比现有最先进的方法提高了2.37%、2.19%和3.58%。该框架通过优化决策制定和用户交互，推动了智能电网管理的发展，助力构建更具韧性和适应性的智能电网基础设施。

> With rapid advancements in artificial intelligence, question-answering (Q&A) systems have become essential in intelligent search engines, virtual assistants, and customer service platforms. However, in dynamic domains like smart grids, conventional retrieval-augmented generation(RAG) Q&A systems face challenges such as inadequate retrieval quality, irrelevant responses, and inefficiencies in handling large-scale, real-time data streams. This paper proposes an optimized iterative retrieval-based Q&A framework called Chats-Grid tailored for smart grid environments. In the pre-retrieval phase, Chats-Grid advanced query expansion ensures comprehensive coverage of diverse data sources, including sensor readings, meter records, and control system parameters. During retrieval, Best Matching 25(BM25) sparse retrieval and BAAI General Embedding(BGE) dense retrieval in Chats-Grid are combined to process vast, heterogeneous datasets effectively. Post-retrieval, a fine-tuned large language model uses prompt engineering to assess relevance, filter irrelevant results, and reorder documents based on contextual accuracy. The model further generates precise, context-aware answers, adhering to quality criteria and employing a self-checking mechanism for enhanced reliability. Experimental results demonstrate Chats-Grid's superiority over state-of-the-art methods in fidelity, contextual recall, relevance, and accuracy by 2.37%, 2.19%, and 3.58% respectively. This framework advances smart grid management by improving decision-making and user interactions, fostering resilient and adaptive smart grid infrastructures.

[Arxiv](https://arxiv.org/abs/2502.15583)