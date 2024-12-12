# ShifCon：借助基于移位的对比框架提升非主导语言的能力

发布时间：2024年10月25日

`LLM应用` `语言模型` `多语言处理`

> ShifCon: Enhancing Non-Dominant Language Capabilities with a Shift-based Contrastive Framework

# 摘要

> 尽管利用多语言数据对大型语言模型（LLMs）进行微调能够迅速提升其多语言能力，然而由于不同语言的训练数据不均衡，在主导语言（如英语）和非主导语言之间，它们仍存在性能差距。为进一步提升非主导语言的性能，我们提出了 ShifCon 这一基于移位的对比框架，旨在让其他语言的内部前向过程与主导语言的对齐。具体而言，它把非主导语言的表示移入主导语言子空间，使其能够获取模型参数中编码的相对丰富的信息。在生成前，丰富后的表示再移回原语言子空间。此外，我们引入了子空间距离度量来确定转移表示的最佳层区域，并运用多语言对比学习进一步增强该区域内表示的对齐。实验证明，我们的 ShifCon 框架显著提高了非主导语言的性能，对低资源语言尤其有效。进一步的分析提供了更多见解，以验证 ShifCon 的有效性并推动未来研究。

> Although fine-tuning Large Language Models (LLMs) with multilingual data can rapidly enhance the multilingual capabilities of LLMs, they still exhibit a performance gap between the dominant language (e.g., English) and non-dominant ones due to the imbalance of training data across languages. To further enhance the performance of non-dominant languages, we propose ShifCon, a Shift-based Contrastive framework that aligns the internal forward process of other languages toward that of the dominant one. Specifically, it shifts the representations of non-dominant languages into the dominant language subspace, allowing them to access relatively rich information encoded in the model parameters. The enriched representations are then shifted back into their original language subspace before generation. Moreover, we introduce a subspace distance metric to pinpoint the optimal layer area for shifting representations and employ multilingual contrastive learning to further enhance the alignment of representations within this area. Experiments demonstrate that our ShifCon framework significantly enhances the performance of non-dominant languages, particularly for low-resource ones. Further analysis offers extra insights to verify the effectiveness of ShifCon and propel future research

[Arxiv](https://arxiv.org/abs/2410.19453)