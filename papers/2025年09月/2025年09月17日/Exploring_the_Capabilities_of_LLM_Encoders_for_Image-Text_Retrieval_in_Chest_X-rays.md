# 探究LLM编码器用于胸部X光片图像-文本检索的性能

发布时间：2025年09月17日

`LLM应用` `医疗健康`

> Exploring the Capabilities of LLM Encoders for Image-Text Retrieval in Chest X-rays

# 摘要

> 视觉语言预训练虽已推动图文对齐技术的进步，但放射学领域的发展仍受临床报告异质性的制约——这类报告常包含缩写、仅含印象的记录及风格差异。与通用领域“数据越多性能越好”的情况不同，盲目扩大嘈杂报告的规模反而可能使模型学习陷入瓶颈甚至退化。我们提出疑问：大型语言模型（LLM）编码器能否提供稳健的临床表征，以跨多种风格迁移并更好地引导图文对齐？为此，我们推出LLM2VEC4CXR（一种针对胸部X光报告的领域适配LLM编码器）和LLM2CLIP4CXR（一种将该编码器与视觉主干网络耦合的双塔框架）。LLM2VEC4CXR不仅比基于BERT的基线模型更擅长理解临床文本，还能应对缩写和风格差异，在报告级指标上实现了出色的临床对齐。LLM2CLIP4CXR则借助这些嵌入提升检索精度和临床相关评分，且跨数据集泛化能力优于以往的医学CLIP变体。我们的模型在160万份胸部X光研究（涵盖公共与私人来源，包含异质性及嘈杂报告）上训练后发现：稳健性——而非单纯的规模——才是实现有效多模态学习的关键。我们已发布相关模型，以助力医学影像-文本表征学习的深入研究。

> Vision-language pretraining has advanced image-text alignment, yet progress in radiology remains constrained by the heterogeneity of clinical reports, including abbreviations, impression-only notes, and stylistic variability. Unlike general-domain settings where more data often leads to better performance, naively scaling to large collections of noisy reports can plateau or even degrade model learning. We ask whether large language model (LLM) encoders can provide robust clinical representations that transfer across diverse styles and better guide image-text alignment. We introduce LLM2VEC4CXR, a domain-adapted LLM encoder for chest X-ray reports, and LLM2CLIP4CXR, a dual-tower framework that couples this encoder with a vision backbone. LLM2VEC4CXR improves clinical text understanding over BERT-based baselines, handles abbreviations and style variation, and achieves strong clinical alignment on report-level metrics. LLM2CLIP4CXR leverages these embeddings to boost retrieval accuracy and clinically oriented scores, with stronger cross-dataset generalization than prior medical CLIP variants. Trained on 1.6M CXR studies from public and private sources with heterogeneous and noisy reports, our models demonstrate that robustness -- not scale alone -- is the key to effective multimodal learning. We release models to support further research in medical image-text representation learning.

[Arxiv](https://arxiv.org/abs/2509.15234)