# # Kimi-VL技术报告

发布时间：2025年04月10日

`LLM应用` `视觉语言模型` `人工智能`

> Kimi-VL Technical Report

# 摘要

> 我们推出Kimi-VL，一款高效开源的混合专家（MoE）视觉语言模型（VLM），具备高级多模态推理、长上下文理解及强大代理能力，其语言解码器仅激活28亿参数（Kimi-VL-A3B）。作为通用型VLM，Kimi-VL在多轮对话任务（如OSWorld）中表现卓越，与旗舰模型并驾齐驱。它还在多项具挑战性的视觉语言任务中展现出色，涵盖大学水平的图像与视频理解、OCR、数学推理及多图理解。对比评估显示，Kimi-VL与GPT-4o-mini、Qwen2.5-VL-7B、Gemma-3-12B-IT等先进VLM比肩，同时在多个关键领域超越GPT-4o。Kimi-VL在长上下文处理与清晰感知方面亦有突破。凭借128K扩展上下文窗口，它能高效处理各类长输入，在LongVideoBench和MMLongBench-Doc上分别取得64.5和35.1的优异成绩。其原生分辨率视觉编码器MoonViT赋予其识别超高清视觉输入的能力，在InfoVQA和ScreenSpot-Pro上分别达到83.2和34.5分，同时保持低计算成本。基于Kimi-VL，我们开发出长思维增强版：Kimi-VL-Thinking。该模型通过长链式思维（CoT）监督微调（SFT）和强化学习（RL）优化，展现卓越的长期推理能力。在MMMU、MathVision和MathVista上分别取得61.7、36.8和71.3分，同时保持28亿激活的LLM参数规模，树立高效多模态思考模型的新标杆。代码和模型已开源，访问地址：https://github.com/MoonshotAI/Kimi-VL。

> We present Kimi-VL, an efficient open-source Mixture-of-Experts (MoE) vision-language model (VLM) that offers advanced multimodal reasoning, long-context understanding, and strong agent capabilities - all while activating only 2.8B parameters in its language decoder (Kimi-VL-A3B). Kimi-VL demonstrates strong performance across challenging domains: as a general-purpose VLM, Kimi-VL excels in multi-turn agent tasks (e.g., OSWorld), matching flagship models. Furthermore, it exhibits remarkable capabilities across diverse challenging vision language tasks, including college-level image and video comprehension, OCR, mathematical reasoning, and multi-image understanding. In comparative evaluations, it effectively competes with cutting-edge efficient VLMs such as GPT-4o-mini, Qwen2.5-VL-7B, and Gemma-3-12B-IT, while surpassing GPT-4o in several key domains. Kimi-VL also advances in processing long contexts and perceiving clearly. With a 128K extended context window, Kimi-VL can process diverse long inputs, achieving impressive scores of 64.5 on LongVideoBench and 35.1 on MMLongBench-Doc. Its native-resolution vision encoder, MoonViT, further allows it to see and understand ultra-high-resolution visual inputs, achieving 83.2 on InfoVQA and 34.5 on ScreenSpot-Pro, while maintaining lower computational cost for common tasks. Building upon Kimi-VL, we introduce an advanced long-thinking variant: Kimi-VL-Thinking. Developed through long chain-of-thought (CoT) supervised fine-tuning (SFT) and reinforcement learning (RL), this model exhibits strong long-horizon reasoning capabilities. It achieves scores of 61.7 on MMMU, 36.8 on MathVision, and 71.3 on MathVista while maintaining the compact 2.8B activated LLM parameters, setting a new standard for efficient multimodal thinking models. Code and models are publicly accessible at https://github.com/MoonshotAI/Kimi-VL.

[Arxiv](https://arxiv.org/abs/2504.07491)