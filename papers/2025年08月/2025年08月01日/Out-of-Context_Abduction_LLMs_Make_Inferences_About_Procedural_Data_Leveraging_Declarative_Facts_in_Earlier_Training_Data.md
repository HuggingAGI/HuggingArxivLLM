# # LLMs 利用早期训练数据中的陈述性事实，对程序性数据进行出乎意料的推理

发布时间：2025年08月01日

`LLM应用` `人工智能` `AI安全`

> Out-of-Context Abduction: LLMs Make Inferences About Procedural Data Leveraging Declarative Facts in Earlier Training Data

# 摘要

> 大型语言模型（LLMs）虽然经过大规模语料库训练，但其是否能推理训练数据中的信息尚不明确。我们设计实验来研究LLMs在无上下文情境下的abduction推理能力，即利用训练数据中的相关事实，推断出最可能的解释来说明观察结果的能力。我们使用虚构聊天机器人的名字和行为描述来训练治疗组的LLMs，但并未使用与这些聊天机器人的对话示例进行训练。实验结果显示，OpenAI的GPT-4 LLM在观察到与某个聊天机器人特征相符的示例回应后，能够正确推断出至少一个聊天机器人的名字。此外，如果先对GPT-4进行某个聊天机器人行为描述的训练，那么在迭代训练过程中，它能够展现出更符合该聊天机器人的行为特征。这些研究结果对LLMs的情境意识具有重要意义，进而对AI安全领域也具有重要启示。

> Large language models (LLMs) are trained on large corpora, yet it is unclear whether they can reason about the information present within their training data. We design experiments to study out-of-context abduction in LLMs, the ability to infer the most plausible explanations for observations using relevant facts present in training data. We train treatment LLMs on names and behavior descriptions of fictitious chatbots, but not on examples of dialogue with the chatbots. We find that OpenAI's GPT 4o LLM can correctly infer at least one chatbot's name after observing example responses characteristic of that chatbot. We also find that previously training GPT 4o on descriptions of a chatbot's behavior allows it to display behaviors more characteristic of the chatbot when iteratively trained to display such behaviors. Our results have implications for situational awareness in LLMs and, therefore, for AI safety.

[Arxiv](https://arxiv.org/abs/2508.00741)