# RomanLens: 潜在罗马化及其在大型语言模型多语言能力中的作用

发布时间：2025年02月11日

`LLM理论` `机器翻译`

> RomanLens: Latent Romanization and its role in Multilinguality in LLMs

# 摘要

> 大型语言模型 (LLMs) 在主要基于英语语料库训练的情况下，仍展现了卓越的多语言泛化能力。一个关键问题是：LLMs 如何实现如此强大的多语言能力？针对非拉丁字母语言，我们研究了罗马化（用拉丁字母表示非拉丁字母文字）在多语言处理中的桥梁作用。通过机制可解释性技术分析下一个词的生成过程，我们发现中间层常将目标词表示为罗马化形式，随后才转为原生文字，这一现象被命名为潜在罗马化。此外，激活补丁实验表明，LLMs 在原生与罗马化文字中对语义概念的编码方式相似，暗示了共享的潜在表示。在向非拉丁语言翻译时，我们的研究发现，目标语言以罗马化形式呈现时，其表示在模型层中出现得比原生文字更早。这些发现深化了我们对 LLMs 多语言表示的理解，并揭示了罗马化在促进语言迁移中的隐性作用。我们的研究为改进多语言语言建模和可解释性提供了新方向。

> Large Language Models (LLMs) exhibit remarkable multilingual generalization despite being predominantly trained on English-centric corpora. A fundamental question arises: how do LLMs achieve such robust multilingual capabilities? For non-Latin script languages, we investigate the role of romanization - the representation of non-Latin scripts using Latin characters - as a bridge in multilingual processing. Using mechanistic interpretability techniques, we analyze next-token generation and find that intermediate layers frequently represent target words in romanized form before transitioning to native script, a phenomenon we term Latent Romanization. Further, through activation patching experiments, we demonstrate that LLMs encode semantic concepts similarly across native and romanized scripts, suggesting a shared underlying representation. Additionally in translation towards non Latin languages, our findings reveal that when the target language is in romanized form, its representations emerge earlier in the model's layers compared to native script. These insights contribute to a deeper understanding of multilingual representation in LLMs and highlight the implicit role of romanization in facilitating language transfer. Our work provides new directions for potentially improving multilingual language modeling and interpretability.

[Arxiv](https://arxiv.org/abs/2502.07424)