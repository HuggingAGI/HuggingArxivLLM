# # SepALM：音频语言模型助力鲁棒语音分离的纠错器

发布时间：2025年05月06日

`LLM应用` `音频处理` `语音技术`

> SepALM: Audio Language Models Are Error Correctors for Robust Speech Separation

# 摘要

> 当前语音分离技术在处理冗长的混合音频波形时表现出色，但在嘈杂、混响等复杂现实环境中，往往难以避免失真或伪影的产生。为突破这一局限，我们提出了SepALM这一创新方法，通过在初步分离后，借助音频语言模型（ALMs）在文本域内对语音进行修复与重合成。SepALM由分离器、校正器、合成器和对齐器四大核心组件构成。通过引入基于ALM的端到端错误校正机制，我们有效降低了错误累积的风险，并成功绕过了传统方法在结合自动语音识别（ASR）与大型语言模型（LLMs）时常见的优化难题。此外，我们还开发了链式思维（CoT）提示和知识蒸馏技术，以优化ALM的推理与训练流程。实验结果证实，SepALM不仅显著提升了语音分离的精度，更在新型声学环境中的适应性方面实现了重大突破。

> While contemporary speech separation technologies adeptly process lengthy mixed audio waveforms, they are frequently challenged by the intricacies of real-world environments, including noisy and reverberant settings, which can result in artifacts or distortions in the separated speech. To overcome these limitations, we introduce SepALM, a pioneering approach that employs audio language models (ALMs) to rectify and re-synthesize speech within the text domain following preliminary separation. SepALM comprises four core components: a separator, a corrector, a synthesizer, and an aligner. By integrating an ALM-based end-to-end error correction mechanism, we mitigate the risk of error accumulation and circumvent the optimization hurdles typically encountered in conventional methods that amalgamate automatic speech recognition (ASR) with large language models (LLMs). Additionally, we have developed Chain-of-Thought (CoT) prompting and knowledge distillation techniques to facilitate the reasoning and training processes of the ALM. Our experiments substantiate that SepALM not only elevates the precision of speech separation but also markedly bolsters adaptability in novel acoustic environments.

[Arxiv](https://arxiv.org/abs/2505.03273)