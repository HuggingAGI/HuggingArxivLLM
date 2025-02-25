# 白船-音频：打造端到端语音交互的统一框架

发布时间：2025年02月24日

`LLM应用` `音频处理` `语音交互`

> Baichuan-Audio: A Unified Framework for End-to-End Speech Interaction

# 摘要

> 我们重磅推出 Baichuan-Audio——一款集音频理解和生成于一体的端到端音频大语言模型。它搭载了独特的文本引导语音生成机制，让实时语音交互变得轻松自然。Baichuan-Audio 基于预训练的 ASR 模型，采用 12.5 Hz 帧率的多码本离散化技术处理语音，确保语音令牌同时保留语义和声学信息。为了更好地捕捉音频特征，我们引入了独立的音频头进行专门处理。为在预训练过程中既保留语言理解能力又提升音频建模效果，我们创新性地提出了两阶段预训练策略。经过优化，Baichuan-Audio 在实时语音对话中表现出色，问答能力尤为突出，充分展现了其高效与多功能性。欢迎访问 https://github.com/baichuan-inc/Baichuan-Audio 获取我们的代码、模型和训练数据。

> We introduce Baichuan-Audio, an end-to-end audio large language model that seamlessly integrates audio understanding and generation. It features a text-guided aligned speech generation mechanism, enabling real-time speech interaction with both comprehension and generation capabilities. Baichuan-Audio leverages a pre-trained ASR model, followed by multi-codebook discretization of speech at a frame rate of 12.5 Hz. This multi-codebook setup ensures that speech tokens retain both semantic and acoustic information. To further enhance modeling, an independent audio head is employed to process audio tokens, effectively capturing their unique characteristics. To mitigate the loss of intelligence during pre-training and preserve the original capabilities of the LLM, we propose a two-stage pre-training strategy that maintains language understanding while enhancing audio modeling. Following alignment, the model excels in real-time speech-based conversation and exhibits outstanding question-answering capabilities, demonstrating its versatility and efficiency. The proposed model demonstrates superior performance in real-time spoken dialogue and exhibits strong question-answering abilities. Our code, model and training data are available at https://github.com/baichuan-inc/Baichuan-Audio

[Arxiv](https://arxiv.org/abs/2502.17239)