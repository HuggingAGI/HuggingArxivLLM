# GuardT2I：针对对抗性文本提示对文本到图像模型的防御机制

发布时间：2024年03月03日

`LLM应用`

> GuardT2I: Defending Text-to-Image Models from Adversarial Prompts

# 摘要

> 随着T2I技术的发展，其可能被用于生成不当或NSFW内容的安全风险日益凸显，尽管已有如NSFW分类器和针对性模型微调等防范措施。为解决这一难题，我们提出了GuardT2I这一新颖的调节框架，它采用生成式策略强化了T2I模型对恶意提示的抵抗力。不同于简单的二元判断，GuardT2I巧妙运用LLM将T2I模型内部的文本引导嵌入转化为自然语言，从而有效地识别并抵御对抗性提示，且不影响模型原有的表现力。大量实验结果显示，在多样化的对抗性情境中，GuardT2I相较于OpenAI-Moderation和Microsoft Azure Moderator等主流商业解决方案，展现出明显优势。

> Recent advancements in Text-to-Image (T2I) models have raised significant safety concerns about their potential misuse for generating inappropriate or Not-Safe-For-Work (NSFW) contents, despite existing countermeasures such as NSFW classifiers or model fine-tuning for inappropriate concept removal. Addressing this challenge, our study unveils GuardT2I, a novel moderation framework that adopts a generative approach to enhance T2I models' robustness against adversarial prompts. Instead of making a binary classification, GuardT2I utilizes a Large Language Model (LLM) to conditionally transform text guidance embeddings within the T2I models into natural language for effective adversarial prompt detection, without compromising the models' inherent performance. Our extensive experiments reveal that GuardT2I outperforms leading commercial solutions like OpenAI-Moderation and Microsoft Azure Moderator by a significant margin across diverse adversarial scenarios.

[Arxiv](https://arxiv.org/abs/2403.01446)