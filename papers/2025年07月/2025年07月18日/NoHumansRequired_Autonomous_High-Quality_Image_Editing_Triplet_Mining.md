# 无需人工干预：自主高质量图像编辑中的三元组挖掘

发布时间：2025年07月18日

`LLM应用

理由：这篇论文主要探讨了生成模型在图像编辑中的应用，特别是如何通过自动化方法创建高质量的训练数据集，以提升图像编辑助手的性能。虽然没有直接讨论LLM的理论，但其应用了生成模型（可能基于LLM）来解决实际问题，因此归类为LLM应用。` `计算机视觉` `图像处理`

> NoHumansRequired: Autonomous High-Quality Image Editing Triplet Mining

# 摘要

> 生成模型的最新进展推动了无需额外用户输入即可遵循自然语言指令的图像编辑助手的创建。然而，其监督训练所需的数百万个三元组（原始图像、指令、编辑后图像）面临像素级精确示例挖掘的挑战。每个编辑需仅影响指定区域，同时保持风格连贯、物理合理及视觉吸引力。现有缺乏稳健的自动化编辑质量指标限制了大规模可靠自动化。为此，我们开发了一种自动化的模块化管道，能够跨领域、分辨率、指令复杂度和风格挖掘高保真三元组。该系统基于公开生成模型，无需人工干预，通过任务调整的 Gemini 验证器直接评估指令遵循度和美学，无需分割或接地模型。借助反转和组合引导，我们的挖掘集扩大了约 2.2 倍，支持大规模高保真训练数据的生成。通过自动化重复标注步骤，该方法实现了无需人工标记的大规模训练。为促进这一资源密集型领域的研究，我们发布了包含 358,000 个高质量三元组的开放数据集 NHR-Edit。在最大规模的跨数据集评估中，它超越了所有公开替代方案。此外，我们开源了微调的 Bagel 模型 Bagel-NHR-Edit，在实验中实现了最先进的指标。

> Recent advances in generative modeling enable image editing assistants that follow natural language instructions without additional user input. Their supervised training requires millions of triplets: original image, instruction, edited image. Yet mining pixel-accurate examples is hard. Each edit must affect only prompt-specified regions, preserve stylistic coherence, respect physical plausibility, and retain visual appeal. The lack of robust automated edit-quality metrics hinders reliable automation at scale. We present an automated, modular pipeline that mines high-fidelity triplets across domains, resolutions, instruction complexities, and styles. Built on public generative models and running without human intervention, our system uses a task-tuned Gemini validator to score instruction adherence and aesthetics directly, removing any need for segmentation or grounding models. Inversion and compositional bootstrapping enlarge the mined set by approximately 2.2x, enabling large-scale high-fidelity training data. By automating the most repetitive annotation steps, the approach allows a new scale of training without human labeling effort. To democratize research in this resource-intensive area, we release NHR-Edit: an open dataset of 358k high-quality triplets. In the largest cross-dataset evaluation, it surpasses all public alternatives. We also release Bagel-NHR-Edit, an open-source fine-tuned Bagel model, which achieves state-of-the-art metrics in our experiments.

[Arxiv](https://arxiv.org/abs/2507.14119)