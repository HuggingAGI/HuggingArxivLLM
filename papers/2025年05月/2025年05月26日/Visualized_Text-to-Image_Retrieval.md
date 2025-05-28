# # 可视化文本到图像检索

发布时间：2025年05月26日

`LLM应用` `计算机视觉` `图像生成`

> Visualized Text-to-Image Retrieval

# 摘要

> 我们提出了一种全新的文本到图像（T2I）检索范式——Visualize-then-Retrieve (VisRet)，它有效解决了现有跨模态嵌入在跨模态相似性对齐方面的局限性。VisRet首先通过T2I生成技术将文本查询转化为图像模态表达，随后在图像模态内部完成检索，从而绕过了传统跨模态检索器在识别细微视觉-空间特征方面的不足。在三个知识密集型T2I检索基准测试中，包括一个新引入的多实体基准，实验结果表明，VisRet在不同嵌入模型上将T2I检索的NDCG@10指标提升了24.5%至32.7%。当应用于检索增强生成流水线时，VisRet还显著提高了下游视觉问答任务的准确性。该方法具有良好的兼容性，可与现成的检索器无缝对接，因此成为知识密集型多模态系统中的一个高效模块。我们的代码和新基准数据集均已开源，详情请访问https://github.com/xiaowu0162/Visualize-then-Retrieve。

> We propose Visualize-then-Retrieve (VisRet), a new paradigm for Text-to-Image (T2I) retrieval that mitigates the limitations of cross-modal similarity alignment of existing multi-modal embeddings. VisRet first projects textual queries into the image modality via T2I generation. Then, it performs retrieval within the image modality to bypass the weaknesses of cross-modal retrievers in recognizing subtle visual-spatial features. Experiments on three knowledge-intensive T2I retrieval benchmarks, including a newly introduced multi-entity benchmark, demonstrate that VisRet consistently improves T2I retrieval by 24.5% to 32.7% NDCG@10 across different embedding models. VisRet also significantly benefits downstream visual question answering accuracy when used in retrieval-augmented generation pipelines. The method is plug-and-play and compatible with off-the-shelf retrievers, making it an effective module for knowledge-intensive multi-modal systems. Our code and the new benchmark are publicly available at https://github.com/xiaowu0162/Visualize-then-Retrieve.

[Arxiv](https://arxiv.org/abs/2505.20291)