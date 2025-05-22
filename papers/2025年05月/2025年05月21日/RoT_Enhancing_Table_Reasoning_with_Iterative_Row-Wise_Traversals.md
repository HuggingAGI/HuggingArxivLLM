# RoT：迭代行遍历增强表格推理

发布时间：2025年05月21日

`LLM应用` `数据分析` `信息处理`

> RoT: Enhancing Table Reasoning with Iterative Row-Wise Traversals

# 摘要

> 表格推理任务在高效数据获取中至关重要，旨在根据给定表格回答问题。近期，通过长链式思考（Long CoT）增强的推理大型语言模型（RLLMs）在表格推理方面表现卓越。然而，长链式思考在训练成本高昂且由于表格内容幻觉导致可靠性较低。因此，我们提出逐行思考（Row-of-Thought, RoT），通过逐行迭代遍历表格，允许在每次遍历时进行推理扩展和基于反思的优化。利用逐行遍历扩展推理长度并借助LLMs的反思能力，RoT无需额外训练。顺序遍历鼓励对表格内容的更多关注，从而减少幻觉现象。实验表明，RoT在不使用推理模型的情况下，平均比RLLMs高出4.3%的性能，并在WikiTableQuestions和TableBench数据集上与可比模型相比达到最新水平，证明了其有效性。此外，RoT在使用更少推理标记的情况下超越长链式思考，表明其更高的效率。

> The table reasoning task, crucial for efficient data acquisition, aims to answer questions based on the given table. Recently, reasoning large language models (RLLMs) with Long Chain-of-Thought (Long CoT) significantly enhance reasoning capabilities, leading to brilliant performance on table reasoning. However, Long CoT suffers from high cost for training and exhibits low reliability due to table content hallucinations. Therefore, we propose Row-of-Thought (RoT), which performs iteratively row-wise table traversal, allowing for reasoning extension and reflection-based refinement at each traversal. Scaling reasoning length by row-wise traversal and leveraging reflection capabilities of LLMs, RoT is training-free. The sequential traversal encourages greater attention to the table, thus reducing hallucinations. Experiments show that RoT, using non-reasoning models, outperforms RLLMs by an average of 4.3%, and achieves state-of-the-art results on WikiTableQuestions and TableBench with comparable models, proving its effectiveness. Also, RoT outperforms Long CoT with fewer reasoning tokens, indicating higher efficiency.

[Arxiv](https://arxiv.org/abs/2505.15110)