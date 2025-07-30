# # 基准测试：基于Transformer嵌入向量的过滤近似最近邻搜索算法

发布时间：2025年07月29日

`其他` `信息检索` `推荐系统`

> Benchmarking Filtered Approximate Nearest Neighbor Search Algorithms on Transformer-based Embedding Vectors

# 摘要

> 文本、图像、音频和视频嵌入模型的突破推动了多个领域的进展，涵盖检索增强生成、推荐系统、车辆/人员重新识别和人脸识别等多个方向。在这些领域中，许多应用都需要一种高效的方法，在嵌入空间中检索与给定查询接近的项目，同时满足基于项目属性的过滤条件，这个问题被称为过滤近似最近邻搜索（FANNS）。在本研究中，我们对FANNS方法进行了全面的综述和分类，并分析了它们在文献中的基准测试情况。通过这样做，我们发现当前FANNS领域的一个关键挑战：缺乏多样性和现实性的数据集，特别是那些基于最新变压器文本嵌入模型的数据集。为了解决这一问题，我们引入了一个新的数据集，包含arXiv存储库中270多万篇研究文章摘要的嵌入向量，同时附带11个真实世界属性，如作者和类别。我们在新的数据集上对各种FANNS方法进行了基准测试，发现每种方法都有其独特的优势和局限性；没有任何一种方法能在所有场景下表现最佳。例如，ACORN支持多种过滤类型，并在数据集规模上表现可靠，但通常会输给更专业的方法。SeRF在有序属性的范围过滤方面表现出色，但无法处理分类属性。Filtered-DiskANN和UNG在中等规模数据集上表现出色，但在大规模数据集上失败，凸显了基于变压器嵌入的挑战，这些嵌入通常比早期嵌入大一个数量级。我们得出结论，没有一种普遍最佳的方法存在。

> Advances in embedding models for text, image, audio, and video drive progress across multiple domains, including retrieval-augmented generation, recommendation systems, vehicle/person reidentification, and face recognition. Many applications in these domains require an efficient method to retrieve items that are close to a given query in the embedding space while satisfying a filter condition based on the item's attributes, a problem known as Filtered Approximate Nearest Neighbor Search (FANNS). In this work, we present a comprehensive survey and taxonomy of FANNS methods and analyze how they are benchmarked in the literature. By doing so, we identify a key challenge in the current FANNS landscape: the lack of diverse and realistic datasets, particularly ones derived from the latest transformer-based text embedding models. To address this, we introduce a novel dataset consisting of embedding vectors for the abstracts of over 2.7 million research articles from the arXiv repository, accompanied by 11 real-world attributes such as authors and categories. We benchmark a wide range of FANNS methods on our novel dataset and find that each method has distinct strengths and limitations; no single approach performs best across all scenarios. ACORN, for example, supports various filter types and performs reliably across dataset scales but is often outperformed by more specialized methods. SeRF shows excellent performance for range filtering on ordered attributes but cannot handle categorical attributes. Filtered-DiskANN and UNG excel on the medium-scale dataset but fail on the large-scale dataset, highlighting the challenge posed by transformer-based embeddings, which are often more than an order of magnitude larger than earlier embeddings. We conclude that no universally best method exists.

[Arxiv](https://arxiv.org/abs/2507.21989)