# 挖掘无标签数据，释放语言模型的无限潜力

发布时间：2025年03月13日

`LLM应用` `自动驾驶` `问答系统`

> Unlock the Power of Unlabeled Data in Language Driving Model

# 摘要

> 基于视觉的大语言模型（VisionLLMs）在自动驾驶领域发展迅猛，但其进步高度依赖于大规模高质量标注数据，这不仅成本高昂，且耗时耗力。为解决这一难题，我们提出了一种半监督学习方法，通过充分利用丰富但未标注的数据来提升语言-驾驶模型的表现。具体来说，我们首先设计了一系列基于模板的提示，用于从场景中提取信息，并利用少量标注数据训练的模型生成问题，为未标注数据创建伪答案。随后，我们提出了一种自我一致性优化方法，以提升这些伪标注的质量，并将其用于后续训练。基于预训练的VisionLLM（如InternVL），我们构建了一个强大的语言驾驶模型（LDM），在驾驶场景问答任务中超越了现有最优方法。实验结果表明，仅需5%的标注数据，我们的方法即可在DriveLM基准上取得优异表现，与使用完整数据集训练的模型相比毫不逊色。特别地，我们的LDM在有限标注数据下达到了44.85%的性能，结合未标注数据后提升至54.27%，而完整数据集训练的模型在DriveLM基准上达到了60.68%的性能。

> Recent Vision-based Large Language Models~(VisionLLMs) for autonomous driving have seen rapid advancements. However, such promotion is extremely dependent on large-scale high-quality annotated data, which is costly and labor-intensive. To address this issue, we propose unlocking the value of abundant yet unlabeled data to improve the language-driving model in a semi-supervised learning manner. Specifically, we first introduce a series of template-based prompts to extract scene information, generating questions that create pseudo-answers for the unlabeled data based on a model trained with limited labeled data. Next, we propose a Self-Consistency Refinement method to improve the quality of these pseudo-annotations, which are later used for further training. By utilizing a pre-trained VisionLLM (e.g., InternVL), we build a strong Language Driving Model (LDM) for driving scene question-answering, outperforming previous state-of-the-art methods. Extensive experiments on the DriveLM benchmark show that our approach performs well with just 5% labeled data, achieving competitive performance against models trained with full datasets. In particular, our LDM achieves 44.85% performance with limited labeled data, increasing to 54.27% when using unlabeled data, while models trained with full datasets reach 60.68% on the DriveLM benchmark.

[Arxiv](https://arxiv.org/abs/2503.10586)