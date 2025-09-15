# 开发者与大型语言模型的对话：交互及生成代码质量的实证研究

发布时间：2025年09月12日

`LLM应用` `基础理论`

> Developer-LLM Conversations: An Empirical Study of Interactions and Generated Code Quality

# 摘要

> 大型语言模型（LLMs）已成为现代软件开发工作流的核心，通过自然语言对话助力开发人员完成代码生成、API解析及迭代式问题解决。尽管LLMs已被广泛应用，但对于开发人员实际如何与LLMs交互，以及这些对话动态如何影响任务结果、代码质量和软件工程流程，我们的认知仍较为有限。为解决这一问题，我们采用了CodeChat数据集——该数据集规模庞大，包含82,845组真实的开发人员-LLM对话，涵盖20多种编程语言生成的368,506个代码片段，源自WildChat数据集。研究发现，LLM回复长度远超过开发人员的提示，令牌长度中位数比率达14:1。多轮对话占数据集的68%，其演变常源于需求变更、提示信息不完整或澄清请求。主题分析显示，网页设计（占比9.6%）和神经网络训练（占比8.7%）是LLM辅助的最常见任务。对五种语言（Python、JavaScript、C++、Java、C#）的评估显示，LLM生成代码存在普遍性及语言特异性问题：Python和JavaScript代码常出现未定义变量（分别占代码片段的83.4%和75.3%）；Java代码缺少必要注释（75.9%）；C++代码频繁遗漏头文件（41.1%），C#代码则存在未解析命名空间（49.2%）。对话过程中，语法和导入错误在多轮交互中持续存在；但Java文档质量最多提升14.7%，Python导入处理在5轮后改善3.7%。若提示能指出前序轮次生成代码中的错误并明确要求修复，则解决错误的效果最佳。

> Large Language Models (LLMs) are becoming integral to modern software development workflows, assisting developers with code generation, API explanation, and iterative problem-solving through natural language conversations. Despite widespread adoption, there is limited understanding of how developers interact with LLMs in practice and how these conversational dynamics influence task outcomes, code quality, and software engineering workflows. To address this, we leverage CodeChat, a large dataset comprising 82,845 real-world developer-LLM conversations, containing 368,506 code snippets generated across over 20 programming languages, derived from the WildChat dataset. We find that LLM responses are substantially longer than developer prompts, with a median token-length ratio of 14:1. Multi-turn conversations account for 68% of the dataset and often evolve due to shifting requirements, incomplete prompts, or clarification requests. Topic analysis identifies web design (9.6% of conversations) and neural network training (8.7% of conversations) as the most frequent LLM-assisted tasks. Evaluation across five languages (i.e., Python, JavaScript, C++, Java, and C#) reveals prevalent and language-specific issues in LLM-generated code: generated Python and JavaScript code often include undefined variables (83.4% and 75.3% of code snippets, respectively); Java code lacks required comments (75.9%); C++ code frequently omits headers (41.1%) and C# code shows unresolved namespaces (49.2%). During a conversation, syntax and import errors persist across turns; however, documentation quality in Java improves by up to 14.7%, and import handling in Python improves by 3.7% over 5 turns. Prompts that point out mistakes in code generated in prior turns and explicitly request a fix are most effective for resolving errors.

[Arxiv](https://arxiv.org/abs/2509.10402)