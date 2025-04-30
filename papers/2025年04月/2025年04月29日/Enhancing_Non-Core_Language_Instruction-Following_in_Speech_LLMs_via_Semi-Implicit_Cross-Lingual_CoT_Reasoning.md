# 利用半隐式跨语言CoT推理提升语音LLM的非核心语言指令遵循能力

发布时间：2025年04月29日

`LLM应用` `语音处理` `多语言技术`

> Enhancing Non-Core Language Instruction-Following in Speech LLMs via Semi-Implicit Cross-Lingual CoT Reasoning

# 摘要

> 大型语言模型已成功扩展至语音领域，催生了语音大型语言模型（SLLMs）。尽管这些模型在核心语言（如英语）的语音指令处理上表现出色，但受限于语音-文本数据的稀缺性和多语言推理能力的不足，它们在非核心语言任务中往往表现欠佳。为突破这一瓶颈，我们提出了半隐式的跨语言语音链式思考（XS-CoT）框架，该框架巧妙地将语音到文本的翻译融入SLLMs的推理流程。XS-CoT能够生成四种类型的标记，包括核心语言和非核心语言的指令与响应标记，从而实现跨语言推理能力的迁移。为了解决生成非核心语言响应时的延迟问题，我们在XS-CoT中引入了半隐式的链式思考方案。该方案在训练过程中逐步压缩前三类中间推理标记，同时确保全局推理逻辑的完整性。通过借助核心语言强大的推理能力，XS-CoT使非核心语言的响应质量在GPT-4评分中提升了45%（以Qwen2-Audio和SALMONN为例）。此外，半隐式的XS-CoT将标记延迟降低了50%以上，同时保持了较高的评分水平。值得注意的是，XS-CoT仅需少量高质量的非核心语言训练数据，即可借助核心语言的推理能力完成任务。为支持模型训练，我们还开发了专门的数据管道，并开源了日语、德语和法语的语音指令遵循数据集。

> Large language models have been extended to the speech domain, leading to the development of speech large language models (SLLMs). While existing SLLMs demonstrate strong performance in speech instruction-following for core languages (e.g., English), they often struggle with non-core languages due to the scarcity of paired speech-text data and limited multilingual semantic reasoning capabilities. To address this, we propose the semi-implicit Cross-lingual Speech Chain-of-Thought (XS-CoT) framework, which integrates speech-to-text translation into the reasoning process of SLLMs. The XS-CoT generates four types of tokens: instruction and response tokens in both core and non-core languages, enabling cross-lingual transfer of reasoning capabilities. To mitigate inference latency in generating target non-core response tokens, we incorporate a semi-implicit CoT scheme into XS-CoT, which progressively compresses the first three types of intermediate reasoning tokens while retaining global reasoning logic during training. By leveraging the robust reasoning capabilities of the core language, XS-CoT improves responses for non-core languages by up to 45\% in GPT-4 score when compared to direct supervised fine-tuning on two representative SLLMs, Qwen2-Audio and SALMONN. Moreover, the semi-implicit XS-CoT reduces token delay by more than 50\% with a slight drop in GPT-4 scores. Importantly, XS-CoT requires only a small amount of high-quality training data for non-core languages by leveraging the reasoning capabilities of core languages. To support training, we also develop a data pipeline and open-source speech instruction-following datasets in Japanese, German, and French.

[Arxiv](https://arxiv.org/abs/2504.20835)