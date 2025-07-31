# # 适用于语音助手的轻量级噪声鲁棒语音活动检测器

发布时间：2025年07月29日

`其他` `语音处理` `AIoT`

> Tiny Noise-Robust Voice Activity Detector for Voice Assistants

# 摘要

> 语音活动检测（VAD）在噪声环境下的准确性一直是语音处理领域的难题。准确的VAD对于自动语音识别、语音转文本、对话式代理等应用至关重要，因为噪声会严重影响这些任务的性能。现代应用中，语音助手通常安装在人工智能物联网（AIoT）设备上，如手机、智能眼镜、耳机等，这些设备的语音信号通常包含背景噪声。因此，VAD模块必须保持轻量化，以满足实际设备的限制。现有的模型在处理各种声学环境下的低信噪比问题时往往表现不佳。一个简单的VAD通常能在干净的环境中检测到人声，但在噪声环境下则难以准确检测。我们提出了一种噪声鲁棒的VAD，它包含了一个轻量化的VAD，并增加了数据预处理和后处理模块来处理背景噪声。这种方法显著提高了噪声环境下的VAD准确性，而无需使用更大的模型或进行微调。实验结果表明，与基线方法相比，我们的方法在高背景噪声干扰的环境中取得了显著改进。此外，这种改进的VAD还增强了对干净语音的检测效果。

> Voice Activity Detection (VAD) in the presence of background noise remains a challenging problem in speech processing. Accurate VAD is essential in automatic speech recognition, voice-to-text, conversational agents, etc, where noise can severely degrade the performance. A modern application includes the voice assistant, specially mounted on Artificial Intelligence of Things (AIoT) devices such as cell phones, smart glasses, earbuds, etc, where the voice signal includes background noise. Therefore, VAD modules must remain light-weight due to their practical on-device limitation. The existing models often struggle with low signal-to-noise ratios across diverse acoustic environments. A simple VAD often detects human voice in a clean environment, but struggles to detect the human voice in noisy conditions. We propose a noise-robust VAD that comprises a light-weight VAD, with data pre-processing and post-processing added modules to handle the background noise. This approach significantly enhances the VAD accuracy in noisy environments and requires neither a larger model, nor fine-tuning. Experimental results demonstrate that our approach achieves a notable improvement compared to baselines, particularly in environments with high background noise interference. This modified VAD additionally improving clean speech detection.

[Arxiv](https://arxiv.org/abs/2507.22157)