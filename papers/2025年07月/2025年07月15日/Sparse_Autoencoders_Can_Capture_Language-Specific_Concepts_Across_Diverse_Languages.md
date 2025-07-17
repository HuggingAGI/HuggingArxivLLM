# 稀疏自动编码器可以在多种语言间掌握语言特定的概念

发布时间：2025年07月15日

`LLM理论` `语言识别`

> Sparse Autoencoders Can Capture Language-Specific Concepts Across Diverse Languages

# 摘要

> 探索大型语言模型（LLMs）的多语言机制，有助于我们理解其跨语言处理能力，然而这一领域仍充满挑战。现有研究多聚焦于单个神经元，但其多义性特征使其难以从跨语言表示中提取语言特异性单元。为解决这一问题，我们引入了稀疏自动编码器（SAEs），因其能学习单义特征，这些特征可跨语言表征LLMs中的具体与抽象概念。尽管部分特征呈现语言独立性，但语言特异性特征的研究仍待深入。本研究中，我们提出基于特征激活概率的SAE-LAPE方法，用于在前馈网络中识别语言特异性特征。研究发现，许多此类特征主要集中在模型的中层至顶层，且具有良好的可解释性。这些特征不仅影响模型的多语言性能和语言输出，还可用于语言识别，其性能可与fastText相媲美，同时具备更高的可解释性。我们的代码已开源，地址为https://github.com/LyzanderAndrylie/language-specific-features。


> Understanding the multilingual mechanisms of large language models (LLMs) provides insight into how they process different languages, yet this remains challenging. Existing studies often focus on individual neurons, but their polysemantic nature makes it difficult to isolate language-specific units from cross-lingual representations. To address this, we explore sparse autoencoders (SAEs) for their ability to learn monosemantic features that represent concrete and abstract concepts across languages in LLMs. While some of these features are language-independent, the presence of language-specific features remains underexplored. In this work, we introduce SAE-LAPE, a method based on feature activation probability, to identify language-specific features within the feed-forward network. We find that many such features predominantly appear in the middle to final layers of the model and are interpretable. These features influence the model's multilingual performance and language output and can be used for language identification with performance comparable to fastText along with more interpretability. Our code is available at https://github.com/LyzanderAndrylie/language-specific-features .

[Arxiv](https://arxiv.org/abs/2507.11230)