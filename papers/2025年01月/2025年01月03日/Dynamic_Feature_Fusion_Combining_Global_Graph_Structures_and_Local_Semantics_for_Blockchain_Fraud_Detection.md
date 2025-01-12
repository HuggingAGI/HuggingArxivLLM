# 动态特征融合：全局图结构与局部语义的完美结合，助力区块链欺诈检测

发布时间：2025年01月03日

`其他

理由：这篇论文主要讨论的是区块链技术中的智能合约和欺诈检测方法，特别是通过结合图表示学习和语义特征提取来改进欺诈检测。虽然论文中提到了语义特征提取，但这与大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）没有直接关联。因此，这篇论文更适合归类为“其他”。` `区块链`

> Dynamic Feature Fusion: Combining Global Graph Structures and Local Semantics for Blockchain Fraud Detection

# 摘要

> 区块链技术的兴起推动了智能合约在金融领域的广泛应用。然而，现有欺诈检测方法在捕捉交易网络的全局结构模式和交易数据的局部语义关系方面存在明显不足。大多数模型仅关注结构信息或语义特征，导致在检测复杂欺诈模式时效果欠佳。本文提出了一种动态特征融合模型，结合图表示学习和语义特征提取，用于区块链欺诈检测。我们构建全局图表示来建模账户关系，并从交易数据中提取局部上下文特征。通过引入动态多模态融合机制，自适应地整合这些特征，使模型能够有效捕捉结构和语义欺诈模式。我们还开发了一套完整的数据处理流程，包括图构建、时间特征增强和文本预处理。在大规模真实区块链数据集上的实验表明，我们的方法在准确性、F1分数和召回率上均优于现有基准。这项工作强调了整合结构关系和语义相似性对稳健欺诈检测的重要性，并为区块链系统的安全提供了可扩展的解决方案。

> The advent of blockchain technology has facilitated the widespread adoption of smart contracts in the financial sector. However, current fraud detection methodologies exhibit limitations in capturing both global structural patterns within transaction networks and local semantic relationships embedded in transaction data. Most existing models focus on either structural information or semantic features individually, leading to suboptimal performance in detecting complex fraud patterns.In this paper, we propose a dynamic feature fusion model that combines graph-based representation learning and semantic feature extraction for blockchain fraud detection. Specifically, we construct global graph representations to model account relationships and extract local contextual features from transaction data. A dynamic multimodal fusion mechanism is introduced to adaptively integrate these features, enabling the model to capture both structural and semantic fraud patterns effectively. We further develop a comprehensive data processing pipeline, including graph construction, temporal feature enhancement, and text preprocessing. Experimental results on large-scale real-world blockchain datasets demonstrate that our method outperforms existing benchmarks across accuracy, F1 score, and recall metrics. This work highlights the importance of integrating structural relationships and semantic similarities for robust fraud detection and offers a scalable solution for securing blockchain systems.

[Arxiv](https://arxiv.org/abs/2501.02032)