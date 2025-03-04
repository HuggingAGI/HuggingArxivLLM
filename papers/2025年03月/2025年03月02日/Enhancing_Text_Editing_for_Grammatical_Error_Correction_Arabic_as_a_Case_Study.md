# # 提升文本编辑能力：以阿拉伯语为例的语法纠错研究  
改进文本编辑功能，专注于语法错误修正：以阿拉伯语为研究案例

发布时间：2025年03月02日

`LLM应用` `语法纠正`

> Enhancing Text Editing for Grammatical Error Correction: Arabic as a Case Study

# 摘要

> 文本编辑将语法错误纠正（GEC）视为序列标注问题，通过为输入标记分配编辑标签实现文本校正。这种方法因高效且易于理解而备受关注。然而，尽管英语中的研究已非常成熟，但阿拉伯语等形态丰富的语言仍鲜有探索。本文提出一种直接从数据中推导编辑标签的文本编辑方法，无需特定语言的编辑规则。我们在阿拉伯语（一种双语制且形态丰富的语言）上验证了该方法的有效性，并研究了不同编辑表示对模型性能的影响。我们的方法在两个阿拉伯语GEC基准数据集上达到了SOTA水平，并在另外两个数据集上与SOTA持平。此外，我们的模型比现有阿拉伯语GEC系统快六倍以上，使其在实际应用中更具实用性。最后，我们探索了集成模型，展示了如何通过结合不同模型进一步提升性能。我们公开发布了代码、数据和预训练模型。


> Text editing frames grammatical error correction (GEC) as a sequence tagging problem, where edit tags are assigned to input tokens, and applying these edits results in the corrected text. This approach has gained attention for its efficiency and interpretability. However, while extensively explored for English, text editing remains largely underexplored for morphologically rich languages like Arabic. In this paper, we introduce a text editing approach that derives edit tags directly from data, eliminating the need for language-specific edits. We demonstrate its effectiveness on Arabic, a diglossic and morphologically rich language, and investigate the impact of different edit representations on model performance. Our approach achieves SOTA results on two Arabic GEC benchmarks and performs on par with SOTA on two others. Additionally, our models are over six times faster than existing Arabic GEC systems, making our approach more practical for real-world applications. Finally, we explore ensemble models, demonstrating how combining different models leads to further performance improvements. We make our code, data, and pretrained models publicly available.

[Arxiv](https://arxiv.org/abs/2503.00985)