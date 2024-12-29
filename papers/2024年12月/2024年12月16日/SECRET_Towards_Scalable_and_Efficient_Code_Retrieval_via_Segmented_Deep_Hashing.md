# SECRET：借助分段深度哈希达成可扩展且高效的代码检索

发布时间：2024年12月16日

`其他` `软件开发` `代码检索`

> SECRET: Towards Scalable and Efficient Code Retrieval via Segmented Deep Hashing

# 摘要

> 代码检索，即依据用户的自然语言描述来检索代码片段，深受开发人员青睐，在实际的软件开发中发挥着关键作用。深度学习的到来使检索范式从基于词汇的匹配转变为借助深度学习模型将源代码和查询编码为向量表示，依向量相似度来促进代码检索。虽然这些模型效果不错，但管理大规模代码数据库面临重大挑战。此前的研究提出了基于深度哈希的方法，为查询和代码片段生成哈希码，并利用汉明距离快速召回代码候选。然而，这种方法依赖对整个代码库的线性扫描，限制了其可扩展性。为进一步提升大规模代码检索的效率，我们提出了一种新颖的方法SECRET（通过分段深度哈希实现可扩展和高效的代码检索）。SECRET通过迭代训练策略，把现有深度哈希方法算出的长哈希码转化为几个短哈希码段。训练完成后，SECRET通过查找每个段的哈希表来召回代码候选，从而大幅降低召回的时间复杂度。大量实验结果表明，SECRET能将检索时间大幅减少至少 95%，同时达到与现有深度哈希方法相当甚至更优的性能。此外，在哈希表数量相同的情况下，SECRET 与被称为 LSH 的经典基于哈希表的方法相比，也展现出更出色的性能和效率。

> Code retrieval, which retrieves code snippets based on users' natural language descriptions, is widely used by developers and plays a pivotal role in real-world software development. The advent of deep learning has shifted the retrieval paradigm from lexical-based matching towards leveraging deep learning models to encode source code and queries into vector representations, facilitating code retrieval according to vector similarity. Despite the effectiveness of these models, managing large-scale code database presents significant challenges. Previous research proposes deep hashing-based methods, which generate hash codes for queries and code snippets and use Hamming distance for rapid recall of code candidates. However, this approach's reliance on linear scanning of the entire code base limits its scalability. To further improve the efficiency of large-scale code retrieval, we propose a novel approach SECRET (Scalable and Efficient Code Retrieval via SegmEnTed deep hashing). SECRET converts long hash codes calculated by existing deep hashing approaches into several short hash code segments through an iterative training strategy. After training, SECRET recalls code candidates by looking up the hash tables for each segment, the time complexity of recall can thus be greatly reduced. Extensive experimental results demonstrate that SECRET can drastically reduce the retrieval time by at least 95% while achieving comparable or even higher performance of existing deep hashing approaches. Besides, SECRET also exhibits superior performance and efficiency compared to the classical hash table-based approach known as LSH under the same number of hash tables.

[Arxiv](https://arxiv.org/abs/2412.11728)