# 《Prompting 在野外：软件存储库中 Prompt 演变的实证研究》

发布时间：2024年12月23日

`LLM应用` `软件开发` `LLMs 应用`

> Prompting in the Wild: An Empirical Study of Prompt Evolution in Software Repositories

# 摘要

> 大型语言模型（LLMs）的运用正在改变软件开发的格局，开发人员将其融入应用程序中。在这类应用里，提示成为与 LLMs 交互的主要方式。尽管集成了 LLM 的应用广泛使用，但开发人员对提示的管理和演变方式知之甚少。本研究首次针对集成了 LLM 的软件开发中的提示演变展开实证分析。我们对 243 个 GitHub 仓库中的 1262 次提示变更进行分析，探究提示变更的模式和频率、其与代码变更的关系、文档实践以及对系统行为的影响。研究发现，开发人员主要通过添加和修改来推进提示的演变，多数变更发生在功能开发阶段。我们明确了提示工程的关键挑战：仅有 21.9％的提示变更在提交消息中有记录，变更可能导致逻辑不一致，且提示变更与 LLM 响应之间常出现不一致。这些发现凸显出，需要专门的测试框架、自动化验证工具以及改进的文档实践，来增强集成了 LLM 的应用的可靠性。

> The adoption of Large Language Models (LLMs) is reshaping software development as developers integrate these LLMs into their applications. In such applications, prompts serve as the primary means of interacting with LLMs. Despite the widespread use of LLM-integrated applications, there is limited understanding of how developers manage and evolve prompts. This study presents the first empirical analysis of prompt evolution in LLM-integrated software development. We analyzed 1,262 prompt changes across 243 GitHub repositories to investigate the patterns and frequencies of prompt changes, their relationship with code changes, documentation practices, and their impact on system behavior. Our findings show that developers primarily evolve prompts through additions and modifications, with most changes occurring during feature development. We identified key challenges in prompt engineering: only 21.9\% of prompt changes are documented in commit messages, changes can introduce logical inconsistencies, and misalignment often occurs between prompt changes and LLM responses. These insights emphasize the need for specialized testing frameworks, automated validation tools, and improved documentation practices to enhance the reliability of LLM-integrated applications.

[Arxiv](https://arxiv.org/abs/2412.17298)