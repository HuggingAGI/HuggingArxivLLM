# VDInstruct：基于内容感知视觉分词的零样本关键信息抽取

发布时间：2025年07月13日

`LLM应用` `文档处理` `信息抽取`

> VDInstruct: Zero-Shot Key Information Extraction via Content-Aware Vision Tokenization

# 摘要

> 关键信息抽取（KIE）通过提取精确语义内容并准确捕捉空间结构，为理解视觉文档（如收据和合同）奠定了基础。然而，现有的多模态大型语言模型（MLLMs）在处理密集文档时表现欠佳，且依赖于随图像大小扩展的视觉分词方法，导致冗余计算和内存低效。为解决这些问题，我们提出了VDInstruct——一款将空间区域检测与语义特征提取分离的MLLM。我们的模型核心是内容感知的分词策略：它不均匀地将整个图像分割成碎片，而是根据文档复杂度生成相应比例的token，保留关键结构同时消除浪费的token。通过三阶段训练范式，我们的模型在KIE基准测试中达到最先进（SOTA）水平，与领先方法的准确性相匹配或超越，同时将图像token数量减少约3.6倍。在零样本评估中，VDInstruct超越了强大的基线模型（如DocOwl 1.5），F1分数提升+5.5，凸显了其对未见文档的鲁棒性。这些发现表明，内容感知的分词策略与显式布局建模相结合，为文档理解提供了有前景的发展方向。数据、源代码和模型权重将公开发布。

> Key Information Extraction (KIE) underpins the understanding of visual documents (e.g., receipts and contracts) by extracting precise semantic content and accurately capturing spatial structure. Yet existing multimodal large language models (MLLMs) often perform poorly on dense documents and rely on vision tokenization approaches that scale with image size, leading to redundant computation and memory inefficiency. To address these challenges, we introduce VDInstruct, an MLLM that separates spatial region detection from semantic feature extraction. Central to our model is a content-aware tokenization strategy: rather than fragmenting the entire image uniformly, it generates tokens in proportion to document complexity, preserving critical structure while eliminating wasted tokens. Leveraging a three-stage training paradigm, our model achieves state-of-the-art (SOTA) results on KIE benchmarks, matching or exceeding the accuracy of leading approaches while reducing the number of image tokens by roughly 3.6x. In zero-shot evaluations, VDInstruct surpasses strong baselines-such as DocOwl 1.5-by +5.5 F1 points, highlighting its robustness to unseen documents. These findings show that content-aware tokenization combined with explicit layout modeling offers a promising direction forward for document understanding. Data, source code, and model weights will be made publicly available.

[Arxiv](https://arxiv.org/abs/2507.09531)