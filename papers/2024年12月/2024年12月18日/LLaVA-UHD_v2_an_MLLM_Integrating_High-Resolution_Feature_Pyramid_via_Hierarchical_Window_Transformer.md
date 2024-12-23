# LLaVA-UHD v2：一个借助分层窗口变压器融合高分辨率特征金字塔的多语言大型语言模型

发布时间：2024年12月18日

`LLM应用` `多模态` `语言模型`

> LLaVA-UHD v2: an MLLM Integrating High-Resolution Feature Pyramid via Hierarchical Window Transformer

# 摘要

> 在多模态大型语言模型（MLLMs）里，视觉转换器（ViTs）被广泛用于视觉编码。但它们在解决通用 MLLM 任务时表现欠佳。我们认为这是由于缺乏不同视觉层次的信息，阻碍了与语言生成所需的各种语义粒度的匹配。为解决此问题，我们推出了 LLaVA-UHD v2，这是一款先进的 MLLM，以分层窗口转换器为核心，通过构建和整合高分辨率特征金字塔，能够捕捉不同的视觉粒度。作为视觉语言投影仪，Hiwin 转换器包含两个主要模块：（i）通过利用图像金字塔高频细节的 ViT 派生特征上采样过程构建的逆特征金字塔；（ii）分层窗口注意力，专注于跨尺度窗口内的一组关键采样特征，以压缩多级特征图。大量实验表明，LLaVA-UHD v2 在热门基准测试中的表现优于现有 MLLM。值得一提的是，与基线方法相比，我们的设计在 14 个基准测试中平均提升了 3.7％，比如在 DocVQA 上提升了 9.3％。我们公开了所有数据、模型检查点和代码，以助力未来的研究。

> In multimodal large language models (MLLMs), vision transformers (ViTs) are widely employed for visual encoding. However, their performance in solving universal MLLM tasks is not satisfactory. We attribute it to a lack of information from diverse visual levels, impeding alignment with the various semantic granularity required for language generation. To address this issue, we present LLaVA-UHD v2, an advanced MLLM centered around a Hierarchical window transformer that enables capturing diverse visual granularity by constructing and integrating a high-resolution feature pyramid. As a vision-language projector, Hiwin transformer comprises two primary modules: (i) an inverse feature pyramid, constructed by a ViT-derived feature up-sampling process utilizing high-frequency details from an image pyramid, and (ii) hierarchical window attention, focusing on a set of key sampling features within cross-scale windows to condense multi-level feature maps. Extensive experiments demonstrate that LLaVA-UHD v2 achieves superior performance over existing MLLMs on popular benchmarks. Notably, our design brings an average boost of 3.7% across 14 benchmarks compared with the baseline method, 9.3% on DocVQA for instance. We make all the data, model checkpoint, and code publicly available to facilitate future research.

[Arxiv](https://arxiv.org/abs/2412.13871)