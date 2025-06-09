# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月05日

`LLM应用

摘要讨论了将语音输入与大型语言模型集成的挑战，并提出了一种基于向量化量化的解决方案，以实现音频信号与LLM的离散化处理。这属于将LLM应用于自动语音识别领域的具体应用，因此归类为LLM应用。` `语音技术` `自动语音识别`

> Bridging the Modality Gap: Softly Discretizing Audio Representation for LLM-based Automatic Speech Recognition

# 摘要

> 语音输入与大型语言模型 (LLMs) 集成面临一个主要挑战：音频数据的连续性与 LLM 的离散令牌范式不兼容。为解决这一问题，我们提出了一种基于向量化量化 (VQ) 的方法，将其融入到 LLM 驱动的自动语音识别 (ASR) 系统中。通过利用 LLM 的嵌入表作为 VQ 代码本，该模块实现了音频编码器输出的连续表示与 LLM 输入的离散化对齐，使 LLM 能够处理更贴合语言结构的离散化音频信号。进一步地，我们通过动态更新代码本并进行加权求和，实现了音频表示的 "软离散化"。实验结果表明，相较于传统基于 LLM 的 ASR 方法，我们的方案在域外条件下表现尤为突出。这项研究突显了软离散化技术在跨模态桥梁中的巨大潜力，特别是在 LLM 驱动的 ASR 领域。

> One challenge of integrating speech input with large language models (LLMs) stems from the discrepancy between the continuous nature of audio data and the discrete token-based paradigm of LLMs. To mitigate this gap, we propose a method for integrating vector quantization (VQ) into LLM-based automatic speech recognition (ASR). Using the LLM embedding table as the VQ codebook, the VQ module aligns the continuous representations from the audio encoder with the discrete LLM inputs, enabling the LLM to operate on a discretized audio representation that better reflects the linguistic structure. We further create a soft "discretization" of the audio representation by updating the codebook and performing a weighted sum over the codebook embeddings. Empirical results demonstrate that our proposed method significantly improves upon the LLM-based ASR baseline, particularly in out-of-domain conditions. This work highlights the potential of soft discretization as a modality bridge in LLM-based ASR.

[Arxiv](https://arxiv.org/abs/2506.05706)