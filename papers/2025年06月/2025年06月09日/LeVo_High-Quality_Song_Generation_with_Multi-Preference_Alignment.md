# LeVo：通过多偏好对齐实现高质量歌曲生成

发布时间：2025年06月09日

`LLM应用`

> LeVo: High-Quality Song Generation with Multi-Preference Alignment

# 摘要

> 大型语言模型 (LLMs) 和音频语言模型的最新进展显著提升了音乐生成，尤其是在歌词到歌曲的生成方面。然而，现有方法在处理歌曲的复杂构成以及高质量数据稀缺性方面仍面临挑战，导致音质、音乐性、指令遵循以及人声与乐器和谐等方面存在局限。为了解决这些问题，我们提出了 LeVo，一个基于 LM 的框架，包含 LeLM 和音乐编解码器。LeLM 能够并行建模两种类型的令牌：混合令牌，代表人声与伴奏的结合音频，以实现人声与乐器的和谐；双轨令牌，分别编码人声和伴奏，用于高质量歌曲生成。它采用了两个解码器-only 变换器和模块化扩展训练策略，以防止不同令牌类型之间的干扰。为了进一步提升音乐性和指令遵循能力，我们引入了基于直接偏好优化 (DPO) 的多偏好对齐方法。该方法通过半自动数据构建过程和 DPO 后训练处理多样的人类偏好。实验结果表明，LeVo 在客观和主观指标上均显著优于现有方法。消融研究进一步验证了我们设计的有效性。音频示例可在 https://levo-demo.github.io/ 获取。


> Recent advances in large language models (LLMs) and audio language models have significantly improved music generation, particularly in lyrics-to-song generation. However, existing approaches still struggle with the complex composition of songs and the scarcity of high-quality data, leading to limitations in sound quality, musicality, instruction following, and vocal-instrument harmony. To address these challenges, we introduce LeVo, an LM-based framework consisting of LeLM and a music codec. LeLM is capable of parallelly modeling two types of tokens: mixed tokens, which represent the combined audio of vocals and accompaniment to achieve vocal-instrument harmony, and dual-track tokens, which separately encode vocals and accompaniment for high-quality song generation. It employs two decoder-only transformers and a modular extension training strategy to prevent interference between different token types. To further enhance musicality and instruction following, we introduce a multi-preference alignment method based on Direct Preference Optimization (DPO). This method handles diverse human preferences through a semi-automatic data construction process and DPO post-training. Experimental results demonstrate that LeVo consistently outperforms existing methods on both objective and subjective metrics. Ablation studies further justify the effectiveness of our designs. Audio examples are available at https://levo-demo.github.io/.

[Arxiv](https://arxiv.org/abs/2506.07520)