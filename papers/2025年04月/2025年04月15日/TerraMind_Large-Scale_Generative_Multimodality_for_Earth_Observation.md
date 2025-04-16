# # TerraMind：面向地球观测的大规模多模态生成平台

发布时间：2025年04月15日

`其他

理由：这篇论文介绍了TerraMind，一个多模态基础模型，专注于地球观测领域。它创新性地采用双尺度表示进行预训练，并在特定应用场景中展示了其优势。虽然涉及模型的应用，但更侧重于特定领域的模型设计与创新，因此归类为“其他”。` `地球观测` `多模态模型`

> TerraMind: Large-Scale Generative Multimodality for Earth Observation

# 摘要

> 我们推出TerraMind——首个支持任意到任意生成的地球观测多模态基础模型。与传统多模态模型不同，TerraMind创新性地采用双尺度表示进行预训练，在token级别编码高层上下文信息以学习跨模态关系，同时在pixel级别利用精细表征捕捉关键空间细微差别。基于全球大规模数据集的九种地理空间模态，TerraMind展现出三大突破：(i) 其双尺度早期融合方法为地球观测开辟了丰富的零样本和少样本应用场景；(ii) 引入"模态思考"(TiM)能力，可在微调和推理过程中自动生成额外人工数据以优化输出；(iii) 在PANGAEA等地球观测领域标准基准测试中超越现有最优水平。TerraMind的预训练数据、模型权重和代码均已开源。

> We present TerraMind, the first any-to-any generative, multimodal foundation model for Earth observation (EO). Unlike other multimodal models, TerraMind is pretrained on dual-scale representations combining both token-level and pixel-level data across modalities. On a token level, TerraMind encodes high-level contextual information to learn cross-modal relationships, while on a pixel level, TerraMind leverages fine-grained representations to capture critical spatial nuances. We pretrained TerraMind on nine geospatial modalities of a global, large-scale dataset. In this paper, we demonstrate that (i) TerraMind's dual-scale early fusion approach unlocks a range of zero-shot and few-shot applications for Earth observation, (ii) TerraMind introduces "Thinking-in-Modalities" (TiM) -- the capability of generating additional artificial data during finetuning and inference to improve the model output -- and (iii) TerraMind achieves beyond state-of-the-art performance in community-standard benchmarks for EO like PANGAEA. The pretraining dataset, the model weights, and our code is open-sourced under a permissive license.

[Arxiv](https://arxiv.org/abs/2504.11171)