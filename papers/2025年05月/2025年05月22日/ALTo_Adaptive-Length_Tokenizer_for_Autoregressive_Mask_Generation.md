# # **自适应长度分词器ALTo用于自回归掩码生成**

发布时间：2025年05月22日

`LLM理论` `计算机视觉` `图像处理`

> ALTo: Adaptive-Length Tokenizer for Autoregressive Mask Generation

# 摘要

> 尽管人类能够根据视觉对象的复杂性灵活分配注意力，轻松完成绘制，现有的多模态大型语言模型（MLLMs）却受限于 rigid token representations。为突破这一限制，我们提出了 ALTo，一种用于自回归掩码生成的自适应长度tokenizer。为此，我们设计了一种新型 token 长度预测器，并结合长度正则化项和可微分的 token 分块策略。我们进一步构建了 ALToLLM，使其与 MLLM 无缝集成。通过组相对策略优化（GRPO），实现了掩码质量和效率之间的权衡。实验表明，ALToLLM 在 popular segmentation benchmarks 上实现了 state-of-the-art 性能，同时具备自适应 token 成本。代码和模型可在 https://github.com/yayafengzi/ALToLLM 获取。

> While humans effortlessly draw visual objects and shapes by adaptively allocating attention based on their complexity, existing multimodal large language models (MLLMs) remain constrained by rigid token representations. Bridging this gap, we propose ALTo, an adaptive length tokenizer for autoregressive mask generation. To achieve this, a novel token length predictor is designed, along with a length regularization term and a differentiable token chunking strategy. We further build ALToLLM that seamlessly integrates ALTo into MLLM. Preferences on the trade-offs between mask quality and efficiency is implemented by group relative policy optimization (GRPO). Experiments demonstrate that ALToLLM achieves state-of-the-art performance with adaptive token cost on popular segmentation benchmarks. Code and models are released at https://github.com/yayafengzi/ALToLLM.

[Arxiv](https://arxiv.org/abs/2505.16495)