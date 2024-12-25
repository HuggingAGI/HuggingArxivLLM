# 理解视觉任务的关键所在：解释性说明

发布时间：2024年12月24日

`LLM应用` `计算机视觉`

> The Key of Understanding Vision Tasks: Explanatory Instructions

# 摘要

> 计算机视觉（CV）虽遵循了自然语言处理（NLP）中的诸多里程碑，像大型 Transformer 模型、广泛预训练以及自回归范式等，却仍未完全达成 NLP 中所见的零样本任务泛化。本文探讨了这样一个观点：CV 采用的离散且术语化的任务定义（比如“图像分割”）或许是零样本任务泛化的关键阻碍。我们假设，由于这些术语定义，深度模型若未真正理解先前见过的任务，就难以泛化到新任务。为验证此，我们引入了解释性指令，它通过输入图像到输出的详细语言转换，提供了定义 CV 任务目标的直观方式。我们创建了一个包含 1200 万个“图像输入→解释性指令→输出”三元组的大规模数据集，并训练了一个以图像和解释性指令为输入的基于自回归的视觉语言模型（基于 AR 的 VLM）。通过学习遵循这些指令，基于 AR 的 VLM 实现了先前见过任务的指令级零样本能力，并在未见过的 CV 任务中展现出强大的零样本泛化能力。代码和数据集将在我们的 GitHub 库中公开。

> Computer Vision (CV) has yet to fully achieve the zero-shot task generalization observed in Natural Language Processing (NLP), despite following many of the milestones established in NLP, such as large transformer models, extensive pre-training, and the auto-regression paradigm, among others. In this paper, we explore the idea that CV adopts discrete and terminological task definitions (\eg, ``image segmentation''), which may be a key barrier to zero-shot task generalization. Our hypothesis is that without truly understanding previously-seen tasks--due to these terminological definitions--deep models struggle to generalize to novel tasks. To verify this, we introduce Explanatory Instructions, which provide an intuitive way to define CV task objectives through detailed linguistic transformations from input images to outputs. We create a large-scale dataset comprising 12 million ``image input $\to$ explanatory instruction $\to$ output'' triplets, and train an auto-regressive-based vision-language model (AR-based VLM) that takes both images and explanatory instructions as input. By learning to follow these instructions, the AR-based VLM achieves instruction-level zero-shot capabilities for previously-seen tasks and demonstrates strong zero-shot generalization for unseen CV tasks. Code and dataset will be openly available on our GitHub repository.

[Arxiv](https://arxiv.org/abs/2412.18525)