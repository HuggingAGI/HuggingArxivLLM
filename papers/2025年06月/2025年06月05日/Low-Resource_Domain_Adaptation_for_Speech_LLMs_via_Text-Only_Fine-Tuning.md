# 仅文本微调实现语音大语言模型的低资源领域适应研究

发布时间：2025年06月05日

`LLM应用` `语音识别`

> Low-Resource Domain Adaptation for Speech LLMs via Text-Only Fine-Tuning

# 摘要

> 近年来，自动语音识别技术通过投影方法将语音编码器与大型语言模型相结合，形成了性能卓越的Speech LLMs。然而，将这些模型应用于新领域仍具挑战性，尤其是在资源匮乏的场景下，难以获得成对的语音-文本数据。我们提出了一种仅基于目标领域文本的微调策略，无需额外的音频数据。为了保持语音与文本的对齐，我们在微调过程中引入了实时评估机制。实验结果表明，该方法在保持原领域性能的同时，实现了有效的领域自适应。在LibriSpeech、SlideSpeech和Medical数据集上的实验表明，我们的方法在语音识别性能上具有竞争力，与全语音-文本微调相比，性能下降幅度极小。此外，该方法还能提升模型对新领域的泛化能力，而不会导致灾难性遗忘，突显了仅基于文本的微调在资源匮乏场景下进行语音识别领域自适应的潜力。

> Recent advances in automatic speech recognition (ASR) have combined speech encoders with large language models (LLMs) through projection, forming Speech LLMs with strong performance. However, adapting them to new domains remains challenging, especially in low-resource settings where paired speech-text data is scarce. We propose a text-only fine-tuning strategy for Speech LLMs using unpaired target-domain text without requiring additional audio. To preserve speech-text alignment, we introduce a real-time evaluation mechanism during fine-tuning. This enables effective domain adaptation while maintaining source-domain performance. Experiments on LibriSpeech, SlideSpeech, and Medical datasets show that our method achieves competitive recognition performance, with minimal degradation compared to full audio-text fine-tuning. It also improves generalization to new domains without catastrophic forgetting, highlighting the potential of text-only fine-tuning for low-resource domain adaptation of ASR.

[Arxiv](https://arxiv.org/abs/2506.05671)