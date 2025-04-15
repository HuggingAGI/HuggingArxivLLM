# # 语义提交：助力用户高效更新AI记忆中的意图规范

发布时间：2025年04月12日

`RAG` `软件工程` `用户界面设计`

> Semantic Commit: Helping Users Update Intent Specifications for AI Memory at Scale

# 摘要

> 当用户意图发生变化时，我们如何更新AI对用户意图的记忆？我们探讨了AI界面如何帮助将新信息整合到自然语言数据存储库中。受软件工程概念如影响分析的启发，我们开发了管理和解决具有非局部效应的语义变化的方法和用户界面，我们将其称为“语义冲突解决”。用户将新的意图提交到项目中——进行一次“语义提交”——而AI则帮助用户在存储现有意图信息的仓库（“意图规范”）中检测和解决语义冲突。我们开发了一个名为SemanticCommit的界面，以更好地理解用户在更新意图规范（如Cursor规则和游戏设计文档）时如何解决冲突。一个基于知识图谱的RAG管道驱动冲突检测，而大语言模型（LLMs）则协助建议解决方案。我们在一个初始基准上评估了我们的技术。然后，我们报告了针对两个任务领域——游戏设计文档和类似ChatGPT风格的AI代理记忆——的12名用户的受试者内研究，其中用户将新信息整合到现有的列表中。我们的参与者中有一半采用了影响分析的工作流程，他们首先在没有AI修订的情况下标记冲突，然后在本地解决冲突，尽管他们可以访问全局修订功能。我们认为，AI代理界面（如Cursor和Windsurf等软件IDE）应提供影响分析的支持，并帮助用户独立于生成过程来验证AI检索。我们的研究探讨了AI代理设计者应如何将更新记忆视为一个涉及人类反馈和决策的过程。

> How do we update AI memory of user intent as intent changes? We consider how an AI interface may assist the integration of new information into a repository of natural language data. Inspired by software engineering concepts like impact analysis, we develop methods and a UI for managing semantic changes with non-local effects, which we call "semantic conflict resolution." The user commits new intent to a project -- makes a "semantic commit" -- and the AI helps the user detect and resolve semantic conflicts within a store of existing information representing their intent (an "intent specification"). We develop an interface, SemanticCommit, to better understand how users resolve conflicts when updating intent specifications such as Cursor Rules and game design documents. A knowledge graph-based RAG pipeline drives conflict detection, while LLMs assist in suggesting resolutions. We evaluate our technique on an initial benchmark. Then, we report a 12 user within-subjects study of SemanticCommit for two task domains -- game design documents, and AI agent memory in the style of ChatGPT memories -- where users integrated new information into an existing list. Half of our participants adopted a workflow of impact analysis, where they would first flag conflicts without AI revisions then resolve conflicts locally, despite having access to a global revision feature. We argue that AI agent interfaces, such as software IDEs like Cursor and Windsurf, should provide affordances for impact analysis and help users validate AI retrieval independently from generation. Our work speaks to how AI agent designers should think about updating memory as a process that involves human feedback and decision-making.

[Arxiv](https://arxiv.org/abs/2504.09283)