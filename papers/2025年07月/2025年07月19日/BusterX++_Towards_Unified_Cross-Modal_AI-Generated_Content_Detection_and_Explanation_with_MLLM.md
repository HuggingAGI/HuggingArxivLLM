# BusterX++: 面向基于MLLM的统一跨模态AI生成内容检测与解释

发布时间：2025年07月19日

`LLM应用` `媒体生成`

> BusterX++: Towards Unified Cross-Modal AI-Generated Content Detection and Explanation with MLLM

# 摘要

> 生成式AI的突破显著提升了图像和视频合成能力，同时也加剧了虚假信息的传播风险。针对这一挑战，检测技术从传统方法升级为多模态大语言模型（MLLMs），在识别合成媒体时更具透明度和可解释性。然而，现有检测系统受限于单模态设计，无法有效应对多格式合成内容。为此，我们推出了	extbf{BusterX++}，首个专为跨模态合成媒体检测设计的框架。通过创新的强化学习（RL）后训练策略，结合多阶段训练、思考奖励和混合推理，BusterX++实现了稳定且显著的性能提升。为全面评估性能，我们还构建了	extbf{GenBuster++}，一个基于前沿生成技术的跨模态基准测试，包含4,000张图像和视频片段，由专家精心筛选，确保高质量和实际应用价值。实验结果充分验证了我们方法的有效性和通用性。

> Recent advances in generative AI have dramatically improved image and video synthesis capabilities, significantly increasing the risk of misinformation through sophisticated fake content. In response, detection methods have evolved from traditional approaches to multimodal large language models (MLLMs), offering enhanced transparency and interpretability in identifying synthetic media. However, current detection systems remain fundamentally limited by their single-modality design. These approaches analyze images or videos separately, making them ineffective against synthetic content that combines multiple media formats. To address these challenges, we introduce \textbf{BusterX++}, a novel framework designed specifically for cross-modal detection and explanation of synthetic media. Our approach incorporates an advanced reinforcement learning (RL) post-training strategy that eliminates cold-start. Through Multi-stage Training, Thinking Reward, and Hybrid Reasoning, BusterX++ achieves stable and substantial performance improvements. To enable comprehensive evaluation, we also present \textbf{GenBuster++}, a cross-modal benchmark leveraging state-of-the-art image and video generation techniques. This benchmark comprises 4,000 images and video clips, meticulously curated by human experts using a novel filtering methodology to ensure high quality, diversity, and real-world applicability. Extensive experiments demonstrate the effectiveness and generalizability of our approach.

[Arxiv](https://arxiv.org/abs/2507.14632)