# FrugalRAG：学习高效检索与推理，助力多跳问答任务

发布时间：2025年07月10日

`RAG` `问答系统`

> FrugalRAG: Learning to retrieve and reason for multi-hop QA

# 摘要

> 我们探讨了在拥有大型非结构化文档语料库访问权限的情况下回答复杂问题的挑战。目前解决这一问题的主要方法是借助语言模型，通过迭代检索并分析文档，直至模型积累足够信息生成答案。现有改进方法主要集中在提升RAG指标（如准确性和召回率）上，可分为两类：其一是在大型问答数据集上进行微调，这些数据集包含思维链轨迹；其二是借助基于强化学习的微调技术，利用问题-文档相关性信号。然而，检索搜索次数的效率同样重要，却常被忽视。本研究发现：(1) 与近期研究观点相反，提升RAG指标无需大规模微调。具体而言，只需优化提示的标准ReAct流水线即可在HotPotQA等基准测试中超越现有最优方法。(2) 监督学习和强化学习微调可从“节俭性”角度优化RAG，即通过减少推理阶段的搜索次数来降低延迟。例如，使用相同基线模型，仅需少量训练数据（1000个示例），即可在主流RAG基准测试中以近乎一半的搜索成本实现具有竞争力的性能。

> We consider the problem of answering complex questions, given access to a large unstructured document corpus. The de facto approach to solving the problem is to leverage language models that (iteratively) retrieve and reason through the retrieved documents, until the model has sufficient information to generate an answer. Attempts at improving this approach focus on retrieval-augmented generation (RAG) metrics such as accuracy and recall and can be categorized into two types: (a) fine-tuning on large question answering (QA) datasets augmented with chain-of-thought traces, and (b) leveraging RL-based fine-tuning techniques that rely on question-document relevance signals. However, efficiency in the number of retrieval searches is an equally important metric, which has received less attention. In this work, we show that: (1) Large-scale fine-tuning is not needed to improve RAG metrics, contrary to popular claims in recent literature. Specifically, a standard ReAct pipeline with improved prompts can outperform state-of-the-art methods on benchmarks such as HotPotQA. (2) Supervised and RL-based fine-tuning can help RAG from the perspective of frugality, i.e., the latency due to number of searches at inference time. For example, we show that we can achieve competitive RAG metrics at nearly half the cost (in terms of number of searches) on popular RAG benchmarks, using the same base model, and at a small training cost (1000 examples).

[Arxiv](https://arxiv.org/abs/2507.07634)