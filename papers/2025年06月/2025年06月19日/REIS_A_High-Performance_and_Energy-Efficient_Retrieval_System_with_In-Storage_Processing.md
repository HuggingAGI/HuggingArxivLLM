# REIS：一款结合存储内处理的高性能、低能耗检索系统

发布时间：2025年06月19日

`RAG` `搜索引擎` `问答系统`

> REIS: A High-Performance and Energy-Efficient Retrieval System with In-Storage Processing

# 摘要

> 大型语言模型 (LLMs) 存在固有挑战：其知识仅限于训练数据。为解决这一问题，检索增强生成 (RAG) 通过外部知识库补充了 LLMs 的静态训练知识。RAG 包含索引、检索和生成三个阶段。其中，RAG 的检索阶段成为了推理管道中的关键瓶颈。在这一阶段，用户查询会被映射为嵌入向量，随后借助近似最近邻搜索 (ANNS) 算法在数据库中寻找相似向量以识别相关内容。然而，由于数据库规模庞大，ANNS 在主机与存储系统间造成了显著的数据传输开销。为缓解这一问题，先前研究提出了存储内处理 (ISP) 技术，旨在通过在存储内部执行计算来加速 ANNS。然而，现有基于 ISP 的 ANNS 方法存在以下问题：(i) 采用未针对 ISP 系统设计的算法，(ii) 未加速 ANNS 选择数据的检索操作，(iii) 引入重大硬件修改，限制了性能并阻碍了应用。我们提出了 REIS，这是首个专为 RAG 设计的 ISP 系统，通过三种关键机制解决了上述问题。首先，REIS 采用将数据库嵌入向量与其相关文档链接的布局，实现高效检索。其次，通过引入一种针对 ISP 的数据放置技术实现了高效的 ANNS，该技术将嵌入分布在存储系统的平面上，并采用了轻量级的闪存转换层。第三，REIS 利用存储系统内部的现有计算资源。与服务器级系统相比，REIS 将检索性能 (能效) 平均提升了 13 倍 (55 倍)。

> Large Language Models (LLMs) face an inherent challenge: their knowledge is confined to the data that they have been trained on. To overcome this issue, Retrieval-Augmented Generation (RAG) complements the static training-derived knowledge of LLMs with an external knowledge repository. RAG consists of three stages: indexing, retrieval, and generation. The retrieval stage of RAG becomes a significant bottleneck in inference pipelines. In this stage, a user query is mapped to an embedding vector and an Approximate Nearest Neighbor Search (ANNS) algorithm searches for similar vectors in the database to identify relevant items. Due to the large database sizes, ANNS incurs significant data movement overheads between the host and the storage system. To alleviate these overheads, prior works propose In-Storage Processing (ISP) techniques that accelerate ANNS by performing computations inside storage. However, existing works that leverage ISP for ANNS (i) employ algorithms that are not tailored to ISP systems, (ii) do not accelerate data retrieval operations for data selected by ANNS, and (iii) introduce significant hardware modifications, limiting performance and hindering their adoption. We propose REIS, the first ISP system tailored for RAG that addresses these limitations with three key mechanisms. First, REIS employs a database layout that links database embedding vectors to their associated documents, enabling efficient retrieval. Second, it enables efficient ANNS by introducing an ISP-tailored data placement technique that distributes embeddings across the planes of the storage system and employs a lightweight Flash Translation Layer. Third, REIS leverages an ANNS engine that uses the existing computational resources inside the storage system. Compared to a server-grade system, REIS improves the performance (energy efficiency) of retrieval by an average of 13x (55x).

[Arxiv](https://arxiv.org/abs/2506.16444)