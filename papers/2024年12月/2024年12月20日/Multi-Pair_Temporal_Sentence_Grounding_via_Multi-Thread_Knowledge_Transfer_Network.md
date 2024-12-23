# 通过多线程知识转移网络实现多对时态句子的接地

发布时间：2024年12月20日

`其他` `视频处理` `多模态学习`

> Multi-Pair Temporal Sentence Grounding via Multi-Thread Knowledge Transfer Network

# 摘要

> 给定一些包含未修剪视频和句子查询的视频-查询对，时间句子接地（TSG）的目标是在这些视频中找出与查询相关的片段。尽管此前优秀的 TSG 方法成果斐然，但它们都是单独训练每个视频-查询对，忽略了不同对之间的关系。我们发现，相似的视频/查询内容不但能助力 TSG 模型更好地理解和推广跨模态表示，还能协助模型定位一些复杂的视频-查询对。以往的方法采用单线程框架，无法协同训练不同的对，且往往要花费大量时间重新获取冗余知识，限制了其在现实中的应用。为此，本文提出了一种全新的设定：多对 TSG，旨在对这些对进行协同训练。具体而言，我们提出了一种新颖的视频-查询协同训练方法——多线程知识转移网络，以高效且有效地定位各类视频-查询对。首先，我们挖掘不同查询之间的时空语义，使其相互协作。为同时学习模态内和模态间的表示，我们设计了一个跨模态对比模块，通过自监督策略探索语义一致性。为充分对齐不同对之间的视觉和文本表示，我们设计了原型对齐策略，包括 1）匹配对象原型和短语原型以实现空间对齐，2）对齐活动原型和句子原型以实现时间对齐。最后，我们开发了一个自适应负选择模块，自适应生成跨模态匹配的阈值。大量实验证明了我们所提方法的有效性和高效性。

> Given some video-query pairs with untrimmed videos and sentence queries, temporal sentence grounding (TSG) aims to locate query-relevant segments in these videos. Although previous respectable TSG methods have achieved remarkable success, they train each video-query pair separately and ignore the relationship between different pairs. We observe that the similar video/query content not only helps the TSG model better understand and generalize the cross-modal representation but also assists the model in locating some complex video-query pairs. Previous methods follow a single-thread framework that cannot co-train different pairs and usually spends much time re-obtaining redundant knowledge, limiting their real-world applications. To this end, in this paper, we pose a brand-new setting: Multi-Pair TSG, which aims to co-train these pairs. In particular, we propose a novel video-query co-training approach, Multi-Thread Knowledge Transfer Network, to locate a variety of video-query pairs effectively and efficiently. Firstly, we mine the spatial and temporal semantics across different queries to cooperate with each other. To learn intra- and inter-modal representations simultaneously, we design a cross-modal contrast module to explore the semantic consistency by a self-supervised strategy. To fully align visual and textual representations between different pairs, we design a prototype alignment strategy to 1) match object prototypes and phrase prototypes for spatial alignment, and 2) align activity prototypes and sentence prototypes for temporal alignment. Finally, we develop an adaptive negative selection module to adaptively generate a threshold for cross-modal matching. Extensive experiments show the effectiveness and efficiency of our proposed method.

[Arxiv](https://arxiv.org/abs/2412.15678)