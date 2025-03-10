# MV-CLAM: 基于语言模型的跨模态投影实现多视角分子解读

发布时间：2025年02月23日

`LLM应用

摘要讨论了大型语言模型在化学和生物医学领域的应用，特别是在分子理解和推理方面的创新方法。论文提出了一种新框架，以增强LLMs处理多视图分子数据的能力，属于应用层面的研究。因此，归类为LLM应用。` `生物医学`

> MV-CLAM: Multi-View Molecular Interpretation with Cross-Modal Projection via Language Model

# 摘要

> 化学与生物医学领域的人类专业知识依赖于对分子背景的理解，而大型语言模型（LLMs）可以通过分子结构与文本之间的精细对齐来扩展这一能力。然而，现有的分子-文本模型存在两大局限：它们忽略了不同分子视角中的互补信息，并依赖单一视角的表示，这限制了对分子的理解。此外，传统的多视图对齐策略还面临两大挑战：分离的对齐空间导致分子与文本嵌入之间的映射不一致，以及现有的损失函数无法在精细粒度对齐中保留互补信息。这可能限制LLMs全面理解分子特性的能力。为了解决这些问题，我们提出了MV-CLAM，一个新颖的框架。它利用多查询变压器（MQ-Former）将多视图分子表示对齐到统一的文本空间中。我们的方法确保了跨视图一致性，同时通过基于文本查询的令牌级对比损失保留了多样的分子特征。MV-CLAM增强了分子推理能力，提升了检索和描述的准确性。其源代码可在https://github.com/sumin124/mv-clam.git获取。

> Human expertise in chemistry and biomedicine relies on contextual molecular understanding, a capability that large language models (LLMs) can extend through fine-grained alignment between molecular structures and text. Recent multimodal learning advances focus on cross-modal alignment, but existing molecule-text models ignore complementary information in different molecular views and rely on single-view representations, limiting molecular understanding. Moreover, naïve multi-view alignment strategies face two challenges: (1) separate aligned spaces with inconsistent mappings between molecule and text embeddings, and that (2) existing loss objectives fail to preserve complementary information for fine-grained alignment. This can limit the LLM's ability to fully understand the molecular properties. To address these issues, we propose MV-CLAM, a novel framework that aligns multi-view molecular representations into a unified textual space using a multi-query transformer (MQ-Former). Our approach ensures cross-view consistency while a token-level contrastive loss preserves diverse molecular features across textual queries. MV-CLAM enhances molecular reasoning, improving retrieval and captioning accuracy. The source code of MV-CLAM is available in https://github.com/sumin124/mv-clam.git.

[Arxiv](https://arxiv.org/abs/2503.04780)