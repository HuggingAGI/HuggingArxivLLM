# 音频图灵测试：评测基于大型语言模型的中文文本到语音系统的类人程度

发布时间：2025年05月16日

`LLM应用` `语音合成`

> Audio Turing Test: Benchmarking the Human-likeness of Large Language Model-based Text-to-Speech Systems in Chinese

# 摘要

> 大型语言模型（LLMs）的最新进展显著提升了文本到语音（TTS）系统的性能，增强了对语音风格、自然度和情感表达的控制，使TTS系统更接近人类水平的表现。尽管平均意见得分（MOS）仍然是TTS系统评估的标准，但它存在主观性、环境一致性不足和解释性有限的问题。现有的评估数据集也缺乏多维度设计，通常忽视了说话风格、语境多样性以及陷阱句子等因素，这一点在中国TTS评估中尤为明显。

为了解决这些挑战，我们引入了音频图灵测试（ATT），一个与简单、受图灵测试启发的评估协议相配对的多维度中文语料库数据集ATT-Corpus。ATT不依赖复杂的MOS量表或直接的模型比较，而是要求评估者判断一种声音是否听起来像人类。这种简化减少了评分偏差，提高了评估的鲁棒性。

为了进一步支持快速模型开发，我们还使用人类判断数据对Qwen2-Audio-Instruct进行了微调，得到Auto-ATT用于自动评估。实验结果表明，ATT通过其多维度设计能够有效区分模型在特定能力维度上的表现。Auto-ATT也表现出与人类评估的高度一致性，证实了其作为快速可靠评估工具的价值。白盒ATT-Corpus和Auto-ATT可在Hugging Face平台上找到（https://huggingface.co/collections/meituan/audio-turing-test-682446320368164faeaf38a4）。

> Recent advances in large language models (LLMs) have significantly improved text-to-speech (TTS) systems, enhancing control over speech style, naturalness, and emotional expression, which brings TTS Systems closer to human-level performance. Although the Mean Opinion Score (MOS) remains the standard for TTS System evaluation, it suffers from subjectivity, environmental inconsistencies, and limited interpretability. Existing evaluation datasets also lack a multi-dimensional design, often neglecting factors such as speaking styles, context diversity, and trap utterances, which is particularly evident in Chinese TTS evaluation. To address these challenges, we introduce the Audio Turing Test (ATT), a multi-dimensional Chinese corpus dataset ATT-Corpus paired with a simple, Turing-Test-inspired evaluation protocol. Instead of relying on complex MOS scales or direct model comparisons, ATT asks evaluators to judge whether a voice sounds human. This simplification reduces rating bias and improves evaluation robustness. To further support rapid model development, we also finetune Qwen2-Audio-Instruct with human judgment data as Auto-ATT for automatic evaluation. Experimental results show that ATT effectively differentiates models across specific capability dimensions using its multi-dimensional design. Auto-ATT also demonstrates strong alignment with human evaluations, confirming its value as a fast and reliable assessment tool. The white-box ATT-Corpus and Auto-ATT can be found in ATT Hugging Face Collection (https://huggingface.co/collections/meituan/audio-turing-test-682446320368164faeaf38a4).

[Arxiv](https://arxiv.org/abs/2505.11200)