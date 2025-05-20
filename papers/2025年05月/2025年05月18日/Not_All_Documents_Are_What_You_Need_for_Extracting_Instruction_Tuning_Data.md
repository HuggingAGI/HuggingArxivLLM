# 并非所有文档都适合提取指令微调数据

发布时间：2025年05月18日

`LLM应用` `问答系统`

> Not All Documents Are What You Need for Extracting Instruction Tuning Data

# 摘要

> 指令微调能够提升大型语言模型（LLMs）的性能，但这种方法严重依赖高质量的训练数据。最近，研究者开始利用LLMs，通过少量的问答对（QA pairs）生成指令数据。然而，这些生成的指令往往缺乏多样性，容易与输入的种子数据相似，限制了其在实际场景中的应用。为了解决这一问题，我们提出了一种从包含丰富且多样化知识的网络语料库中提取指令微调数据的方法。一个简单的解决方案是检索特定领域的文档，并从中提取所有问答对，但这种方法面临两个关键挑战：（1）使用LLMs提取所有问答对的成本过于高昂；（2）许多提取出的问答对可能与下游任务无关，这可能会降低模型性能。为了解决这些问题，我们引入了EQUAL，这是一个高效且可扩展的数据提取框架，它通过迭代交替选择文档和提取高质量问答对，从而提升指令微调的效果。首先，EQUAL基于对比学习得到的嵌入向量对文档语料库进行聚类；然后，它采用多臂老虎机策略，高效识别出可能包含有价值问答对的聚类。这种迭代方法不仅大幅降低了计算成本，还提升了模型性能。我们在AutoMathText和StackOverflow上进行了实验，涵盖四个下游任务，结果表明，与传统方法相比，EQUAL将计算成本降低了5-10倍，并在LLaMA-3.1-8B和Mistral-7B模型上将准确率提升了2.5个百分点。

> Instruction tuning improves the performance of large language models (LLMs), but it heavily relies on high-quality training data. Recently, LLMs have been used to synthesize instruction data using seed question-answer (QA) pairs. However, these synthesized instructions often lack diversity and tend to be similar to the input seeds, limiting their applicability in real-world scenarios. To address this, we propose extracting instruction tuning data from web corpora that contain rich and diverse knowledge. A naive solution is to retrieve domain-specific documents and extract all QA pairs from them, but this faces two key challenges: (1) extracting all QA pairs using LLMs is prohibitively expensive, and (2) many extracted QA pairs may be irrelevant to the downstream tasks, potentially degrading model performance. To tackle these issues, we introduce EQUAL, an effective and scalable data extraction framework that iteratively alternates between document selection and high-quality QA pair extraction to enhance instruction tuning. EQUAL first clusters the document corpus based on embeddings derived from contrastive learning, then uses a multi-armed bandit strategy to efficiently identify clusters that are likely to contain valuable QA pairs. This iterative approach significantly reduces computational cost while boosting model performance. Experiments on AutoMathText and StackOverflow across four downstream tasks show that EQUAL reduces computational costs by 5-10x and improves accuracy by 2.5 percent on LLaMA-3.1-8B and Mistral-7B

[Arxiv](https://arxiv.org/abs/2505.12250)