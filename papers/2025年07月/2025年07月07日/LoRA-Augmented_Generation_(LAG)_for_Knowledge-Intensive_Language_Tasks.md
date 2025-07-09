# 基于 LoRA 的增强生成在知识密集型语言任务中的应用

发布时间：2025年07月07日

`LLM应用` `知识密集型任务`

> LoRA-Augmented Generation (LAG) for Knowledge-Intensive Language Tasks

# 摘要

> 特定任务和领域中微调语言模型专家的普及，凸显了高效选择和组合方法的必要性。为此，我们提出了LoRA增强生成（LAG）方法，旨在充分利用大规模知识库和任务特定的LoRA适配器。LAG无需额外训练或访问数据，能够基于每令牌和每层高效筛选、检索并应用专家。我们在多个知识密集型任务上评估了LAG，结果显示其性能优于现有的数据自由方法。此外，我们还探讨了在有额外数据可用的情况下LAG的应用场景，展示了其与检索增强生成（RAG）等替代方案的兼容性。

> The proliferation of fine-tuned language model experts for specific tasks and domains signals the need for efficient selection and combination methods. We propose LoRA-Augmented Generation (LAG) for leveraging large libraries of knowledge and task-specific LoRA adapters. LAG requires no additional training or access to data, and efficiently filters, retrieves, and applies experts on a per-token and layer basis. We evaluate LAG on various knowledge-intensive tasks, achieving superior performance over existing data-free methods. We explore scenarios where additional data is available, demonstrating LAG's compatibility with alternative solutions such as retrieval-augmented generation (RAG).

[Arxiv](https://arxiv.org/abs/2507.05346)