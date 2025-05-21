# 通过离散声学令牌去噪提升基于LLM的零样本TTS的抗噪声鲁棒性

发布时间：2025年05月19日

`LLM应用

理由：这篇论文将大型语言模型应用于文本到语音（TTS）系统，并提出了一种创新的方法来解决噪声音频提示导致的语音质量问题。具体来说，它结合了神经编解码器去噪器和LauraTTS模型，以提高在噪声环境下的语音质量。这种方法属于将LLM应用于实际任务中的改进和优化，因此归类为LLM应用。` `语音合成` `语音处理`

> Improving Noise Robustness of LLM-based Zero-shot TTS via Discrete Acoustic Token Denoising

# 摘要

> 基于大型语言模型 (LLM) 的零样本 TTS 方法在处理含噪声音频提示时，往往会导致语音质量下降。为解决这一问题，我们提出了一种创新的神经编解码器语音去噪器，并将其与 LauraTTS 模型相结合，打造了更具噪声鲁棒性的零样本 TTS 系统。我们的编解码器去噪器包含音频编解码器、令牌去噪器和嵌入优化器三个部分。其中，令牌去噪器能够从噪声中提取出干净的声学特征，为 LauraTTS 提供高质量的声学提示，从而合成出清晰的个性化语音或通过优化器生成干净的语音波形。实验结果表明，该编解码器去噪器不仅超越了现有语音增强方法，还使 LauraTTS 在噪声环境下的表现优于传统依赖额外增强模型的方案。

> Large language model (LLM) based zero-shot text-to-speech (TTS) methods tend to preserve the acoustic environment of the audio prompt, leading to degradation in synthesized speech quality when the audio prompt contains noise. In this paper, we propose a novel neural codec-based speech denoiser and integrate it with the advanced LLM-based TTS model, LauraTTS, to achieve noise-robust zero-shot TTS. The proposed codec denoiser consists of an audio codec, a token denoiser, and an embedding refiner. The token denoiser predicts the first two groups of clean acoustic tokens from the noisy ones, which can serve as the acoustic prompt for LauraTTS to synthesize high-quality personalized speech or be converted to clean speech waveforms through the embedding refiner and codec decoder. Experimental results show that our proposed codec denoiser outperforms state-of-the-art speech enhancement (SE) methods, and the proposed noise-robust LauraTTS surpasses the approach using additional SE models.

[Arxiv](https://arxiv.org/abs/2505.13830)