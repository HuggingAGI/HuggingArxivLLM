# ITFormer：融合时间序列与自然语言，构建多模态问答系统，基于大规模多任务数据集

发布时间：2025年06月24日

`LLM应用` `时间序列分析` `问答系统`

> ITFormer: Bridging Time Series and Natural Language for Multi-Modal QA with Large-Scale Multitask Dataset

# 摘要

> 时间序列数据在工业监测、医疗诊断和气候研究等领域发挥着关键作用。然而，如何将高维时间信号与自然语言有效结合，用于动态交互任务，仍是一个重大挑战。为解决这一问题，我们提出了时间序列问答（Time-Series QA）任务，并发布了首个大规模、多任务、时序-文本问答数据集EngineMT-QA，该数据集旨在捕捉时间序列信号与自然语言之间的复杂交互。基于此，我们提出了Instruct Time Transformer（ITFormer），这是一个将时间序列编码器与冻结大型语言模型（LLMs）相结合的创新框架。ITFormer通过有效提取、对齐和融合时序与文本特征，在问答准确率上相比强基线模型实现了显著提升，且仅增加了不到1%的可训练参数。通过结合计算效率与强大的跨模态建模能力，我们的工作建立了一个灵活的时序数据与自然语言结合范式，为多模态人工智能的研究和应用开辟了新道路。更多项目详情，包括数据集和代码，均可访问：https://pandalin98.github.io/itformer_site/

> Time-series data are critical in diverse applications, such as industrial monitoring, medical diagnostics, and climate research. However, effectively integrating these high-dimensional temporal signals with natural language for dynamic, interactive tasks remains a significant challenge. To address this, we introduce the Time-Series Question Answering (Time-Series QA) task and release EngineMT-QA, the first large-scale, multi-task, temporal-textual QA dataset designed to capture complex interactions between time-series signals and natural language. Building on this resource, we propose the Instruct Time Transformer (ITFormer), a novel framework that bridges time-series encoders with frozen large language models (LLMs). ITFormer effectively extracts, aligns, and fuses temporal and textual features, achieving a strong improvement in QA accuracy over strong baselines with fewer than 1\% additional trainable parameters. By combining computational efficiency with robust cross-modal modeling, our work establishes a adaptable paradigm for integrating temporal data with natural language, paving the way for new research and applications in multi-modal AI. More details about the project, including datasets and code, are available at: https://pandalin98.github.io/itformer_site/

[Arxiv](https://arxiv.org/abs/2506.20093)