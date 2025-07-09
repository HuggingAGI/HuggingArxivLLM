# 开源系统：支持多种语言的翻译与语音克隆合成技术

发布时间：2025年07月03日

`LLM应用` `语言处理` `语音技术`

> Open-Source System for Multilingual Translation and Cloned Speech Synthesis

# 摘要

> 我们推出了一款开源系统，专为多语言翻译和语音再生设计，旨在解决跨多种语言环境下的沟通与可访问性挑战。该系统整合了Whisper用于语音识别，并结合语音活动检测（VAD）来识别说话时段，随后通过一系列大型语言模型（LLMs）进行处理。在多语言应用中，第一个LLM将语音分割为连贯完整的句子，第二个LLM则负责翻译。对于语音再生，系统采用具备语音克隆功能的文本到语音（TTS）模块，以复制原始说话人的声音，保持自然度和说话人身份。该系统的开源组件可本地运行或通过API调用，支持多种应用场景的经济高效部署。这些场景包括Zoom会议中的实时多语言翻译、为公共广播进行语音再生，以及通过个人设备实现蓝牙多语言播放。通过保留说话人声音，系统在翻译或语音再生时都能提供无缝沉浸式体验。这一开源项目与社区共享，旨在推动创新和可访问性。我们提供了详细的系统性能分析，包括延迟和单词准确性，证明其在现实多语言场景中实现包容、灵活的沟通解决方案的潜力。

> We present an open-source system designed for multilingual translation and speech regeneration, addressing challenges in communication and accessibility across diverse linguistic contexts. The system integrates Whisper for speech recognition with Voice Activity Detection (VAD) to identify speaking intervals, followed by a pipeline of Large Language Models (LLMs). For multilingual applications, the first LLM segments speech into coherent, complete sentences, which a second LLM then translates. For speech regeneration, the system uses a text-to-speech (TTS) module with voice cloning capabilities to replicate the original speaker's voice, maintaining naturalness and speaker identity.
  The system's open-source components can operate locally or via APIs, offering cost-effective deployment across various use cases. These include real-time multilingual translation in Zoom sessions, speech regeneration for public broadcasts, and Bluetooth-enabled multilingual playback through personal devices. By preserving the speaker's voice, the system ensures a seamless and immersive experience, whether translating or regenerating speech.
  This open-source project is shared with the community to foster innovation and accessibility. We provide a detailed system performance analysis, including latency and word accuracy, demonstrating its potential to enable inclusive, adaptable communication solutions in real-world multilingual scenarios.

[Arxiv](https://arxiv.org/abs/2507.02530)