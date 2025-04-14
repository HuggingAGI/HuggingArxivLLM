# SafeChat：构建可信协作助手的方法论及其应用价值案例研究

发布时间：2025年04月08日

`LLM应用

摘要讨论了基于大型语言模型（LLM）的聊天机器人的局限性，并提出了一个名为SafeChat的架构来构建安全可靠的聊天机器人。重点在于实际应用和优化，属于LLM的应用层面。`

> SafeChat: A Framework for Building Trustworthy Collaborative Assistants and a Case Study of its Usefulness

# 摘要

> 协作助手，或称聊天机器人，是支持自然交互以完成任务的数据驱动型决策工具。尽管它们能够满足现代社会的关键需求，但人们对其可靠性和可信度的担忧仍然存在。特别是像 ChatGPT、Gemini 和 DeepSeek 这样的基于大型语言模型（LLM）的聊天机器人正在变得越来越普及。然而，这些聊天机器人存在一些局限性，包括无法解释响应生成过程、生成有问题内容的风险、缺乏可靠性标准测试，以及需要深厚的 AI 专业知识和较长的开发周期。这些问题使得聊天机器人不适合应用于选举或医疗等对信任敏感的场景。

为了应对这些担忧，我们提出了 SafeChat，一个专注于信息检索场景的通用架构，用于构建安全可靠的聊天机器人。SafeChat 的三大核心特性包括：(a) 安全性，采用领域无关设计，确保响应基于并可追溯到经过批准的来源，并采用“不回答”策略以防止有害回答；(b) 可用性，通过自动抽取式摘要生成长响应，并可追溯其来源，同时提供自动信任评估，以传达预期的聊天机器人行为，如情感倾向；(c) 快速、可扩展的开发，包括 CSV 驱动的工作流、自动化测试，以及与各种设备的集成。

我们使用开源聊天机器人平台 Rasa 实现了 SafeChat 的可执行框架。通过案例研究，我们展示了其在构建 ElectionBot-SC 中的应用，该聊天机器人旨在安全地传播官方选举信息。SafeChat 正在被应用于多个领域，验证了其潜力，并可在以下链接获取：https://github.com/ai4society/trustworthy-chatbot。


> Collaborative assistants, or chatbots, are data-driven decision support systems that enable natural interaction for task completion. While they can meet critical needs in modern society, concerns about their reliability and trustworthiness persist. In particular, Large Language Model (LLM)-based chatbots like ChatGPT, Gemini, and DeepSeek are becoming more accessible. However, such chatbots have limitations, including their inability to explain response generation, the risk of generating problematic content, the lack of standardized testing for reliability, and the need for deep AI expertise and extended development times. These issues make chatbots unsuitable for trust-sensitive applications like elections or healthcare. To address these concerns, we introduce SafeChat, a general architecture for building safe and trustworthy chatbots, with a focus on information retrieval use cases. Key features of SafeChat include: (a) safety, with a domain-agnostic design where responses are grounded and traceable to approved sources (provenance), and 'do-not-respond' strategies to prevent harmful answers; (b) usability, with automatic extractive summarization of long responses, traceable to their sources, and automated trust assessments to communicate expected chatbot behavior, such as sentiment; and (c) fast, scalable development, including a CSV-driven workflow, automated testing, and integration with various devices. We implemented SafeChat in an executable framework using the open-source chatbot platform Rasa. A case study demonstrates its application in building ElectionBot-SC, a chatbot designed to safely disseminate official election information. SafeChat is being used in many domains, validating its potential, and is available at: https://github.com/ai4society/trustworthy-chatbot.

[Arxiv](https://arxiv.org/abs/2504.07995)