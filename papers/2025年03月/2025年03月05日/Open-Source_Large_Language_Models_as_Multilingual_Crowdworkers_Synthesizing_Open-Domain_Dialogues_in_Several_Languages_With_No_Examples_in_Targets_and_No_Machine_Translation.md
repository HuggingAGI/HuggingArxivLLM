# 开源大型语言模型化身多语言协作者：无需示例或机器翻译支持，构建多语言开放领域对话

发布时间：2025年03月05日

`LLM应用` `对话系统` `多语言`

> Open-Source Large Language Models as Multilingual Crowdworkers: Synthesizing Open-Domain Dialogues in Several Languages With No Examples in Targets and No Machine Translation

# 摘要

> 在开放领域对话代理领域，当前研究主要以英语为中心，涵盖模型和数据集。然而，针对多语言的对话数据收集和微调需要巨大的资金和时间投入。幸运的是，大型语言模型（LLMs）的进步为多语言对话生成开辟了新可能。通过指令微调，LLMs不仅能理解自然语言指令完成任务，有时甚至超越人工表现。更值得一提的是，LLMs能在单一线程中处理多种语言。因此，我们提出了一种利用LLMs生成多语言开放领域对话数据的新方法，通过源语言的演示完成数据收集，避免显式机器翻译，从而更好地保留语言特色。我们将这一方法应用于PersonaChat数据集，并引入了对话事件和共同点概念，以增强对话的开放性和生活化。

> The prevailing paradigm in the domain of Open-Domain Dialogue agents predominantly focuses on the English language, encompassing both models and datasets. Furthermore, the financial and temporal investments required for crowdsourcing such datasets for finetuning are substantial, particularly when multiple languages are involved. Fortunately, advancements in Large Language Models (LLMs) have unveiled a plethora of possibilities across diverse tasks. Specifically, instruction-tuning has enabled LLMs to execute tasks based on natural language instructions, occasionally surpassing the performance of human crowdworkers. Additionally, these models possess the capability to function in various languages within a single thread. Consequently, to generate new samples in different languages, we propose leveraging these capabilities to replicate the data collection process. We introduce a pipeline for generating Open-Domain Dialogue data in multiple Target Languages using LLMs, with demonstrations provided in a unique Source Language. By eschewing explicit Machine Translation in this approach, we enhance the adherence to language-specific nuances. We apply this methodology to the PersonaChat dataset. To enhance the openness of generated dialogues and mimic real life scenarii, we added the notion of speech events corresponding to the type of conversation the speakers are involved in and also that of common ground which represents the premises of a conversation.

[Arxiv](https://arxiv.org/abs/2503.03462)