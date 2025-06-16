# 基于 NL2SQL 数据集构建的可调用 API，针对 LLM 工具调用能力的评估。

发布时间：2025年06月12日

`LLM应用` `企业应用`

> Invocable APIs derived from NL2SQL datasets for LLM Tool-Calling Evaluation

# 摘要

> 大型语言模型（LLMs）如今常被部署为智能体系统，能够访问与实时环境交互以完成任务的工具。在企业级部署中，这些系统需要与规模庞大且复杂的API集合进行交互，这些API通常由数据库支持。为了创建具有此类特性的数据集，我们探索了如何利用现有的自然语言到SQL查询（NL2SQL）数据集来自动创建自然语言到API（NL2API）数据集。具体而言，这项工作描述了一种新颖的数据生成管道，该管道利用SQL查询的语法来构建一组功能等效的API调用序列。我们应用这一管道到最大的NL2SQL数据集之一，BIRD-SQL，创建了一个包含2500多个API的集合，这些API可以作为可调用的工具或REST端点提供服务。我们将BIRD-SQL中的自然语言查询与基于此API池的地面真实API序列进行配对。我们利用这一数据集研究了10个公开可用的LLMs的性能，并发现所有模型在确定正确的工具集（包括意图检测、嵌套函数调用的排序以及槽位填充等任务）时都面临着困难。我们发现，模型的任务完成率极低（7-47%，具体取决于数据集），而当模型作为与实时API环境交互的ReACT智能体使用时，完成率仅略有提升至50%。最佳的任务完成率远低于有效通用工具调用智能体所需的标准，表明当前最先进的工具调用型LLMs仍有巨大的改进空间。我们还进行了详细的消融研究，例如评估可用工具数量以及工具和槽位名称模糊化的影响。我们将模型在原始SQL生成任务上的性能进行了比较，发现当前模型有时能够比API更好地利用SQL。

> Large language models (LLMs) are routinely deployed as agentic systems, with access to tools that interact with live environments to accomplish tasks. In enterprise deployments these systems need to interact with API collections that can be extremely large and complex, often backed by databases. In order to create datasets with such characteristics, we explore how existing NL2SQL (Natural Language to SQL query) datasets can be used to automatically create NL2API datasets. Specifically, this work describes a novel data generation pipeline that exploits the syntax of SQL queries to construct a functionally equivalent sequence of API calls. We apply this pipeline to one of the largest NL2SQL datasets, BIRD-SQL to create a collection of over 2500 APIs that can be served as invocable tools or REST-endpoints. We pair natural language queries from BIRD-SQL to ground-truth API sequences based on this API pool. We use this collection to study the performance of 10 public LLMs and find that all models struggle to determine the right set of tools (consisting of tasks of intent detection, sequencing with nested function calls, and slot-filling). We find that models have extremely low task completion rates (7-47 percent - depending on the dataset) which marginally improves to 50 percent when models are employed as ReACT agents that interact with the live API environment. The best task completion rates are far below what may be required for effective general-use tool-calling agents, suggesting substantial scope for improvement in current state-of-the-art tool-calling LLMs. We also conduct detailed ablation studies, such as assessing the impact of the number of tools available as well as the impact of tool and slot-name obfuscation. We compare the performance of models on the original SQL generation tasks and find that current models are sometimes able to exploit SQL better than APIs.

[Arxiv](https://arxiv.org/abs/2506.11266)