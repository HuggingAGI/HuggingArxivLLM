# MAP：重新审视权重分解在低秩适配中的应用

发布时间：2025年05月29日

`LLM理论` `机器学习`

> MAP: Revisiting Weight Decomposition for Low-Rank Adaptation

# 摘要

> 大型语言模型的快速发展为自然语言处理领域带来了翻天覆地的变化，但其微调过程的高计算成本仍是一个亟待解决的难题，严重阻碍了模型的广泛应用。为应对这一挑战，参数高效微调（PEFT）方法如LoRA应运而生。近期研究DoRA尝试将权重调整进一步分解为方向和幅度两个部分。然而，现有方法通常在列级别上以启发式方式定义方向，缺乏严谨的几何基础。本文提出了一种全新的框架MAP，它将权重矩阵重新表述为高维向量，并以严谨的方式将其适应过程分解为方向和幅度。MAP通过归一化预训练权重、学习方向更新，并引入两个标量系数分别独立缩放基向量和更新向量的幅度，使适应过程更加灵活且可解释。这一设计不仅保持了与现有PEFT方法的兼容性，还显著提升了模型性能。大量实验结果表明，MAP与现有方法结合使用时能带来显著的性能提升，为现有的PEFT方法提供了一种简单而强大的增强方案。鉴于MAP的通用性和简洁性，我们期待它能够成为未来PEFT方法设计的默认配置。

> The rapid development of large language models has revolutionized natural language processing, but their fine-tuning remains computationally expensive, hindering broad deployment. Parameter-efficient fine-tuning (PEFT) methods, such as LoRA, have emerged as solutions. Recent work like DoRA attempts to further decompose weight adaptation into direction and magnitude components. However, existing formulations often define direction heuristically at the column level, lacking a principled geometric foundation. In this paper, we propose MAP, a novel framework that reformulates weight matrices as high-dimensional vectors and decouples their adaptation into direction and magnitude in a rigorous manner. MAP normalizes the pre-trained weights, learns a directional update, and introduces two scalar coefficients to independently scale the magnitude of the base and update vectors. This design enables more interpretable and flexible adaptation, and can be seamlessly integrated into existing PEFT methods. Extensive experiments show that MAP significantly improves performance when coupling with existing methods, offering a simple yet powerful enhancement to existing PEFT methods. Given the universality and simplicity of MAP, we hope it can serve as a default setting for designing future PEFT methods.

[Arxiv](https://arxiv.org/abs/2505.23094)