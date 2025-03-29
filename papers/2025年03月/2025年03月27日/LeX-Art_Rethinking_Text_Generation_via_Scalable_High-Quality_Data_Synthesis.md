# LeX-Art：重新思考文本生成，通过大规模高质量数据合成实现突破

发布时间：2025年03月27日

`其他` `AI生成内容` `创意设计`

> LeX-Art: Rethinking Text Generation via Scalable High-Quality Data Synthesis

# 摘要

> 我们正式推出 LeX-Art，这是一个全方位的高质量文本-图像合成解决方案，系统性地解决了提示表达与文本渲染保真度之间的差距。我们基于 Deepseek-R1 构建了一个数据驱动的合成流水线，精心打造了 LeX-10K 数据集，其中包含 10,000 张高分辨率、美学优化的 1024×1024 图像。除了数据集构建，我们还开发了 LeX-Enhancer 这一强大的提示增强模型，并训练了 LeX-FLUX 和 LeX-Lumina 两款文本到图像模型，实现了当前最优的文本渲染效果。为了更全面地评估视觉文本生成，我们推出了 LeX-Bench 评估基准，从保真度、美学和对齐度三个维度进行评估，并引入了配对归一化编辑距离（PNED）这一创新性指标，用于更稳健地衡量文本准确性。实验结果表明，LeX-Lumina 在 CreateBench 上实现了 79.81% 的 PNED 提升，而 LeX-FLUX 在颜色（+3.18%）、位置（+4.45%）和字体准确性（+3.81%）方面均超越了现有基线。我们的代码、模型、数据集和演示现已公开。

> We introduce LeX-Art, a comprehensive suite for high-quality text-image synthesis that systematically bridges the gap between prompt expressiveness and text rendering fidelity. Our approach follows a data-centric paradigm, constructing a high-quality data synthesis pipeline based on Deepseek-R1 to curate LeX-10K, a dataset of 10K high-resolution, aesthetically refined 1024$\times$1024 images. Beyond dataset construction, we develop LeX-Enhancer, a robust prompt enrichment model, and train two text-to-image models, LeX-FLUX and LeX-Lumina, achieving state-of-the-art text rendering performance. To systematically evaluate visual text generation, we introduce LeX-Bench, a benchmark that assesses fidelity, aesthetics, and alignment, complemented by Pairwise Normalized Edit Distance (PNED), a novel metric for robust text accuracy evaluation. Experiments demonstrate significant improvements, with LeX-Lumina achieving a 79.81% PNED gain on CreateBench, and LeX-FLUX outperforming baselines in color (+3.18%), positional (+4.45%), and font accuracy (+3.81%). Our codes, models, datasets, and demo are publicly available.

[Arxiv](https://arxiv.org/abs/2503.21749)