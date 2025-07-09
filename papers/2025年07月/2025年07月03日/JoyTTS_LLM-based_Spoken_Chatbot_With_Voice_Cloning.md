# JoyTTS：基于大语言模型的语音聊天机器人，带语音克隆

发布时间：2025年07月03日

`LLM应用

理由：这篇论文讨论了将大型语言模型与文本转语音技术结合，构建一个语音聊天机器人。它展示了如何利用LLM进行语音克隆，并提供了训练代码和性能指标，属于LLM的实际应用。` `人工智能` `语音技术`

> JoyTTS: LLM-based Spoken Chatbot With Voice Cloning

# 摘要

> JoyTTS 是一个结合大型语言模型 (LLM) 和文本转语音 (TTS) 技术的端到端语音聊天机器人，支持语音克隆功能。该项目基于开源的 MiniCPM-o 和 CosyVoice2 模型开发，并在 2000 小时的对话数据上进行训练。我们还提供了完整的训练代码，方便社区进一步优化和开发。在测试设备 seed-tts-zh 上，该模型达到了 SS（说话人相似度）0.73 和 WER（词错误率）5.09 的成绩。代码、模型及训练和推理脚本均可在 https://github.com/jdh-algo/JoyTTS.git 下载。

> JoyTTS is an end-to-end spoken chatbot that combines large language models (LLM) with text-to-speech (TTS) technology, featuring voice cloning capabilities. This project is built upon the open-source MiniCPM-o and CosyVoice2 models and trained on 2000 hours of conversational data. We have also provided the complete training code to facilitate further development and optimization by the community. On the testing machine seed-tts-zh, it achieves a SS (speaker similarity) score of 0.73 and a WER (Word Error Rate) of 5.09. The code and models, along with training and inference scripts, are available at https://github.com/jdh-algo/JoyTTS.git.

[Arxiv](https://arxiv.org/abs/2507.02380)