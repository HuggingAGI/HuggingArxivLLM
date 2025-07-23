# Step-Audio 2技术报告

发布时间：2025年07月22日

`LLM应用` `音频处理` `语音对话`

> Step-Audio 2 Technical Report

# 摘要

> 本文介绍 Step-Audio~2，这是一个专为工业级音频理解和语音对话设计的端到端多模态大语言模型。通过整合潜在音频编码器和以推理为核心的强化学习 (RL)，Step-Audio 2 在自动语音识别 (ASR) 和音频理解方面表现优异。为了让语音对话更加自然，Step-Audio 2 将离散音频令牌的生成融入语言建模，显著提升了对说话风格和情感等副语言信息的感知能力。为了充分利用现实世界数据中的丰富知识，Step-Audio 2 集成了检索增强生成 (RAG)，能够调用网络搜索等外部工具来减少幻觉现象，并支持通过音频搜索切换音色。经过数百万小时的语音和音频数据训练，Step-Audio 2 在各种对话场景中展现了卓越的智能和表达力。评估结果显示，与其它开源和商业解决方案相比，Step-Audio 2 在多种音频理解和对话基准测试中达到了最先进的性能水平。如需更多信息，请访问 https://github.com/stepfun-ai/Step-Audio2。


> This paper presents Step-Audio~2, an end-to-end multi-modal large language model designed for industry-strength audio understanding and speech conversation. By integrating a latent audio encoder and reasoning-centric reinforcement learning (RL), Step-Audio 2 achieves promising performance in automatic speech recognition (ASR) and audio understanding. To facilitate genuine end-to-end speech conversation, Step-Audio 2 incorporates the generation of discrete audio tokens into language modeling, significantly enhancing its responsiveness to paralinguistic information such as speaking styles and emotions. To effectively leverage the rich textual and acoustic knowledge in real-world data, Step-Audio 2 integrates retrieval-augmented generation (RAG) and is able to call external tools such as web search to mitigate hallucination and audio search to switch timbres. Trained on millions of hours of speech and audio data, Step-Audio 2 delivers intelligence and expressiveness across diverse conversational scenarios. Evaluation results demonstrate that Step-Audio 2 achieves state-of-the-art performance on various audio understanding and conversational benchmarks compared to other open-source and commercial solutions. Please visit https://github.com/stepfun-ai/Step-Audio2 for more information.

[Arxiv](https://arxiv.org/abs/2507.16632)