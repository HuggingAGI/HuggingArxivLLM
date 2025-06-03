# # **Zoom-Refine：通过局部放大与自我优化提升高分辨率多模态理解能力**
Zoom-Refine：通过局部放大与自我优化提升高分辨率多模态理解能力

发布时间：2025年06月02日

`LLM应用` `人工智能` `计算机视觉`

> Zoom-Refine: Boosting High-Resolution Multimodal Understanding via Localized Zoom and Self-Refinement

# 摘要

> 多模态大型语言模型（MLLM）在处理高分辨率图像时常常面临挑战，尤其是在需要精细细节的复杂视觉理解任务中。我们提出了一种无训练的创新方法——Zoom-Refine，专为提升MLLM在这一领域的表现而设计。Zoom-Refine通过‘局部放大’和‘自我优化’两个步骤协同工作。首先，‘局部放大’阶段利用MLLM生成初步响应，并通过预测边界框来识别与任务最相关的图像区域。随后，在‘自我优化’阶段，Zoom-Refine将高分辨率裁剪区域的精细细节与初步推理相结合，重新评估并优化响应。这种方法充分发挥了MLLM在空间定位、上下文推理和比较分析方面的能力，无需额外训练或外部专家支持。实验结果表明，Zoom-Refine在两个高分辨率多模态基准测试中表现优异。代码可在\href{https://github.com/xavier-yu114/Zoom-Refine}{\color{magenta}github.com/xavier-yu114/Zoom-Refine}获取。

> Multimodal Large Language Models (MLLM) often struggle to interpret high-resolution images accurately, where fine-grained details are crucial for complex visual understanding. We introduce Zoom-Refine, a novel training-free method that enhances MLLM capabilities to address this issue. Zoom-Refine operates through a synergistic process of \textit{Localized Zoom} and \textit{Self-Refinement}. In the \textit{Localized Zoom} step, Zoom-Refine leverages the MLLM to provide a preliminary response to an input query and identifies the most task-relevant image region by predicting its bounding box coordinates. During the \textit{Self-Refinement} step, Zoom-Refine then integrates fine-grained details from the high-resolution crop (identified by \textit{Localized Zoom}) with its initial reasoning to re-evaluate and refine its preliminary response. Our method harnesses the MLLM's inherent capabilities for spatial localization, contextual reasoning and comparative analysis without requiring additional training or external experts. Comprehensive experiments demonstrate the efficacy of Zoom-Refine on two challenging high-resolution multimodal benchmarks. Code is available at \href{https://github.com/xavier-yu114/Zoom-Refine}{\color{magenta}github.com/xavier-yu114/Zoom-Refine}

[Arxiv](https://arxiv.org/abs/2506.01663)