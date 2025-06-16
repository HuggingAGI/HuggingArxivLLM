# KEENHash: 将程序高效转换为功能感知嵌入表示，用于大规模二进制代码相似性分析

发布时间：2025年06月13日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型应用于二进制代码相似性分析，通过生成函数嵌入来提高分析效率和效果，属于LLM的实际应用。` `网络安全` `软件工程`

> KEENHash: Hashing Programs into Function-Aware Embeddings for Large-Scale Binary Code Similarity Analysis

# 摘要

> 二进制代码相似性分析（BCSA）在网络安全等领域至关重要。目前，函数级别的差异工具被广泛用于BCSA，通过逐一匹配函数来评估二进制程序的相似性。然而，这些方法因时间复杂度过高，难以在大规模场景中应用。为了解决这一问题，我们提出了一种名为KEENHash的新颖哈希方法，通过大型语言模型生成的函数嵌入，将二进制代码转换为程序级别的表示。KEENHash结合K-Means聚类和特征哈希技术，将整个二进制程序压缩成一个固定长度的紧凑嵌入，从而实现高效且精准的大型程序级别BCSA，超越现有最佳方法。实验数据显示，KEENHash的速度比现有最佳函数匹配工具快215倍以上，且效果丝毫不减。在处理53亿次相似性评估的大规模任务时，KEENHash仅需395.83秒，而传统工具则需56天之久。我们还在包含202,305个二进制程序的大型数据集中，对KEENHash进行了全面评估。结果显示，相比四种现有最佳方法，KEENHash在所有测试中均表现出色，性能提升至少23.16%，尤其在大规模恶意软件检测的BCSA安全场景中，优势尤为明显。

> Binary code similarity analysis (BCSA) is a crucial research area in many fields such as cybersecurity. Specifically, function-level diffing tools are the most widely used in BCSA: they perform function matching one by one for evaluating the similarity between binary programs. However, such methods need a high time complexity, making them unscalable in large-scale scenarios (e.g., 1/n-to-n search). Towards effective and efficient program-level BCSA, we propose KEENHash, a novel hashing approach that hashes binaries into program-level representations through large language model (LLM)-generated function embeddings. KEENHash condenses a binary into one compact and fixed-length program embedding using K-Means and Feature Hashing, allowing us to do effective and efficient large-scale program-level BCSA, surpassing the previous state-of-the-art methods. The experimental results show that KEENHash is at least 215 times faster than the state-of-the-art function matching tools while maintaining effectiveness. Furthermore, in a large-scale scenario with 5.3 billion similarity evaluations, KEENHash takes only 395.83 seconds while these tools will cost at least 56 days. We also evaluate KEENHash on the program clone search of large-scale BCSA across extensive datasets in 202,305 binaries. Compared with 4 state-of-the-art methods, KEENHash outperforms all of them by at least 23.16%, and displays remarkable superiority over them in the large-scale BCSA security scenario of malware detection.

[Arxiv](https://arxiv.org/abs/2506.11612)