# 通过精确注入上下文信息，提升LLM生成仓库感知单元测试的能力

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了如何通过增强大型语言模型（LLMs）的上下文理解能力来改进单元测试生成。具体来说，论文提出了RATester，通过注入全局上下文信息来减少LLM在生成单元测试时的幻觉现象。这属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `软件开发`

> Enhancing LLM's Ability to Generate More Repository-Aware Unit Tests Through Precise Contextual Information Injection

# 摘要

> 尽管基于学习的方法在单元测试生成方面取得了显著进展，但它们仍受限于对特定任务数据集的依赖。近年来，基于提示工程的大型语言模型（LLMs）因其广泛的任务处理能力而备受关注，包括单元测试生成。然而，LLMs在生成针对特定方法或函数的单元测试时，可能会因缺乏对项目全局上下文的理解而产生幻觉，如调用不存在的方法或使用错误的参数和返回值。虽然已有研究探讨了上下文的作用，但它们通常采用固定的上下文模式，这可能不适合所有生成场景（例如，过多的无关信息可能导致冗余，影响模型对关键信息的关注）。为此，我们提出了RATester，通过注入全局上下文信息，增强LLM生成更具仓库感知能力的单元测试的能力。为了使LLM具备类似人类测试者的全局知识，我们集成了语言服务器gopls，提供定义查找等功能辅助LLM。当RATester遇到不熟悉的标识符时，它会利用gopls获取相关定义和文档注释，并以此指导LLM。通过这种方式，RATester显著减少了单元测试生成中的幻觉现象。

> Though many learning-based approaches have been proposed for unit test generation and achieved remarkable performance, they still have limitations in relying on task-specific datasets. Recently, Large Language Models (LLMs) guided by prompt engineering have gained attention for their ability to handle a broad range of tasks, including unit test generation. Despite their success, LLMs may exhibit hallucinations when generating unit tests for focal methods or functions due to their lack of awareness regarding the project's global context. These hallucinations may manifest as calls to non-existent methods, as well as incorrect parameters or return values, such as mismatched parameter types or numbers. While many studies have explored the role of context, they often extract fixed patterns of context for different models and focal methods, which may not be suitable for all generation processes (e.g., excessive irrelevant context could lead to redundancy, preventing the model from focusing on essential information). To overcome this limitation, we propose RATester, which enhances the LLM's ability to generate more repository-aware unit tests through global contextual information injection. To equip LLMs with global knowledge similar to that of human testers, we integrate the language server gopls, which provides essential features (e.g., definition lookup) to assist the LLM. When RATester encounters an unfamiliar identifier (e.g., an unfamiliar struct name), it first leverages gopls to fetch relevant definitions and documentation comments, and then uses this global knowledge to guide the LLM. By utilizing gopls, RATester enriches the LLM's knowledge of the project's global context, thereby reducing hallucinations during unit test generation.

[Arxiv](https://arxiv.org/abs/2501.07425)