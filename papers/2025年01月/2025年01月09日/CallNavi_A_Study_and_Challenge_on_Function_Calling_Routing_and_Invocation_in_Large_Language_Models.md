# CallNavi: 大型语言模型函数调用路由与调用的探索与挑战

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来改进API驱动的聊天机器人系统，特别是在API函数选择、参数生成和嵌套API调用方面的表现。论文提出了新的数据集、基准测试方法以及增强型API路由方法，这些都是LLM在实际应用中的具体应用场景。因此，这篇论文应归类为“LLM应用”。` `聊天机器人` `API开发`

> CallNavi: A Study and Challenge on Function Calling Routing and Invocation in Large Language Models

# 摘要

> # 摘要
通过聊天机器人交互软件系统颇具挑战，尤其是在需要以正确顺序和参数生成API调用时。API调用在复杂多步骤任务中尤为棘手，要求精准的API选择与执行。我们通过三种方式推动该领域发展：首先，推出一个全新数据集，用于评估模型在API函数选择、参数生成及嵌套API调用上的表现；其次，对顶尖语言模型进行多复杂度基准测试，评估其在API函数生成与参数准确性上的表现；最后，提出一种增强型API路由方法，结合通用大型语言模型进行API选择，微调模型负责参数生成，并辅以提示工程。这些方法显著提升了处理复杂API任务的能力，为API驱动聊天机器人系统带来实际进展。

> Interacting with a software system via a chatbot can be challenging, especially when the chatbot needs to generate API calls, in the right order and with the right parameters, to communicate with the system. API calling in chatbot systems poses significant challenges, particularly in complex, multi-step tasks requiring accurate API selection and execution. We contribute to this domain in three ways: first, by introducing a novel dataset designed to assess models on API function selection, parameter generation, and nested API calls; second, by benchmarking state-of-the-art language models across varying levels of complexity to evaluate their performance in API function generation and parameter accuracy; and third, by proposing an enhanced API routing method that combines general-purpose large language models for API selection with fine-tuned models for parameter generation and some prompt engineering approach. These approaches lead to substantial improvements in handling complex API tasks, offering practical advancements for real-world API-driven chatbot systems.

[Arxiv](https://arxiv.org/abs/2501.05255)