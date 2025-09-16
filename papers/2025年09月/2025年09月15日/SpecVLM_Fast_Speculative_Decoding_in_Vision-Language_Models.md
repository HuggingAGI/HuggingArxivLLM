# SpecVLM：视觉-语言模型的快速推测性解码

发布时间：2025年09月15日

`LLM应用` `基础理论`

> SpecVLM: Fast Speculative Decoding in Vision-Language Models

# 摘要

> 推测解码是加速自回归大型语言模型（LLMs）的强大手段，但将其直接应用于视觉语言模型（VLMs）时，却面临独特的系统限制：预填充阶段中，视觉token占主导地位，其数量随图像分辨率和视频长度增加而增多，导致计算量和内存（尤其是键值（KV）缓存）显著膨胀。为此，我们研究了VLMs的推测解码并提出SpecVLM——一个实用系统，它（1）构建了强大的EAGLE-2风格基线EagleVLM，相比完整自回归推理实现1.5-2.3倍的端到端加速；（2）通过弹性视觉压缩器进一步加速VLM推理——该压缩器能自适应选择剪枝、池化、卷积和重采样原语，在每个输入的浮点运算数/参数与准确性之间取得平衡。为避免构建昂贵的离线蒸馏语料库，我们提出在线logit蒸馏协议：利用实时教师logit和倒数第二层特征训练草稿模型，并结合交叉熵与Smooth L1损失函数，在保持计算效率的同时省去了存储和预处理步骤。该协议还揭示了一种训练时缩放效应：在线训练时间越长，草稿模型的平均接受长度就会单调增加，从而提升推测效率。实验结果显示，SpecVLM实现了进一步加速，在LLaVA和MMMU数据集上，经过5个epoch训练后，端到端加速比最终达到2.5-2.9倍，且在不同分辨率和任务难度下表现稳定，同时保持了目标模型的输出分布（即无损解码）。我们的代码开源于https://github.com/haiduo/SpecVLM。

> Speculative decoding is a powerful way to accelerate autoregressive large language models (LLMs), but directly porting it to vision-language models (VLMs) faces unique systems constraints: the prefill stage is dominated by visual tokens whose count scales with image resolution and video length, inflating both compute and memory, especially the key-value (KV) cache. We study speculative decoding for VLMs and introduce SpecVLM, a practical system that (1) establishes a strong EAGLE-2-style baseline, EagleVLM, delivering 1.5--2.3x end-to-end speedups over full autoregressive inference, and (2) further accelerates VLM inference with an elastic visual compressor that adaptively selects among pruning, pooling, convolution, and resampler primitives to balance FLOPs/parameters and accuracy per input. To avoid costly offline distillation corpora, we propose an online-logit distillation protocol that trains the draft model with on-the-fly teacher logits and penultimate features using a combined cross-entropy and Smooth L1 objective, eliminating storage and preprocessing while remaining compute-efficient. This protocol reveals a training-time scaling effect: longer online training monotonically increases the draft model's average accepted length, improving speculative efficiency. Empirically, SpecVLM achieves additional acceleration, culminating in 2.5--2.9x end-to-end speedups within 5 epochs across LLaVA and MMMU, consistently over resolutions and task difficulties, while preserving the target model's output distribution (lossless decoding). Our code is available at https://github.com/haiduo/SpecVLM.

[Arxiv](https://arxiv.org/abs/2509.11815)