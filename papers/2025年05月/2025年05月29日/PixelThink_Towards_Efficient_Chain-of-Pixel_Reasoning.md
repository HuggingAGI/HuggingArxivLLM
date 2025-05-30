# PixelThink：探索高效像素链式推理方法

发布时间：2025年05月29日

`LLM应用` `计算机视觉`

> PixelThink: Towards Efficient Chain-of-Pixel Reasoning

# 摘要

> 现有推理分割方法通常基于图像-文本对及其掩码标签微调多模态大语言模型（MLLMs）。然而，这些方法在分布外场景下表现有限，缺乏显式推理过程。尽管近期研究通过群体相对策略优化（GRPO）强化学习提升推理能力，但它们常陷入过度思考，生成冗长的推理链，导致计算成本升高且难以控制推理质量。为解决这一问题，我们提出PixelThink，一种结合外部任务难度估计和内部模型不确定性测量的简单有效方案，可在强化学习框架内调节推理生成。模型根据场景复杂度和预测置信度自动压缩推理长度。为支持全面评估，我们引入了ReasonSeg-Diff扩展基准，包含推理参考和难度评分，并设计了一系列指标来共同评估分割精度、推理质量和效率。实验结果表明，PixelThink显著提升了推理效率和整体分割性能。这项研究为高效且可解释的多模态理解提供了新视角。代码和模型将公开发布。

> Existing reasoning segmentation approaches typically fine-tune multimodal large language models (MLLMs) using image-text pairs and corresponding mask labels. However, they exhibit limited generalization to out-of-distribution scenarios without an explicit reasoning process. Although recent efforts leverage reinforcement learning through group-relative policy optimization (GRPO) to enhance reasoning ability, they often suffer from overthinking - producing uniformly verbose reasoning chains irrespective of task complexity. This results in elevated computational costs and limited control over reasoning quality. To address this problem, we propose PixelThink, a simple yet effective scheme that integrates externally estimated task difficulty and internally measured model uncertainty to regulate reasoning generation within a reinforcement learning paradigm. The model learns to compress reasoning length in accordance with scene complexity and predictive confidence. To support comprehensive evaluation, we introduce ReasonSeg-Diff, an extended benchmark with annotated reasoning references and difficulty scores, along with a suite of metrics designed to assess segmentation accuracy, reasoning quality, and efficiency jointly. Experimental results demonstrate that the proposed approach improves both reasoning efficiency and overall segmentation performance. Our work contributes novel perspectives towards efficient and interpretable multimodal understanding. The code and model will be publicly available.

[Arxiv](https://arxiv.org/abs/2505.23727)