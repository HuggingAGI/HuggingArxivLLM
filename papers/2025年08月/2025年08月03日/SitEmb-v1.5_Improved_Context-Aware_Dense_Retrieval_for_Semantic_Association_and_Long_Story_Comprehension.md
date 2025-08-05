# SitEmb-v1.5：增强上下文感知的密集检索，助力语义关联与长篇叙事理解

发布时间：2025年08月03日

`RAG` `信息检索` `问答系统`

> SitEmb-v1.5: Improved Context-Aware Dense Retrieval for Semantic Association and Long Story Comprehension

# 摘要

> 在长文档中进行检索增强生成（RAG）时，通常需要将文本分割成小块作为检索的基本单位。然而，由于原文档中的依赖关系，理解每个块往往需要上下文信息。虽然之前的研究尝试通过编码更长的上下文窗口来生成更长块的嵌入，但检索和下游任务的改进仍然有限。这主要是因为（1）更长的块增加了嵌入模型的信息编码量，超出了其容量；（2）许多现实应用受限于模型或人类带宽，仍需返回本地化证据。

我们提出了一种新方法，通过在更广泛的上下文窗口下表示短块，从而增强检索性能，即在一个块的上下文中定位其含义。我们发现现有嵌入模型并不擅长编码这种情境化上下文，因此提出了新的训练范式，并开发了情境嵌入模型（SitEmb）。为了验证我们的方法，我们整理了一个专门设计的书情节检索数据集，用于评估情境化检索能力。在这一基准测试中，我们基于BGE-M3的SitEmb-v1模型在仅有10亿参数的情况下，显著超越了现有最先进的嵌入模型，包括一些拥有高达70-80亿参数的模型。我们的80亿参数SitEmb-v1.5模型进一步提升了10%以上的性能，并在不同语言和多个下游应用中展现了强大的效果。

> Retrieval-augmented generation (RAG) over long documents typically involves splitting the text into smaller chunks, which serve as the basic units for retrieval. However, due to dependencies across the original document, contextual information is often essential for accurately interpreting each chunk. To address this, prior work has explored encoding longer context windows to produce embeddings for longer chunks. Despite these efforts, gains in retrieval and downstream tasks remain limited. This is because (1) longer chunks strain the capacity of embedding models due to the increased amount of information they must encode, and (2) many real-world applications still require returning localized evidence due to constraints on model or human bandwidth.
  We propose an alternative approach to this challenge by representing short chunks in a way that is conditioned on a broader context window to enhance retrieval performance -- i.e., situating a chunk's meaning within its context. We further show that existing embedding models are not well-equipped to encode such situated context effectively, and thus introduce a new training paradigm and develop the situated embedding models (SitEmb). To evaluate our method, we curate a book-plot retrieval dataset specifically designed to assess situated retrieval capabilities. On this benchmark, our SitEmb-v1 model based on BGE-M3 substantially outperforms state-of-the-art embedding models, including several with up to 7-8B parameters, with only 1B parameters. Our 8B SitEmb-v1.5 model further improves performance by over 10% and shows strong results across different languages and several downstream applications.

[Arxiv](https://arxiv.org/abs/2508.01959)