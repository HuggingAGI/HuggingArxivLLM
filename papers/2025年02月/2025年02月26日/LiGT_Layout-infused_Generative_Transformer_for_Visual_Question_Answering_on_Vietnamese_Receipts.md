# LiGT：布局增强的生成式Transformer模型，专为越南收据设计的视觉问答系统

发布时间：2025年02月26日

`LLM应用` `文档处理`

> LiGT: Layout-infused Generative Transformer for Visual Question Answering on Vietnamese Receipts

# 摘要

> **目的：** 文档视觉问答（Document VQA）要求多模态系统全面处理文本、布局和视觉模式以提供合适的答案。近年来，随着文档数量激增和数字化需求高涨，文档 VQA 获得了广泛关注。然而，现有的文档 VQA 数据集大多集中在英语等资源丰富的语言上。

**方法：** 本文介绍了 ReceiptVQA（**Receipt** **V**isual **Q**uestion **A**nswering），这是首个针对收据的越南语大规模文档 VQA 数据集。收据作为一种具有高商业潜力的文档类型，ReceiptVQA 包含 **9,000多张** 收据图像和 **60,000多组** 手动标注的问题-答案对。此外，我们还提出了 LiGT（**L**ayout-**i**nfused **G**enerative **T**ransformer），一种感知布局的编码-解码架构。该架构设计用于利用语言模型的嵌入层操作布局嵌入，从而尽量减少额外神经模块的使用。

**结果：** 在 ReceiptVQA 上的实验表明，我们的架构表现出了令人鼓舞的性能，与优秀基线模型相比取得了具有竞争力的结果。此外，通过分析实验结果，我们发现与能够生成答案的架构相比，仅使用编码器的模型架构存在明显劣势。我们还观察到，尽管语言模型的语义理解至关重要，但结合多种模态对于处理我们的数据集是必要的。

**结论：** 我们希望这项工作能够推动并促进越南语文档 VQA 的未来发展，为越南语多模态研究社区的多样性做出贡献。


> \textbf{Purpose:} Document Visual Question Answering (document VQA) challenges multimodal systems to holistically handle textual, layout, and visual modalities to provide appropriate answers. Document VQA has gained popularity in recent years due to the increasing amount of documents and the high demand for digitization. Nonetheless, most of document VQA datasets are developed in high-resource languages such as English.
  \textbf{Methods:} In this paper, we present ReceiptVQA (\textbf{Receipt} \textbf{V}isual \textbf{Q}uestion \textbf{A}nswering), the initial large-scale document VQA dataset in Vietnamese dedicated to receipts, a document kind with high commercial potentials. The dataset encompasses \textbf{9,000+} receipt images and \textbf{60,000+} manually annotated question-answer pairs. In addition to our study, we introduce LiGT (\textbf{L}ayout-\textbf{i}nfused \textbf{G}enerative \textbf{T}ransformer), a layout-aware encoder-decoder architecture designed to leverage embedding layers of language models to operate layout embeddings, minimizing the use of additional neural modules.
  \textbf{Results:} Experiments on ReceiptVQA show that our architecture yielded promising performance, achieving competitive results compared with outstanding baselines. Furthermore, throughout analyzing experimental results, we found evident patterns that employing encoder-only model architectures has considerable disadvantages in comparison to architectures that can generate answers. We also observed that it is necessary to combine multiple modalities to tackle our dataset, despite the critical role of semantic understanding from language models.
  \textbf{Conclusion:} We hope that our work will encourage and facilitate future development in Vietnamese document VQA, contributing to a diverse multimodal research community in the Vietnamese language.

[Arxiv](https://arxiv.org/abs/2502.19202)