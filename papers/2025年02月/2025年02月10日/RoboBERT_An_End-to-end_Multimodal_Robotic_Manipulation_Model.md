# RoboBERT：一款全能型多模态机器人操作模型

发布时间：2025年02月10日

`Agent` `机器人` `人工智能`

> RoboBERT: An End-to-end Multimodal Robotic Manipulation Model

# 摘要

> 具身智能整合了多种模态，使智能体能够同时理解图像、语言和动作。然而，现有模型通常依赖额外数据集或大量预训练以实现性能提升，这消耗了大量训练时间和昂贵的硬件成本。为解决这一问题，我们提出了RoboBERT，一个结合独特训练策略的端到端机器人操作模型。该模型采用基于CNN的扩散策略，通过分离不同模态的训练过程，增强了模型的有效性并确保其稳定性。同时，RoboBERT强调数据增强的重要性，验证了多种技术以显著提升性能。与依赖额外数据或大型基础模型的模型不同，RoboBERT仅使用语言标注的专家演示，同时保持相对较小的模型规模，却实现了极具竞争力的成功率。具体而言，在CALVIN基准测试中，RoboBERT在【数学公式】任务上达到了平均长度4.52，创下了新的最先进（SOTA）记录。此外，当在真实机器人上进行测试时，该模型表现出色，成功率高于使用相同数据训练的其他方法。我们提出，RoboBERT的概念和方法展示了广泛的多样性和兼容性，为轻量化多模态机器人模型的发展做出了重要贡献。代码可访问https://github.com/PeterWangsicheng/RoboBERT

> Embodied intelligence integrates multiple modalities, enabling agents to understand images, language, and actions simultaneously. However, existing models always depend on additional datasets or extensive pre-training to maximize performance improvements, consuming abundant training time and expensive hardware cost. To tackle this issue, we present RoboBERT, a novel end-to-end robotic manipulation model integrated with a unique training strategy. This model utilizes a CNN-based diffusion policy, enhancing and stabilizing the effectiveness of this model by separating training processes for different modalities. It also underscores the importance of data augmentation, verifying various techniques to significantly boost performance. Unlike models that depend on extra data or large foundation models, RoboBERT achieves a highly competitive success rate while using only language-labeled expert demonstrations and maintaining a relatively smaller model size. Specifically, RoboBERT achieves an average length of 4.52 on the CALVIN benchmark for \(ABCD \rightarrow D\) task, setting a new state-of-the-art (SOTA) record. Furthermore, when tested on a real robot, the model demonstrates superior performance, achieving a higher success rate than other methods trained with the same data. We propose that these concepts and methodologies of RoboBERT demonstrate extensive versatility and compatibility, contributing significantly to the development of lightweight multimodal robotic models. The code can be accessed on https://github.com/PeterWangsicheng/RoboBERT

[Arxiv](https://arxiv.org/abs/2502.07837)