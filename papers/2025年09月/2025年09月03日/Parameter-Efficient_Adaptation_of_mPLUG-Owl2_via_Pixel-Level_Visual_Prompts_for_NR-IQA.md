# 基于像素级视觉提示的mPLUG-Owl2参数高效自适应：面向NR-IQA

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Parameter-Efficient Adaptation of mPLUG-Owl2 via Pixel-Level Visual Prompts for NR-IQA

# 摘要

> 本文提出一种新颖的参数高效自适应方法，用于无参考图像质量评估（NR-IQA），其核心是在像素空间优化视觉提示。不同于对多模态大型语言模型（MLLMs）进行全量微调，我们的方法最多仅训练60万参数（不足基础模型的0.01%），同时将基础模型完全冻结。推理时，这些视觉提示通过加法与图像融合，再由mPLUG-Owl2结合文本查询“评估图像的技术质量。”进行处理。在KADID-10k、KonIQ-10k和AGIQA-3k数据集上，针对合成、真实、AI生成等多种失真类型的评估显示，该方法性能媲美全量微调方法及专用NR-IQA模型，在KADID-10k上的SRCC达0.93。据我们所知，这是首次将像素空间视觉提示应用于NR-IQA的研究，为低级视觉任务提供了高效的MLLM自适应方案。源代码已公开，地址为https: // github. com/ yahya-ben/ mplug2-vp-for-nriqa 。

> In this paper, we propose a novel parameter-efficient adaptation method for No- Reference Image Quality Assessment (NR-IQA) using visual prompts optimized in pixel-space. Unlike full fine-tuning of Multimodal Large Language Models (MLLMs), our approach trains only 600K parameters at most (< 0.01% of the base model), while keeping the underlying model fully frozen. During inference, these visual prompts are combined with images via addition and processed by mPLUG-Owl2 with the textual query "Rate the technical quality of the image." Evaluations across distortion types (synthetic, realistic, AI-generated) on KADID- 10k, KonIQ-10k, and AGIQA-3k demonstrate competitive performance against full finetuned methods and specialized NR-IQA models, achieving 0.93 SRCC on KADID-10k. To our knowledge, this is the first work to leverage pixel-space visual prompts for NR-IQA, enabling efficient MLLM adaptation for low-level vision tasks. The source code is publicly available at https: // github. com/ yahya-ben/ mplug2-vp-for-nriqa .

[Arxiv](https://arxiv.org/abs/2509.03494)