# LLaVA-MORE：针对大语言模型与视觉主干的对比研究，探索提升视觉指令微调效果的方法。

发布时间：2025年03月19日

`LLM应用` `计算机视觉`

> LLaVA-MORE: A Comparative Study of LLMs and Visual Backbones for Enhanced Visual Instruction Tuning

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展凸显了视觉主干和基础语言模型的关键作用。尽管之前的工作主要集中在将这些组件扩展到数十亿参数的规模，但模型规模、架构与性能之间的权衡关系仍未得到充分探索。此外，训练数据和评估协议的不一致性阻碍了直接比较，使得难以得出最优设计选择。

本文中，我们引入了LLaVA-MORE，这是一个结合了近期语言模型与多样化视觉主干的新MLLM系列。为了确保公平比较，我们采用了一致适用于所有架构的统一训练协议。我们的分析系统地探索了从小型到中型规模的LLMs——包括Phi-4、LLaMA-3.1和Gemma-2——以评估多模态推理、生成和指令遵循能力，同时考察了模型规模与性能之间的关系。

除了评估LLM对最终结果的影响，我们还对多种视觉编码器进行了全面研究，涵盖了从基于CLIP的架构到DINOv2、SigLIP和SigLIP2等替代方案。额外的实验还探讨了提高图像分辨率和预训练数据集变化的影响。

总体而言，我们的研究结果为设计更有效的MLLM提供了见解，提供了一个可复现的评估框架，便于直接比较，并可指导未来模型的开发。我们的源代码和训练好的模型已公开发布，可在以下链接访问：https://github.com/aimagelab/LLaVA-MORE。

> Recent progress in Multimodal Large Language Models (MLLMs) has highlighted the critical roles of both the visual backbone and the underlying language model. While prior work has primarily focused on scaling these components to billions of parameters, the trade-offs between model size, architecture, and performance remain underexplored. Additionally, inconsistencies in training data and evaluation protocols have hindered direct comparisons, making it difficult to derive optimal design choices. In this paper, we introduce LLaVA-MORE, a new family of MLLMs that integrates recent language models with diverse visual backbones. To ensure fair comparisons, we employ a unified training protocol applied consistently across all architectures. Our analysis systematically explores both small- and medium-scale LLMs -- including Phi-4, LLaMA-3.1, and Gemma-2 -- to evaluate multimodal reasoning, generation, and instruction following, while examining the relationship between model size and performance. Beyond evaluating the LLM impact on final results, we conduct a comprehensive study of various visual encoders, ranging from CLIP-based architectures to alternatives such as DINOv2, SigLIP, and SigLIP2. Additional experiments investigate the effects of increased image resolution and variations in pre-training datasets. Overall, our results provide insights into the design of more effective MLLMs, offering a reproducible evaluation framework that facilitates direct comparisons and can guide future model development. Our source code and trained models are publicly available at: https://github.com/aimagelab/LLaVA-MORE.

[Arxiv](https://arxiv.org/abs/2503.15621)