# 绿洲：一张图像，多模态指令数据合成全靠它

发布时间：2025年03月11日

`LLM应用` `数据生成` `生成式AI`

> Oasis: One Image is All You Need for Multimodal Instruction Data Synthesis

# 摘要

> 多模态大型语言模型（MLLMs）的成功主要得益于大规模训练数据的支持。然而，出于隐私考虑，许多MLLMs的训练数据难以获取。再加上多模态数据收集成本高昂、耗时费力，这一问题更加凸显。那么，是否可以在不牺牲多样性和质量的前提下，自动合成多模态训练数据呢？在本文中，我们提出了一种名为Oasis的新方法，仅凭图像即可生成高质量的多模态数据。Oasis突破了传统方法的局限，通过仅向MLLMs输入图像，大幅提升了数据多样性。我们的方法还采用了精细的质量控制机制，确保数据质量。我们收集了超过50万的数据，并在LLaVA-NeXT上进行了增量实验。实验结果表明，我们的方法能显著提升MLLMs的性能。此外，基于图像的合成方式，让我们可以更专注于MLLMs在特定领域的应用能力。代码和数据将公开发布。

> The success of multi-modal large language models (MLLMs) has been largely attributed to the large-scale training data. However, the training data of many MLLMs is unavailable due to privacy concerns. The expensive and labor-intensive process of collecting multi-modal data further exacerbates the problem. Is it possible to synthesize multi-modal training data automatically without compromising diversity and quality? In this paper, we propose a new method, Oasis, to synthesize high-quality multi-modal data with only images. Oasis breaks through traditional methods by prompting only images to the MLLMs, thus extending the data diversity by a large margin. Our method features a delicate quality control method which ensures the data quality. We collected over 500k data and conducted incremental experiments on LLaVA-NeXT. Extensive experiments demonstrate that our method can significantly improve the performance of MLLMs. The image-based synthesis also allows us to focus on the specific-domain ability of MLLMs. Code and data will be publicly available.

[Arxiv](https://arxiv.org/abs/2503.08741)