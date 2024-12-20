# Prompt-A-Video：借助偏好对齐的 LLM 为您的视频扩散模型提供提示

发布时间：2024年12月19日

`LLM应用` `文本到视频模型`

> Prompt-A-Video: Prompt Your Video Diffusion Model via Preference-Aligned LLM

# 摘要

> 文本到视频模型借助对高质量文本 - 视频对的优化取得了非凡进步，其中文本提示对于决定输出视频的质量至关重要。然而，要获取理想的输出，往往需要多次修订和迭代推理来优化用户提供的提示。当前用于优化提示的自动方法在应用于文本到视频扩散模型时面临诸如模态不一致、成本差异和模型未知等难题。为应对这些问题，我们推出了一个基于 LLM 的提示适配框架，名为 Prompt - A - Video，它能够为特定的视频扩散模型精心打造以视频为核心、无需人工且符合偏好的提示。我们的方法包含一个精心构建的两阶段优化与对齐系统。首先，我们开展奖励引导的提示进化流程，自动创建最优提示池，并将其用于 LLM 的监督微调（SFT）。接着，运用多维奖励为 SFT 模型生成成对数据，然后采用直接偏好优化（DPO）算法进一步促进偏好对齐。通过大量的实验和对比分析，我们证实了 Prompt - A - Video 在各类生成模型中的有效性，彰显了其拓展视频生成边界的潜力。

> Text-to-video models have made remarkable advancements through optimization on high-quality text-video pairs, where the textual prompts play a pivotal role in determining quality of output videos. However, achieving the desired output often entails multiple revisions and iterative inference to refine user-provided prompts. Current automatic methods for refining prompts encounter challenges such as Modality-Inconsistency, Cost-Discrepancy, and Model-Unaware when applied to text-to-video diffusion models. To address these problem, we introduce an LLM-based prompt adaptation framework, termed as Prompt-A-Video, which excels in crafting Video-Centric, Labor-Free and Preference-Aligned prompts tailored to specific video diffusion model. Our approach involves a meticulously crafted two-stage optimization and alignment system. Initially, we conduct a reward-guided prompt evolution pipeline to automatically create optimal prompts pool and leverage them for supervised fine-tuning (SFT) of the LLM. Then multi-dimensional rewards are employed to generate pairwise data for the SFT model, followed by the direct preference optimization (DPO) algorithm to further facilitate preference alignment. Through extensive experimentation and comparative analyses, we validate the effectiveness of Prompt-A-Video across diverse generation models, highlighting its potential to push the boundaries of video generation.

[Arxiv](https://arxiv.org/abs/2412.15156)