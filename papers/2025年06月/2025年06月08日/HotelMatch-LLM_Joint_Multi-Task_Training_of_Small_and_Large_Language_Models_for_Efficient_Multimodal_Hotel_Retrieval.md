# # 标题
HotelMatch-LLM：通过协同多任务训练小型与大型语言模型，实现高效多模态酒店检索

发布时间：2025年06月08日

`LLM应用`

> HotelMatch-LLM: Joint Multi-Task Training of Small and Large Language Models for Efficient Multimodal Hotel Retrieval

# 摘要

> 我们推出HotelMatch-LLM，一款专为旅行领域设计的多模态密集检索模型，支持自然语言酒店属性搜索，解决了传统旅行搜索引擎需用户从目的地开始并手动调整搜索参数的局限。HotelMatch-LLM的三大创新包括：(1)特定领域的多任务优化，涵盖新颖的检索、视觉和语言建模目标；(2)结合小型语言模型(SLM)和大型语言模型(LLM)的不对称密集检索架构，实现高效在线查询处理和酒店数据嵌入；(3)强大的图像处理能力，可处理所有酒店图像画廊。在四个多样化测试集上的实验表明，HotelMatch-LLM显著超越现有最先进模型，如VISTA和MARVEL。具体而言，在主要查询类型测试集中，HotelMatch-LLM达到0.681的性能，较最有效基线MARVEL（0.603）有显著提升。分析表明，多任务优化的显著影响、HotelMatch-LLM在不同LLM架构上的良好泛化能力，以及其处理大规模图像画廊的扩展性。

> We present HotelMatch-LLM, a multimodal dense retrieval model for the travel domain that enables natural language property search, addressing the limitations of traditional travel search engines which require users to start with a destination and editing search parameters. HotelMatch-LLM features three key innovations: (1) Domain-specific multi-task optimization with three novel retrieval, visual, and language modeling objectives; (2) Asymmetrical dense retrieval architecture combining a small language model (SLM) for efficient online query processing and a large language model (LLM) for embedding hotel data; and (3) Extensive image processing to handle all property image galleries. Experiments on four diverse test sets show HotelMatch-LLM significantly outperforms state-of-the-art models, including VISTA and MARVEL. Specifically, on the test set -- main query type -- we achieve 0.681 for HotelMatch-LLM compared to 0.603 for the most effective baseline, MARVEL. Our analysis highlights the impact of our multi-task optimization, the generalizability of HotelMatch-LLM across LLM architectures, and its scalability for processing large image galleries.

[Arxiv](https://arxiv.org/abs/2506.07296)