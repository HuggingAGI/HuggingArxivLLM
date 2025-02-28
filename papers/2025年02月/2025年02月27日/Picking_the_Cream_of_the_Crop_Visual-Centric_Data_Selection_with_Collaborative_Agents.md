# 精挑细选优质资源：视觉导向的数据筛选，协作智能体助力

发布时间：2025年02月27日

`Agent` `计算机视觉`

> Picking the Cream of the Crop: Visual-Centric Data Selection with Collaborative Agents

# 摘要

> 为了提升多模态大型语言模型（MLLMs）处理图像和复杂指令的能力，研究者主要通过整理大规模视觉指令微调数据集来实现，这些数据集要么来自现有的视觉任务，要么通过大型语言模型和图像描述合成生成。然而，这些方法常常存在严重缺陷，包括指令与图像配对不一致以及图像质量低劣等问题。这些问题降低了训练效率，限制了模型性能的提升，因为模型在噪声或不相关的数据上浪费了大量资源，而对整体能力的提升却微乎其微。

为了解决这一问题，我们提出了一种基于智能体协作的视觉中心选择方法（ViSA），该方法专注于图像质量评估和图像-指令相关性评估。具体来说，我们的方法包括1）通过视觉智能体协作量化图像信息，以选择包含丰富视觉信息的图像；2）基于视觉中心的指令质量评估方法，以选择与高质量图像相关的高质量指令数据。最后，我们从大规模开源数据集中重新组织了8万条指令数据。

大量实验表明，ViSA在仅使用原始数据2.5%的情况下，在七个基准测试中表现优于或与当前最先进的模型相当，凸显了我们的数据选择方法的高效性。此外，我们还进行了消融研究，以验证我们方法中每个组件的有效性。代码可在https://github.com/HITsz-TMG/ViSA获取。

> To improve Multimodal Large Language Models' (MLLMs) ability to process images and complex instructions, researchers predominantly curate large-scale visual instruction tuning datasets, which are either sourced from existing vision tasks or synthetically generated using LLMs and image descriptions. However, they often suffer from critical flaws, including misaligned instruction-image pairs and low-quality images. Such issues hinder training efficiency and limit performance improvements, as models waste resources on noisy or irrelevant data with minimal benefit to overall capability. To address this issue, we propose a \textbf{Vi}sual-Centric \textbf{S}election approach via \textbf{A}gents Collaboration (ViSA), which centers on image quality assessment and image-instruction relevance evaluation. Specifically, our approach consists of 1) an image information quantification method via visual agents collaboration to select images with rich visual information, and 2) a visual-centric instruction quality assessment method to select high-quality instruction data related to high-quality images. Finally, we reorganize 80K instruction data from large open-source datasets. Extensive experiments demonstrate that ViSA outperforms or is comparable to current state-of-the-art models on seven benchmarks, using only 2.5\% of the original data, highlighting the efficiency of our data selection approach. Moreover, we conduct ablation studies to validate the effectiveness of each component of our method. The code is available at https://github.com/HITsz-TMG/ViSA.

[Arxiv](https://arxiv.org/abs/2502.19917)