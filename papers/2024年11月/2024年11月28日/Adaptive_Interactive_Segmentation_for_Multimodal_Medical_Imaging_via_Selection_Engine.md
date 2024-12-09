# 借助选择引擎实现多模态医学成像的自适应交互式分割

发布时间：2024年11月28日

`其他` `医学图像分析`

> Adaptive Interactive Segmentation for Multimodal Medical Imaging via Selection Engine

# 摘要

> 在医学图像分析领域，达成快速、高效且精准的分割对于自动化诊断和治疗意义重大。尽管深度学习的最新进展大幅提升了分割的准确度，但当下的模型在适应性和泛化能力上常遭遇挑战，尤其是处理多模态医学成像数据时。这些局限源自成像模态间的显著差异以及医学数据固有的复杂性。为应对此类挑战，我们提出了基于 SAM2 构建的策略驱动交互式分割模型（SISeg），其通过整合选择引擎提升了各种医学成像模态的分割表现。为减轻 2D 图像序列推理时的内存瓶颈并优化提示帧选择，我们开发了自动化系统——自适应帧选择引擎（AFSE）。此系统无需大量先验医学知识就能动态选出最优提示帧，并通过交互式反馈机制增强了模型推理过程的可解释性。我们在涵盖 7 种代表性医学成像模态的 10 个数据集上开展了广泛实验，证实了 SISeg 模型在多模态任务中的强大适应能力和泛化能力。项目页面和代码将在：[URL] 提供。

> In medical image analysis, achieving fast, efficient, and accurate segmentation is essential for automated diagnosis and treatment. Although recent advancements in deep learning have significantly improved segmentation accuracy, current models often face challenges in adaptability and generalization, particularly when processing multi-modal medical imaging data. These limitations stem from the substantial variations between imaging modalities and the inherent complexity of medical data. To address these challenges, we propose the Strategy-driven Interactive Segmentation Model (SISeg), built on SAM2, which enhances segmentation performance across various medical imaging modalities by integrating a selection engine. To mitigate memory bottlenecks and optimize prompt frame selection during the inference of 2D image sequences, we developed an automated system, the Adaptive Frame Selection Engine (AFSE). This system dynamically selects the optimal prompt frames without requiring extensive prior medical knowledge and enhances the interpretability of the model's inference process through an interactive feedback mechanism. We conducted extensive experiments on 10 datasets covering 7 representative medical imaging modalities, demonstrating the SISeg model's robust adaptability and generalization in multi-modal tasks. The project page and code will be available at: [URL].

[Arxiv](https://arxiv.org/abs/2411.19447)