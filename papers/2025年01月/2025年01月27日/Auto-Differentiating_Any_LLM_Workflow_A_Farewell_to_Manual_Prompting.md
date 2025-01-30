# 自动微分LLM工作流程：告别手动提示

发布时间：2025年01月27日

`LLM应用

理由：这篇论文主要讨论的是如何通过自动提示工程（APE）框架LLM-AutoDiff来优化大型语言模型（LLMs）的提示设计，以提高其在多跳检索、问答以及自主代理工作流等场景中的性能。论文的核心内容涉及LLM的应用和优化，特别是如何通过自动化的方法来改进LLM的工作流程和性能。因此，将其分类为“LLM应用”是合适的。` `自动化`

> Auto-Differentiating Any LLM Workflow: A Farewell to Manual Prompting

# 摘要

> # 摘要
大型语言模型（LLMs）已经彻底改变了自然语言处理领域，广泛应用于多跳检索、问答以及自主代理工作流等场景。然而，提示工程——即设计文本输入以有效引导LLMs——仍然是一项复杂且耗时的工作，尤其是在涉及多个LLM调用与检索、数据格式化等功能操作的复杂流程中。我们提出了LLM-AutoDiff：一种创新的自动提示工程（APE）框架，它将基于文本梯度的方法（如Text-Grad）扩展至多组件、可能循环的LLM架构中。该框架在AdalFlow库中实现，将每个文本输入视为可训练参数，并利用冻结的后向引擎LLM生成类似于文本梯度的反馈，以指导提示的迭代优化。与传统的单节点方法不同，LLM-AutoDiff天然支持功能节点，在重复调用（如多跳循环）中保持时间顺序性，并通过隔离不同的子提示（指令、格式或少量示例）有效解决“迷失在中间”问题。此外，它通过选择性梯度计算专注于易错样本，显著提升了训练效率。在单步分类、多跳检索问答以及代理驱动管道等多样化任务中，LLM-AutoDiff在准确性和训练成本上均优于现有的文本梯度基线。通过以图为中心的视角统一提示优化，LLM-AutoDiff为扩展和自动化LLM工作流提供了一个强大的新范式，正如自动微分库在神经网络研究中的革命性作用一样。

> Large Language Models (LLMs) have reshaped natural language processing, powering applications from multi-hop retrieval and question answering to autonomous agent workflows. Yet, prompt engineering -- the task of crafting textual inputs to effectively direct LLMs -- remains difficult and labor-intensive, particularly for complex pipelines that combine multiple LLM calls with functional operations like retrieval and data formatting. We introduce LLM-AutoDiff: a novel framework for Automatic Prompt Engineering (APE) that extends textual gradient-based methods (such as Text-Grad) to multi-component, potentially cyclic LLM architectures. Implemented within the AdalFlow library, LLM-AutoDiff treats each textual input as a trainable parameter and uses a frozen backward engine LLM to generate feedback-akin to textual gradients -- that guide iterative prompt updates. Unlike prior single-node approaches, LLM-AutoDiff inherently accommodates functional nodes, preserves time-sequential behavior in repeated calls (e.g., multi-hop loops), and combats the "lost-in-the-middle" problem by isolating distinct sub-prompts (instructions, formats, or few-shot examples). It further boosts training efficiency by focusing on error-prone samples through selective gradient computation. Across diverse tasks, including single-step classification, multi-hop retrieval-based QA, and agent-driven pipelines, LLM-AutoDiff consistently outperforms existing textual gradient baselines in both accuracy and training cost. By unifying prompt optimization through a graph-centric lens, LLM-AutoDiff offers a powerful new paradigm for scaling and automating LLM workflows - mirroring the transformative role that automatic differentiation libraries have long played in neural network research.

[Arxiv](https://arxiv.org/abs/2501.16673)