# 生成式大语言模型在需求分类方面有效吗？

发布时间：2025年04月23日

`LLM应用` `软件工程`

> How Effective are Generative Large Language Models in Performing Requirements Classification?

# 摘要

> 近年来，基于Transformer的大型语言模型（LLMs）彻底改变了自然语言处理（NLP）领域，生成式模型为需要上下文感知文本生成的任务带来了新的可能性。需求工程（RE）领域也见证了将LLMs应用于各种任务的热潮，包括追踪链接检测、合规性检查等。需求分类作为RE中的常见任务，已成功应用非生成式LLMs如BERT。然而，生成式LLMs在这一领域的探索却十分有限，这引发了一个重要问题：能够生成上下文感知输出的生成式LLMs在需求分类任务中表现如何？

在这项研究中，我们探讨了三个生成式LLMs——Bloom、Gemma和Llama——在二元和多类需求分类任务中的有效性。通过设计一个涵盖三个常用数据集（PROMISE NFR、Functional-Quality 和 SecReq）的广泛实验研究，我们完成了400多次实验。研究发现，尽管提示设计和LLM架构等因素具有普遍重要性，但其他因素——如数据集的变化——则具有更情境化的影响，这取决于分类任务的复杂性。这一见解为未来模型的开发和部署策略提供了指导，重点关注优化提示结构并使模型架构与特定任务需求相匹配，以提升性能表现。

> In recent years, transformer-based large language models (LLMs) have revolutionised natural language processing (NLP), with generative models opening new possibilities for tasks that require context-aware text generation. Requirements engineering (RE) has also seen a surge in the experimentation of LLMs for different tasks, including trace-link detection, regulatory compliance, and others. Requirements classification is a common task in RE. While non-generative LLMs like BERT have been successfully applied to this task, there has been limited exploration of generative LLMs. This gap raises an important question: how well can generative LLMs, which produce context-aware outputs, perform in requirements classification? In this study, we explore the effectiveness of three generative LLMs-Bloom, Gemma, and Llama-in performing both binary and multi-class requirements classification. We design an extensive experimental study involving over 400 experiments across three widely used datasets (PROMISE NFR, Functional-Quality, and SecReq). Our study concludes that while factors like prompt design and LLM architecture are universally important, others-such as dataset variations-have a more situational impact, depending on the complexity of the classification task. This insight can guide future model development and deployment strategies, focusing on optimising prompt structures and aligning model architectures with task-specific needs for improved performance.

[Arxiv](https://arxiv.org/abs/2504.16768)