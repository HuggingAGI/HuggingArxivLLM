# GPT-IMAGE-EDIT-1.5M: 百万级GPT生成图像数据集

发布时间：2025年07月28日

`LLM应用` `图像编辑` `数据集`

> GPT-IMAGE-EDIT-1.5M: A Million-Scale, GPT-Generated Image Dataset

# 摘要

> 近年来，以GPT-4o为代表的大型多模态模型的突破为高质量的指令引导图像编辑树立了新标杆。然而，这些模型及其训练数据的专有属性为开源研究设置了障碍。为解决这一问题，我们推出了GPT-IMAGE-EDIT-1.5M——一个公开可用的大型图像编辑语料库，包含超过150万组高质量的三元组（指令、源图像、编辑后图像）。我们通过充分发挥GPT-4o的多功能能力，系统性地整合并优化了OmniEdit、HQ-Edit和UltraEdit三个主流图像编辑数据集。具体而言，我们的方法包括：1）重新生成输出图像以提升视觉质量和指令对齐度；2）选择性重写提示以增强语义清晰度。为了验证数据集的有效性，我们在GPT-IMAGE-EDIT-1.5M上对先进开源模型进行了微调。实验结果令人振奋：微调后的FluxKontext在GEdit-EN、ImgEdit-Full和Complex-Edit等基准测试中分别取得了7.24、3.80和8.78的优异成绩，展现出更强的指令遵循能力、更高的感知质量，同时保持身份一致性。这些成绩不仅显著超越所有已发布的开源方法，还大幅缩小了与领先专有模型的差距。我们期待GPT-IMAGE-EDIT-1.5M的全面发布能为指令引导图像编辑的开源研究注入新的活力。

> Recent advancements in large multimodal models like GPT-4o have set a new standard for high-fidelity, instruction-guided image editing. However, the proprietary nature of these models and their training data creates a significant barrier for open-source research. To bridge this gap, we introduce GPT-IMAGE-EDIT-1.5M, a publicly available, large-scale image-editing corpus containing more than 1.5 million high-quality triplets (instruction, source image, edited image). We systematically construct this dataset by leveraging the versatile capabilities of GPT-4o to unify and refine three popular image-editing datasets: OmniEdit, HQ-Edit, and UltraEdit. Specifically, our methodology involves 1) regenerating output images to enhance visual quality and instruction alignment, and 2) selectively rewriting prompts to improve semantic clarity. To validate the efficacy of our dataset, we fine-tune advanced open-source models on GPT-IMAGE-EDIT-1.5M. The empirical results are exciting, e.g., the fine-tuned FluxKontext achieves highly competitive performance across a comprehensive suite of benchmarks, including 7.24 on GEdit-EN, 3.80 on ImgEdit-Full, and 8.78 on Complex-Edit, showing stronger instruction following and higher perceptual quality while maintaining identity. These scores markedly exceed all previously published open-source methods and substantially narrow the gap to leading proprietary models. We hope the full release of GPT-IMAGE-EDIT-1.5M can help to catalyze further open research in instruction-guided image editing.

[Arxiv](https://arxiv.org/abs/2507.21033)