# 用于基于示例的多面查询检索的多面混合

发布时间：2024年12月02日

`LLM应用` `文档检索`

> Multi-Facet Blending for Faceted Query-by-Example Retrieval

# 摘要

> 随着满足细粒度用户意图的需求日益增加，基于特定方面检索相似文档的分面示例查询（QBE）近来备受关注。然而，由于缺乏方面级相关性数据集，此前的方法主要依靠诸如引文之类的基本指标进行文档级比较；但这限制了它们在基于引文的领域中的应用，也无法捕捉到方面约束的复杂性。在本文中，我们提出了一种多方面融合（FaBle）增强方法，该方法通过分解与重组来利用模块化，从而明确合成特定方面的训练集。我们借助LLMs的内在区分能力，自动将文档分解为方面单元，并生成（不）相关对；接着，动态重组这些单元，进而得到基于方面相关性的文档对。我们的模块化无需预定义的方面知识或标签。另外，为证明FaBle在基于引文的科学论文检索之外新领域的有效性，我们发布了一个用于教育考试项目QBE的基准数据集。在1000份文档上进行FaBle增强，对获取方面条件嵌入的训练帮助显著。

> With the growing demand to fit fine-grained user intents, faceted query-by-example (QBE), which retrieves similar documents conditioned on specific facets, has gained recent attention. However, prior approaches mainly depend on document-level comparisons using basic indicators like citations due to the lack of facet-level relevance datasets; yet, this limits their use to citation-based domains and fails to capture the intricacies of facet constraints. In this paper, we propose a multi-facet blending (FaBle) augmentation method, which exploits modularity by decomposing and recomposing to explicitly synthesize facet-specific training sets. We automatically decompose documents into facet units and generate (ir)relevant pairs by leveraging LLMs' intrinsic distinguishing capabilities; then, dynamically recomposing the units leads to facet-wise relevance-informed document pairs. Our modularization eliminates the need for pre-defined facet knowledge or labels. Further, to prove the FaBle's efficacy in a new domain beyond citation-based scientific paper retrieval, we release a benchmark dataset for educational exam item QBE. FaBle augmentation on 1K documents remarkably assists training in obtaining facet conditional embeddings.

[Arxiv](https://arxiv.org/abs/2412.01443)