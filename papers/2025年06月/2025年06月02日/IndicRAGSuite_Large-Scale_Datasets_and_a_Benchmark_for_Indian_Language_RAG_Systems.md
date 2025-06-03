# IndicRAGSuite：印度语言RAG系统的大规模数据集与基准测试

发布时间：2025年06月02日

`RAG` `多语言处理` `信息检索`

> IndicRAGSuite: Large-Scale Datasets and a Benchmark for Indian Language RAG Systems

# 摘要

> 检索增强生成（RAG）系统让语言模型能够访问相关信息，生成准确、有依据且上下文丰富的响应。然而，印度语言的 RAG 系统发展面临两大挑战：缺乏评估基准和大规模多语言训练数据。现有资源多集中于英语或高资源语言，难以适应印度多语言环境。为此，我们创建了 IndicMSMarco，一个多语言评估基准，涵盖 13 种印度语言，基于 MS MARCO-dev 集的 1000 个多样化查询的翻译。同时，我们利用先进 LLMs 从 19 种印度语言维基百科中构建了大规模（问题、答案、相关段落）数据集，并加入 MS MARCO 数据集的翻译版本，以丰富训练数据并贴近实际信息检索需求。资源现已开放：https://huggingface.co/datasets/ai4bharat/Indic-Rag-Suite

> Retrieval-Augmented Generation (RAG) systems enable language models to access relevant information and generate accurate, well-grounded, and contextually informed responses. However, for Indian languages, the development of high-quality RAG systems is hindered by the lack of two critical resources: (1) evaluation benchmarks for retrieval and generation tasks, and (2) large-scale training datasets for multilingual retrieval. Most existing benchmarks and datasets are centered around English or high-resource languages, making it difficult to extend RAG capabilities to the diverse linguistic landscape of India. To address the lack of evaluation benchmarks, we create IndicMSMarco, a multilingual benchmark for evaluating retrieval quality and response generation in 13 Indian languages, created via manual translation of 1000 diverse queries from MS MARCO-dev set. To address the need for training data, we build a large-scale dataset of (question, answer, relevant passage) tuples derived from the Wikipedias of 19 Indian languages using state-of-the-art LLMs. Additionally, we include translated versions of the original MS MARCO dataset to further enrich the training data and ensure alignment with real-world information-seeking tasks. Resources are available here: https://huggingface.co/datasets/ai4bharat/Indic-Rag-Suite

[Arxiv](https://arxiv.org/abs/2506.01615)