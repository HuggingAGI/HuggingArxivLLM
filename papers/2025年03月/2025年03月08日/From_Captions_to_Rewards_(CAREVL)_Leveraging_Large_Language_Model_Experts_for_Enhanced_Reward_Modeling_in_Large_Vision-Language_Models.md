# 字幕到奖励（CAREVL）：借助大型语言模型专家优化大型视觉-语言模型的奖励建模

发布时间：2025年03月08日

`LLM应用` `视觉语言模型` `多模态处理`

> From Captions to Rewards (CAREVL): Leveraging Large Language Model Experts for Enhanced Reward Modeling in Large Vision-Language Models

# 摘要

> 对齐大型视觉语言模型（LVLMs）与人类偏好面临挑战，主要由于缺乏细粒度、高质量且无需标注的多模态偏好数据。现有基于直接蒸馏的方法在处理低置信度数据时表现不佳，导致效果受限。为此，我们提出CAREVL，一种创新的偏好奖励建模方法，能够可靠地利用高、低置信度数据。首先，一组辅助专家模型（文本奖励模型）巧妙地利用图像字幕作为弱监督信号，筛选出高置信度数据。这些数据随后用于微调LVLM。其次，低置信度数据被用于生成多样化偏好样本，这些样本经过评分和筛选，构建可靠的选中-拒绝样本对，供进一步训练使用。CAREVL在VL-RewardBench和MLLM-as-a-Judge基准测试中超越了传统蒸馏方法，证明了其有效性。代码即将发布。

> Aligning large vision-language models (LVLMs) with human preferences is challenging due to the scarcity of fine-grained, high-quality, and multimodal preference data without human annotations. Existing methods relying on direct distillation often struggle with low-confidence data, leading to suboptimal performance. To address this, we propose CAREVL, a novel method for preference reward modeling by reliably using both high- and low-confidence data. First, a cluster of auxiliary expert models (textual reward models) innovatively leverages image captions as weak supervision signals to filter high-confidence data. The high-confidence data are then used to fine-tune the LVLM. Second, low-confidence data are used to generate diverse preference samples using the fine-tuned LVLM. These samples are then scored and selected to construct reliable chosen-rejected pairs for further training. CAREVL achieves performance improvements over traditional distillation-based methods on VL-RewardBench and MLLM-as-a-Judge benchmark, demonstrating its effectiveness. The code will be released soon.

[Arxiv](https://arxiv.org/abs/2503.06260)