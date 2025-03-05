# 探索Segment Anything Model 2在RGB-热语义分割中的潜力，结合语言指导

发布时间：2025年03月04日

`LLM应用` `机器人`

> Unveiling the Potential of Segment Anything Model 2 for RGB-Thermal Semantic Segmentation with Language Guidance

# 摘要

> 机器人系统的感知能力取决于数据集的丰富性。尽管SAM2在感知任务中展现出强大的潜力，但其固有的训练范式限制了它在RGB-T任务中的应用。为了解决这一难题，我们提出了SHIFNet，这是一种基于SAM2的创新混合交互范式，通过语言指导释放SAM2的潜力，实现高效的RGB-热感知。我们的框架包含两大核心组件：(1)语义感知跨模态融合(SACF)模块，通过文本引导的亲和力学习动态平衡不同模态的贡献，成功克服了SAM2固有的RGB偏见；(2)异质提示解码器(HPD)，通过语义增强模块提升全局语义信息，并结合类别嵌入进一步放大跨模态语义一致性。SHIFNet拥有32.27M可训练参数，在公共基准测试中实现了顶尖的分割性能，在PST900和FMB上分别达到了89.8%和67.8%的优异成绩。该框架不仅推动了预训练大模型在RGB-T分割任务中的适应性，还有效降低了数据收集的高昂成本，同时赋予了机器人系统全面的感知能力。我们的源代码将在https://github.com/iAsakiT3T/SHIFNet公开发布。

> The perception capability of robotic systems relies on the richness of the dataset. Although Segment Anything Model 2 (SAM2), trained on large datasets, demonstrates strong perception potential in perception tasks, its inherent training paradigm prevents it from being suitable for RGB-T tasks. To address these challenges, we propose SHIFNet, a novel SAM2-driven Hybrid Interaction Paradigm that unlocks the potential of SAM2 with linguistic guidance for efficient RGB-Thermal perception. Our framework consists of two key components: (1) Semantic-Aware Cross-modal Fusion (SACF) module that dynamically balances modality contributions through text-guided affinity learning, overcoming SAM2's inherent RGB bias; (2) Heterogeneous Prompting Decoder (HPD) that enhances global semantic information through a semantic enhancement module and then combined with category embeddings to amplify cross-modal semantic consistency. With 32.27M trainable parameters, SHIFNet achieves state-of-the-art segmentation performance on public benchmarks, reaching 89.8% on PST900 and 67.8% on FMB, respectively. The framework facilitates the adaptation of pre-trained large models to RGB-T segmentation tasks, effectively mitigating the high costs associated with data collection while endowing robotic systems with comprehensive perception capabilities. The source code will be made publicly available at https://github.com/iAsakiT3T/SHIFNet.

[Arxiv](https://arxiv.org/abs/2503.02581)