# Views：一种硬件友好的图数据库模型，用于存储语义信息

发布时间：2025年08月25日

`RAG` `基础理论`

> Views: A Hardware-friendly Graph Database Model For Storing Semantic Information

# 摘要

> 图数据库（GDB）作为一种日益普及的存储模型，专门用于处理包含条目间关系的数据。除了在数据库领域的广泛应用，GDB的优势使其在构建符号人工智能（AI）和检索增强生成（RAG）方面展现出巨大潜力——在这些领域中，数据间关系的知识是实现的核心。然而，现有GDB模型尚未针对硬件加速进行优化，这在存储容量和计算效率上造成了瓶颈。本文提出了一种硬件友好的GDB模型——Views。我们详细介绍了其为图数据高效存储与检索量身设计的数据结构和组织方式，并证明了其在表示传统图结构时的等效性。我们还通过实际案例展示了该模型在语义推理和认知建模中的符号处理能力，并对未来发展方向进行了简要展望。

> The graph database (GDB) is an increasingly common storage model for data involving relationships between entries. Beyond its widespread usage in database industries, the advantages of GDBs indicate a strong potential in constructing symbolic artificial intelligences (AIs) and retrieval-augmented generation (RAG), where knowledge of data inter-relationships takes a critical role in implementation. However, current GDB models are not optimised for hardware acceleration, leading to bottlenecks in storage capacity and computational efficiency. In this paper, we propose a hardware-friendly GDB model, called Views. We show its data structure and organisation tailored for efficient storage and retrieval of graph data and demonstrate its equivalence to represent traditional graph representations. We further demonstrate its symbolic processing abilities in semantic reasoning and cognitive modelling with practical examples and provide a short perspective on future developments.

[Arxiv](https://arxiv.org/abs/2508.18123)