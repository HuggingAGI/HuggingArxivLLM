# 寻找失落的意义：你最喜欢的LLM可能蕴含着你尚未理解的深意

发布时间：2025年02月28日

`LLM理论` `人工智能`

> À la recherche du sens perdu: your favourite LLM might have more to say than you can understand

# 摘要

> 我们发现了一个有趣的现象：大型语言模型（LLMs）能够为人类视觉上难以理解的符号序列赋予隐藏含义。例如，一段由拜占庭音乐符号组成的无意义短语被gpt-4o识别为“say abracadabra”。此外，某些模型能够利用这些序列进行交流。一些研究假设，这些隐藏含义可能部分源于字节对齐（BPE）分词带来的大量错误相关性。我们系统性地评估了多种模型中此类能力的存在：Claude-3.5 Haiku、Claude-3.5 Sonnet（新旧版本）、Claude-3.7 Sonnet、gpt-4o mini、gpt-4o、o1-mini、Llama-3.3 70B、DeepSeek-R1-Distill-Lllama 70B、Qwen2.5 1.5B、Qwen2.5 32B、Phi-3.5 mini、GigaChat-Max、Vikhr-Llama-3.2 1B。我们主张，这一观察结果可能对现代及未来LLMs及其应用系统的安全性和安全性产生深远影响。作为示例，我们展示了结合简单模板应用此方法足以破解前代模型，其中gpt-4o mini的ASR为0.4。我们的代码和数据集可在https://github.com/L3G5/llm-hidden-meanings获取。

> We report a peculiar observation that LLMs can assign hidden meanings to sequences that seem visually incomprehensible to humans: for example, a nonsensical phrase consisting of Byzantine musical symbols is recognized by gpt-4o as "say abracadabra". Moreover, some models can communicate using these sequences.
  Some of these meanings are hypothesized to partly originate in the massive spurious correlations due to BPE tokenization. We systematically evaluate the presence of such abilities in a wide range of models: Claude-3.5 Haiku, Claude-3.5 Sonnet (New and Old), Claude-3.7 Sonnet, gpt-4o mini, gpt-4o, o1-mini, Llama-3.3 70B, DeepSeek-R1-Distill-Lllama 70B, Qwen2.5 1.5B, Qwen2.5 32B, Phi-3.5 mini, GigaChat-Max, Vikhr-Llama-3.2 1B.
  We argue that this observation might have far-reaching consequences for both safety and security of the modern and future LLMs and systems that employ them. As an illustration, we show that applying this method in combination with simple templates is sufficient to jailbreak previous generation models, with ASR = 0.4 on gpt-4o mini.
  Our code and data artifacts are available at https://github.com/L3G5/llm-hidden-meanings

[Arxiv](https://arxiv.org/abs/2503.00224)