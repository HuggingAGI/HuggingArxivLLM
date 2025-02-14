# 利用主动学习对话记录提升 RAG：筛选无能者，精准解答有能力者

发布时间：2025年02月13日

`RAG` `问答系统`

> Enhancing RAG with Active Learning on Conversation Records: Reject Incapables and Answer Capables

# 摘要

> 检索增强生成（RAG）是大型语言模型（LLMs）利用外部知识并减少幻觉的关键技术。然而，RAG仍然难以完全防止幻觉响应。为了解决这一问题，至关重要的是要识别容易产生幻觉的样本或引导LLMs给出正确回答，然后由专家标注这些样本以开发高质量的数据集，用于精调LLMs。然而，这类数据集日益稀缺，使其创建变得困难。本文提出利用广泛使用LLMs所产生的大量对话，构建这些数据集，训练LLMs以避免容易引发幻觉的问题，同时准确回答可管理的问题。鉴于专家标注所有对话记录不切实际，本文引入AL4RAG，利用主动学习选择最适合标注的对话样本，在标注预算内优化性能。此外，鉴于传统主动学习方法由于不合适的距离度量而与RAG不完全兼容，我们为RAG主动学习开发了一种新的样本距离测量方法。大量实验表明，我们的方法在多个指标上始终优于基线方法。


> Retrieval-augmented generation (RAG) is a key technique for leveraging external knowledge and reducing hallucinations in large language models (LLMs). However, RAG still struggles to fully prevent hallucinated responses. To address this, it is essential to identify samples prone to hallucination or guide LLMs toward correct responses, which experts then annotate to develop high-quality datasets for refining LLMs. However, the growing scarcity of such datasets makes their creation challenging. This paper proposes using the vast amount of conversations from widespread LLM usage to build these datasets, training LLMs to avoid hallucination-prone questions while accurately responding to manageable ones. Given the impracticality of expert-annotating all conversation records, the paper introduces AL4RAG, which uses active learning to select the most suitable conversation samples for annotation, optimizing performance within an annotation budget. Additionally, recognizing that traditional active learning methods are not fully compatible with RAG due to unsuitable distance metrics, we develop a novel sample distance measurement for RAG active learning. Extensive experiments show that our method consistently outperforms baselines across multiple metrics.

[Arxiv](https://arxiv.org/abs/2502.09073)