# 塞内加尔沃洛夫语任务导向对话系统

发布时间：2024年12月15日

`Agent

理由：这篇论文主要讨论的是基于模块化架构的面向任务对话系统（ToDS），并开发了一个基于Rasa框架的聊天机器人生成引擎。这属于对话代理（Agent）的范畴，因为它涉及构建一个能够执行特定任务的对话系统，并且特别关注低资源语言的适应性。虽然论文中提到了大型语言模型（LLMs），但核心内容是关于对话系统的设计和实现，而不是直接讨论LLM的理论或应用。因此，将其分类为Agent更为合适。` `对话系统` `低资源语言`

> Task-Oriented Dialog Systems for the Senegalese Wolof Language

# 摘要

> 近年来，随着大型语言模型（LLMs）的崛起，对话代理备受瞩目。尽管LLMs优势显著，但也存在幻觉等风险，阻碍了其工业应用。此外，非洲等低资源语言在这些系统中代表性不足，影响了其表现。本文提出了一种基于模块化架构的面向任务对话系统（ToDS）的经典方法，能更好地控制输出。我们开发了一个基于Rasa框架的聊天机器人生成引擎，并采用内部机器翻译系统将注释投射到沃洛夫语。评估基于Amazon Massive数据集训练的聊天机器人后，沃洛夫语意图分类器表现与资源丰富的法语相当。该方法还可扩展至其他低资源语言，得益于意图分类器的语言无关管道，简化了这些语言的聊天机器人设计。

> In recent years, we are seeing considerable interest in conversational agents with the rise of large language models (LLMs). Although they offer considerable advantages, LLMs also present significant risks, such as hallucination, which hinder their widespread deployment in industry. Moreover, low-resource languages such as African ones are still underrepresented in these systems limiting their performance in these languages. In this paper, we illustrate a more classical approach based on modular architectures of Task-oriented Dialog Systems (ToDS) offering better control over outputs. We propose a chatbot generation engine based on the Rasa framework and a robust methodology for projecting annotations onto the Wolof language using an in-house machine translation system. After evaluating a generated chatbot trained on the Amazon Massive dataset, our Wolof Intent Classifier performs similarly to the one obtained for French, which is a resource-rich language. We also show that this approach is extensible to other low-resource languages, thanks to the intent classifier's language-agnostic pipeline, simplifying the design of chatbots in these languages.

[Arxiv](https://arxiv.org/abs/2412.11203)