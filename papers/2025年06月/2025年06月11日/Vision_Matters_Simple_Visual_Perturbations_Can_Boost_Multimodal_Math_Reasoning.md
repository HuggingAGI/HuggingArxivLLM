# 视觉很重要：简单的视觉干扰可以显著提升多模态数学推理能力

发布时间：2025年06月11日

`LLM应用` `多模态` `计算机视觉`

> Vision Matters: Simple Visual Perturbations Can Boost Multimodal Math Reasoning

# 摘要

> 尽管多模态大型语言模型（MLLMs）发展迅猛，但它们对视觉处理的重要性仍存在明显忽视。在一项简单却极具启发性的实验中，我们惊奇地发现：仅依赖语言的模型在获得图像描述后，能够达到甚至超越使用原始视觉输入的MLLMs的性能。这表明，当前MLLMs虽能生成准确的视觉描述，却未能在推理过程中有效整合这些信息。基于这一发现，我们提出了一种无需算法修改或额外训练数据的视觉扰动框架，以增强感知鲁棒性。我们的方法引入了三种针对性扰动：干扰项拼接、优势保持混合和随机旋转，这些扰动可轻松整合到SFT、DPO和GRPO等现有后训练流程中。通过在多个数据集上的广泛实验，我们展示了数学推理性能的一致性提升，其增益与算法更改相当。此外，通过使用视觉扰动训练Qwen2.5-VL-7B，我们在开源7B强化学习微调模型中实现了具有竞争力的性能。通过全面的消融研究，我们分析了不同扰动策略的有效性，发现每种扰动类型在视觉推理的不同方面都有其独特贡献。我们的研究结果凸显了视觉扰动在多模态数学推理中的关键作用：更优秀的推理始于更优秀的感知。我们的代码可在https://github.com/YutingLi0606/Vision-Matters获取。

> Despite the rapid progress of multimodal large language models (MLLMs), they have largely overlooked the importance of visual processing. In a simple yet revealing experiment, we interestingly find that language-only models, when provided with image captions, can achieve comparable or even better performance than MLLMs that consume raw visual inputs. This suggests that current MLLMs may generate accurate visual descriptions but fail to effectively integrate them during reasoning. Motivated by this, we propose a simple visual perturbation framework that enhances perceptual robustness without requiring algorithmic modifications or additional training data. Our approach introduces three targeted perturbations: distractor concatenation, dominance-preserving mixup, and random rotation, that can be easily integrated into existing post-training pipelines including SFT, DPO, and GRPO. Through extensive experiments across multiple datasets, we demonstrate consistent improvements in mathematical reasoning performance, with gains comparable to those achieved through algorithmic changes. Additionally, we achieve competitive performance among open-source 7B RL-tuned models by training Qwen2.5-VL-7B with visual perturbation. Through comprehensive ablation studies, we analyze the effectiveness of different perturbation strategies, revealing that each perturbation type contributes uniquely to different aspects of visual reasoning. Our findings highlight the critical role of visual perturbation in multimodal mathematical reasoning: better reasoning begins with better seeing. Our code is available at https://github.com/YutingLi0606/Vision-Matters.

[Arxiv](https://arxiv.org/abs/2506.09736)