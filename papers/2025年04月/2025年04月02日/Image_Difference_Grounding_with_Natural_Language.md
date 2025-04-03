# 自然语言驱动的图像差异定位

发布时间：2025年04月02日

`其他` `计算机视觉`

> Image Difference Grounding with Natural Language

# 摘要

> 视觉定位（VG）旨在通过自然语言在图像中定位感兴趣区域，但现有方法大多局限于单张图像的解读，这在实际应用中存在局限，例如自动 surveillance 中需要检测多张图像中微小但关键的视觉差异。此外，图像差异理解（IDU）领域的先前研究要么专注于无跨模态文本指导的变化区域检测，要么仅提供粗粒度的差异描述。为推动更精细的视觉-语言感知，我们提出了一项新任务：图像差异定位（IDG），旨在根据用户指令精准定位视觉差异。我们还推出了DiffGround，一个大规模、高质量的IDG数据集，包含多样化视觉变化的图像对，以及用于查询细粒度差异的指令。同时，我们提出了基线模型DiffTracker，该模型通过整合特征差异增强与公共抑制机制，精准定位差异区域。实验结果表明，我们的IDG数据集在实现更精细IDU中具有重要意义。为促进未来研究，DiffGround数据集和DiffTracker模型将公开发布，供研究者使用。

> Visual grounding (VG) typically focuses on locating regions of interest within an image using natural language, and most existing VG methods are limited to single-image interpretations. This limits their applicability in real-world scenarios like automatic surveillance, where detecting subtle but meaningful visual differences across multiple images is crucial. Besides, previous work on image difference understanding (IDU) has either focused on detecting all change regions without cross-modal text guidance, or on providing coarse-grained descriptions of differences. Therefore, to push towards finer-grained vision-language perception, we propose Image Difference Grounding (IDG), a task designed to precisely localize visual differences based on user instructions. We introduce DiffGround, a large-scale and high-quality dataset for IDG, containing image pairs with diverse visual variations along with instructions querying fine-grained differences. Besides, we present a baseline model for IDG, DiffTracker, which effectively integrates feature differential enhancement and common suppression to precisely locate differences. Experiments on the DiffGround dataset highlight the importance of our IDG dataset in enabling finer-grained IDU. To foster future research, both DiffGround data and DiffTracker model will be publicly released.

[Arxiv](https://arxiv.org/abs/2504.01952)