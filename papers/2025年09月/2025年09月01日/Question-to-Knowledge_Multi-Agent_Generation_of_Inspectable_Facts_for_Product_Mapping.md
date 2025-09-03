# 从问题到知识：面向产品映射的可核查事实多智能体生成

发布时间：2025年09月01日

`Agent` `零售与电商`

> Question-to-Knowledge: Multi-Agent Generation of Inspectable Facts for Product Mapping

# 摘要

> 在电子商务中，判断两个产品列表是否指向同一个库存单位（SKU）一直是个难题，尤其是在缺乏明确标识符且各平台产品名称差异悬殊的情况下。基于规则的启发式方法和关键词相似度往往会因忽略品牌、规格或捆绑配置中的细微差异而导致产品误分类。为解决这些问题，我们提出了“问题到知识”（Q2K）多智能体框架，该框架利用大型语言模型（LLMs）实现可靠的SKU映射。Q2K整合了：（1）推理智能体：生成针对性消歧问题；（2）知识智能体：通过精准网络搜索解决这些问题；（3）去重智能体：复用已验证的推理轨迹，减少冗余并确保一致性。此外，人机协作机制可进一步优化不确定案例。在真实消费品数据集上的实验表明，Q2K性能超越了强大的基线模型，在捆绑识别和品牌来源消歧等复杂场景中实现了更高的准确性和鲁棒性。通过复用检索到的推理而非重复搜索，Q2K平衡了准确性与效率，为产品整合提供了可扩展且可解释的解决方案。

> Identifying whether two product listings refer to the same Stock Keeping Unit (SKU) is a persistent challenge in ecommerce, especially when explicit identifiers are missing and product names vary widely across platforms. Rule based heuristics and keyword similarity often misclassify products by overlooking subtle distinctions in brand, specification, or bundle configuration. To overcome these limitations, we propose Question to Knowledge (Q2K), a multi agent framework that leverages Large Language Models (LLMs) for reliable SKU mapping. Q2K integrates: (1) a Reasoning Agent that generates targeted disambiguation questions, (2) a Knowledge Agent that resolves them via focused web searches, and (3) a Deduplication Agent that reuses validated reasoning traces to reduce redundancy and ensure consistency. A human in the loop mechanism further refines uncertain cases. Experiments on real world consumer goods datasets show that Q2K surpasses strong baselines, achieving higher accuracy and robustness in difficult scenarios such as bundle identification and brand origin disambiguation. By reusing retrieved reasoning instead of issuing repeated searches, Q2K balances accuracy with efficiency, offering a scalable and interpretable solution for product integration.

[Arxiv](https://arxiv.org/abs/2509.01182)