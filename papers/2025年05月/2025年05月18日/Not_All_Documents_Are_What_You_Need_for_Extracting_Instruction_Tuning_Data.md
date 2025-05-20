# 并非所有文档都适合用于提取指令微调数据。

发布时间：2025年05月18日

`LLM应用` `软件工程`

> Not All Documents Are What You Need for Extracting Instruction Tuning Data

# 摘要

> 指令微调能显著提升大型语言模型的性能，但其效果高度依赖于高质量的训练数据。最近，研究者开始尝试利用LLMs通过种子问答对（QA）来合成指令数据。然而，这些合成的指令往往缺乏多样性，容易与输入的种子数据趋同，这在实际应用中存在局限性。为了解决这一问题，我们提出了一种从包含丰富且多样化知识的网络语料库中提取指令微调数据的新方法。

一个简单的解决方案是从特定领域的文档中检索并提取所有问答对，但这种方法面临两大挑战：（1）使用LLMs提取所有问答对的成本极高；（2）许多提取出的问答对可能与下游任务无关，这可能会影响模型性能。为了解决这些问题，我们引入了EQUAL，一个高效且可扩展的数据提取框架。通过迭代交替选择文档和提取高质量的问答对，EQUAL有效提升了指令微调的效果。

首先，EQUAL基于对比学习得到的嵌入对文档语料库进行聚类，然后采用多臂老虎机策略来高效识别可能包含有价值问答对的聚类。这种迭代方法在显著降低计算成本的同时，提升了模型性能。在AutoMathText和StackOverflow上进行的四项下游任务实验表明，与LLaMA-3.1-8B和Mistral-7B相比，EQUAL将计算成本降低了5-10倍，并将准确率提升了2.5%。


> Instruction tuning improves the performance of large language models (LLMs), but it heavily relies on high-quality training data. Recently, LLMs have been used to synthesize instruction data using seed question-answer (QA) pairs. However, these synthesized instructions often lack diversity and tend to be similar to the input seeds, limiting their applicability in real-world scenarios. To address this, we propose extracting instruction tuning data from web corpora that contain rich and diverse knowledge. A naive solution is to retrieve domain-specific documents and extract all QA pairs from them, but this faces two key challenges: (1) extracting all QA pairs using LLMs is prohibitively expensive, and (2) many extracted QA pairs may be irrelevant to the downstream tasks, potentially degrading model performance. To tackle these issues, we introduce EQUAL, an effective and scalable data extraction framework that iteratively alternates between document selection and high-quality QA pair extraction to enhance instruction tuning. EQUAL first clusters the document corpus based on embeddings derived from contrastive learning, then uses a multi-armed bandit strategy to efficiently identify clusters that are likely to contain valuable QA pairs. This iterative approach significantly reduces computational cost while boosting model performance. Experiments on AutoMathText and StackOverflow across four downstream tasks show that EQUAL reduces computational costs by 5-10x and improves accuracy by 2.5 percent on LLaMA-3.1-8B and Mistral-7B

[Arxiv](https://arxiv.org/abs/2505.12250)