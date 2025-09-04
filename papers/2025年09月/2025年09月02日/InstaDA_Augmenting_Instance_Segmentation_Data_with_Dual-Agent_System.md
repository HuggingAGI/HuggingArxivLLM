# InstaDA：双智能体系统驱动的实例分割数据增强

发布时间：2025年09月02日

`Agent` `基础理论`

> InstaDA: Augmenting Instance Segmentation Data with Dual-Agent System

# 摘要

> 获取高质量实例分割数据颇具挑战，这源于标注过程的劳动密集特性以及数据集中严重的类别不平衡问题。近期研究通过结合复制粘贴与扩散模型来构建更多样化的数据集，但这些研究往往缺乏大型语言模型（LLMs）与扩散模型的深度协同，也未能充分挖掘现有训练数据中的丰富信息。为克服这些局限，我们提出了InstaDA——一种全新的无需训练双智能体系统，专门用于扩充实例分割数据集。首先，我们设计了文本智能体（T-Agent），通过LLMs与扩散模型的协同来提升数据多样性。该智能体创新性地引入了提示词优化机制，能基于生成的图像迭代优化提示词。这一过程不仅加强了模型间的协同，还提高了图像利用率并优化了提示词质量。此外，我们还提出了图像智能体（I-Agent），用于丰富整体数据分布。该智能体通过基于训练图像生成新实例，从而扩充训练集。为保证实用性和效率，两个智能体均采用独立自动化工作流，提升了易用性。在LVIS 1.0验证集上的实验显示，InstaDA性能显著提升：与基线相比，边界框平均精度（AP）提高+4.0，掩码AP提高+3.3。此外，它在边界框AP上比当前领先模型DiverGen高出+0.3，掩码AP高出+0.1；在常见类别上，边界框AP显著提升+0.7，掩码AP提升+0.2；频繁类别掩码AP则提升+0.5。

> Acquiring high-quality instance segmentation data is challenging due to the labor-intensive nature of the annotation process and significant class imbalances within datasets. Recent studies have utilized the integration of Copy-Paste and diffusion models to create more diverse datasets. However, these studies often lack deep collaboration between large language models (LLMs) and diffusion models, and underutilize the rich information within the existing training data. To address these limitations, we propose InstaDA, a novel, training-free Dual-Agent system designed to augment instance segmentation datasets. First, we introduce a Text-Agent (T-Agent) that enhances data diversity through collaboration between LLMs and diffusion models. This agent features a novel Prompt Rethink mechanism, which iteratively refines prompts based on the generated images. This process not only fosters collaboration but also increases image utilization and optimizes the prompts themselves. Additionally, we present an Image-Agent (I-Agent) aimed at enriching the overall data distribution. This agent augments the training set by generating new instances conditioned on the training images. To ensure practicality and efficiency, both agents operate as independent and automated workflows, enhancing usability. Experiments conducted on the LVIS 1.0 validation set indicate that InstaDA achieves significant improvements, with an increase of +4.0 in box average precision (AP) and +3.3 in mask AP compared to the baseline. Furthermore, it outperforms the leading model, DiverGen, by +0.3 in box AP and +0.1 in mask AP, with a notable +0.7 gain in box AP on common categories and mask AP gains of +0.2 on common categories and +0.5 on frequent categories.

[Arxiv](https://arxiv.org/abs/2509.02973)