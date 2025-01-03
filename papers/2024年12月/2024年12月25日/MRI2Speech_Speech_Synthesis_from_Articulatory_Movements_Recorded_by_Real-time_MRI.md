# MRI2Speech: 基于实时MRI记录的发音动作的语音合成

发布时间：2024年12月25日

`其他

理由：这篇论文主要讨论的是实时MRI（rtMRI）语音合成模型的改进方法，涉及到多模态自监督AV-HuBERT模型和基于流的时长预测器等技术。虽然使用了自监督学习模型，但整体内容与Agent、RAG、LLM应用或LLM理论没有直接关联。因此，将其分类为“其他”更为合适。` `语音合成`

> MRI2Speech: Speech Synthesis from Articulatory Movements Recorded by Real-time MRI

# 摘要

> # 摘要
以往的实时MRI（rtMRI）语音合成模型过度依赖嘈杂的真实语音，直接在真实梅尔频谱图上计算损失会导致语音内容与MRI噪声混淆，影响可懂度。我们提出了一种创新方法，利用多模态自监督AV-HuBERT模型从rtMRI中预测文本，并引入基于流的时长预测器，实现说话人特定的对齐。预测的文本和时长随后被语音解码器用于合成任意新声音的对齐语音。我们在两个数据集上进行了广泛实验，验证了该方法对未见说话人的泛化能力。通过掩盖rtMRI视频的部分内容，我们评估了不同发音器官对文本预测的影响。我们的方法在USC-TIMIT MRI语料库上取得了15.18%的词错误率（WER），显著超越了现有技术。语音样本请访问url{https://mri2speech.github.io/MRI2Speech/}。

> Previous real-time MRI (rtMRI)-based speech synthesis models depend heavily on noisy ground-truth speech. Applying loss directly over ground truth mel-spectrograms entangles speech content with MRI noise, resulting in poor intelligibility. We introduce a novel approach that adapts the multi-modal self-supervised AV-HuBERT model for text prediction from rtMRI and incorporates a new flow-based duration predictor for speaker-specific alignment. The predicted text and durations are then used by a speech decoder to synthesize aligned speech in any novel voice. We conduct thorough experiments on two datasets and demonstrate our method's generalization ability to unseen speakers. We assess our framework's performance by masking parts of the rtMRI video to evaluate the impact of different articulators on text prediction. Our method achieves a $15.18\%$ Word Error Rate (WER) on the USC-TIMIT MRI corpus, marking a huge improvement over the current state-of-the-art. Speech samples are available at url{https://mri2speech.github.io/MRI2Speech/}

[Arxiv](https://arxiv.org/abs/2412.18836)