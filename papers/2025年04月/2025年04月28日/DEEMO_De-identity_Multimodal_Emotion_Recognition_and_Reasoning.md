# DEEMO：基于多模态情感识别与推理的匿名化方法

发布时间：2025年04月28日

`LLM应用` `情感计算` `多模态`

> DEEMO: De-identity Multimodal Emotion Recognition and Reasoning

# 摘要

> 情感理解是一项关键而富有挑战性的任务。现有的大多数方法严重依赖于涉及身份的信息，例如面部表情和语音，这引发了对个人隐私的担忧。为了解决这一问题，我们提出了一个名为“去身份化多模态情感识别与推理”（DEEMO）的新型任务，旨在通过去身份化的视频和音频输入实现情感理解。DEEMO数据集包含两个子集：DEEMO-NFBL，其中包括丰富的非面部肢体语言（NFBL）注释；DEEMO-MER，这是一个用于基于无身份线索的多模态情感识别与推理的指令数据集。这种设计支持在不泄露身份隐私的前提下进行情感理解。此外，我们提出了DEEMO-LLaMA，这是一种多模态大型语言模型（MLLM），它整合了去身份化的音频、视频和文本信息，以增强情感识别和推理能力。大量实验表明，DEEMO-LLaMA在两项任务中均达到了最先进的性能，显著超越现有的MLLM，实现了74.49%的识别准确率和74.45%的F1分数，在去身份化情感推理方面达到了6.20的线索重叠和7.66的标签重叠。我们的工作通过推进隐私保护的情感理解和促进负责任的情感计算，为伦理AI做出了贡献。

> Emotion understanding is a critical yet challenging task. Most existing approaches rely heavily on identity-sensitive information, such as facial expressions and speech, which raises concerns about personal privacy. To address this, we introduce the De-identity Multimodal Emotion Recognition and Reasoning (DEEMO), a novel task designed to enable emotion understanding using de-identified video and audio inputs. The DEEMO dataset consists of two subsets: DEEMO-NFBL, which includes rich annotations of Non-Facial Body Language (NFBL), and DEEMO-MER, an instruction dataset for Multimodal Emotion Recognition and Reasoning using identity-free cues. This design supports emotion understanding without compromising identity privacy. In addition, we propose DEEMO-LLaMA, a Multimodal Large Language Model (MLLM) that integrates de-identified audio, video, and textual information to enhance both emotion recognition and reasoning. Extensive experiments show that DEEMO-LLaMA achieves state-of-the-art performance on both tasks, outperforming existing MLLMs by a significant margin, achieving 74.49% accuracy and 74.45% F1-score in de-identity emotion recognition, and 6.20 clue overlap and 7.66 label overlap in de-identity emotion reasoning. Our work contributes to ethical AI by advancing privacy-preserving emotion understanding and promoting responsible affective computing.

[Arxiv](https://arxiv.org/abs/2504.19549)