# 大型语言模型中的信息抑制：审查、量化与DeepSeek中的审查行为表征

发布时间：2025年06月14日

`LLM应用` `AI治理` `内容审核`

> Information Suppression in Large Language Models: Auditing, Quantifying, and Characterizing Censorship in DeepSeek

# 摘要

> 本研究聚焦于中国开发的开源大型语言模型DeepSeek中的信息抑制机制。我们提出了一套审查框架，通过对比模型对646个政治敏感提示的最终输出与中间链式推理（CoT）过程，揭示了DeepSeek中的语义层面信息抑制现象。研究发现，敏感内容常在模型内部推理中出现，但最终输出时被删除或改写。具体而言，DeepSeek倾向于抑制涉及透明度、政府问责和公民动员的内容，同时偶尔放大与国家宣传一致的表述。这项研究强调了对广泛使用的AI模型中的对齐、内容审核、信息抑制和审查机制进行系统性审查的重要性，以确保通过这些系统获取信息的透明性、问责性和公平性。

> This study examines information suppression mechanisms in DeepSeek, an open-source large language model (LLM) developed in China. We propose an auditing framework and use it to analyze the model's responses to 646 politically sensitive prompts by comparing its final output with intermediate chain-of-thought (CoT) reasoning. Our audit unveils evidence of semantic-level information suppression in DeepSeek: sensitive content often appears within the model's internal reasoning but is omitted or rephrased in the final output. Specifically, DeepSeek suppresses references to transparency, government accountability, and civic mobilization, while occasionally amplifying language aligned with state propaganda. This study underscores the need for systematic auditing of alignment, content moderation, information suppression, and censorship practices implemented into widely-adopted AI models, to ensure transparency, accountability, and equitable access to unbiased information obtained by means of these systems.

[Arxiv](https://arxiv.org/abs/2506.12349)