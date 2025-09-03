# 基于相关全景图的全方位空间建模

发布时间：2025年09月02日

`LLM应用` `交通运输`

> Omnidirectional Spatial Modeling from Correlated Panoramas

# 摘要

> 全向场景理解对具身AI、自动驾驶、沉浸式环境等多种下游应用至关重要，但360°图像中的几何畸变与复杂空间关系使其颇具挑战。现有全向方法仅在单帧内实现场景理解，却忽略了跨帧相关的全景图。为此，我们提出	extbf{CFpano}——	extbf{首个}专注于整体360°场景中跨帧相关全景图视觉问答的基准数据集。该数据集包含2700余张图像及8000多个问答对，问题类型涵盖选择题与开放式VQA。基于CFpano，我们进一步提出\methodname：这是一款通过群体相对策略优化（GRPO）及定制奖励函数微调的多模态大语言模型（MLLM），旨在实现跨帧相关全景图的稳健一致推理。我们利用CFpano对现有多模态大语言模型展开基准测试，结果显示\methodname在选择题与开放式VQA任务中均达到最先进水平，在所有主要推理类别上均超越强基线，整体性能	extbf{提升5.37\%}。我们的分析验证了GRPO的有效性，并为全景场景理解树立了新基准。

> Omnidirectional scene understanding is vital for various downstream applications, such as embodied AI, autonomous driving, and immersive environments, yet remains challenging due to geometric distortion and complex spatial relations in 360° imagery. Existing omnidirectional methods achieve scene understanding within a single frame while neglecting cross-frame correlated panoramas. To bridge this gap, we introduce \textbf{CFpano}, the \textbf{first} benchmark dataset dedicated to cross-frame correlated panoramas visual question answering in the holistic 360° scenes. CFpano consists of over 2700 images together with over 8000 question-answer pairs, and the question types include both multiple choice and open-ended VQA. Building upon our CFpano, we further present \methodname, a multi-modal large language model (MLLM) fine-tuned with Group Relative Policy Optimization (GRPO) and a set of tailored reward functions for robust and consistent reasoning with cross-frame correlated panoramas. Benchmark experiments with existing MLLMs are conducted with our CFpano. The experimental results demonstrate that \methodname achieves state-of-the-art performance across both multiple-choice and open-ended VQA tasks, outperforming strong baselines on all major reasoning categories (\textbf{+5.37\%} in overall performance). Our analyses validate the effectiveness of GRPO and establish a new benchmark for panoramic scene understanding.

[Arxiv](https://arxiv.org/abs/2509.02164)