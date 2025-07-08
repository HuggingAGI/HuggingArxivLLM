# # MolVision：基于视觉语言模型的分子性质预测

发布时间：2025年07月04日

`LLM应用` `计算化学` `材料科学`

> MolVision: Molecular Property Prediction with Vision Language Models

# 摘要

> 分子性质预测是计算化学中的基础任务，在药物发现和材料科学领域具有重要应用价值。尽管近期研究探索了使用大型语言模型（LLMs）来解决这一问题，但现有方法主要依赖于如SMILES/SELFIES等分子文本表示方法，这些方法可能存在模糊性和结构信息不足的问题。在本研究中，我们提出了MolVision，这是一种创新的方法，通过整合分子结构图像和文本描述来增强性质预测能力，从而充分利用视觉-语言模型（VLMs）。我们构建了一个包含十个多样化的数据集的基准，覆盖了分类、回归和描述等多种任务类型。在零-shot、少-shot和微调设置下，我们评估了九种不同的VLMs，发现视觉信息能够显著提升预测性能，尤其是在结合LoRA等高效微调策略时。我们的实验结果表明，尽管视觉信息单独使用可能无法达到最佳效果，但通过多模态融合，分子性质预测的泛化能力得到了显著提升。此外，将视觉编码器适应分子图像并与LoRA相结合，进一步优化了模型性能。MolVision的代码和数据集可在以下链接获取：$\href{https://molvision.github.io/MolVision/}{https://molvision.github.io/MolVision/}$.

> Molecular property prediction is a fundamental task in computational chemistry with critical applications in drug discovery and materials science. While recent works have explored Large Language Models (LLMs) for this task, they primarily rely on textual molecular representations such as SMILES/SELFIES, which can be ambiguous and structurally less informative. In this work, we introduce MolVision, a novel approach that leverages Vision-Language Models (VLMs) by integrating both molecular structure as images and textual descriptions to enhance property prediction. We construct a benchmark spanning ten diverse datasets, covering classification, regression and description tasks. Evaluating nine different VLMs in zero-shot, few-shot, and fine-tuned settings, we find that visual information improves prediction performance, particularly when combined with efficient fine-tuning strategies such as LoRA. Our results reveal that while visual information alone is insufficient, multimodal fusion significantly enhances generalization across molecular properties. Adaptation of vision encoder for molecular images in conjunction with LoRA further improves the performance. The code and data is available at : $\href{https://molvision.github.io/MolVision/}{https://molvision.github.io/MolVision/}$.

[Arxiv](https://arxiv.org/abs/2507.03283)