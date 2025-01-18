# 大型语言模型在主观任务中的视角转换

发布时间：2025年01月15日

`LLM应用

理由：这篇论文主要讨论了如何通过“视角转换推理”（RPT）方法来改进大型语言模型（LLMs）在主观任务上的表现。该方法通过动态选择不同的视角（如直接、角色和第三人称视角）来优化LLMs的回应。这属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `人工智能`

> Perspective Transition of Large Language Models for Solving Subjective Tasks

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域掀起了一场革命，推动了各种任务的显著进展。然而，与常识推理和算术问答等客观任务不同，LLMs在主观任务上的表现仍有局限，其中对特定问题的视角在更好地理解上下文和给出恰当回应方面至关重要。例如，在某些场景中，LLMs从专家视角回答时表现更佳，可能激发其相关领域知识；而在另一些场景中，从第三人称视角回答则能提供更准确的回应，帮助更全面地理解问题并减轻固有偏见。本文提出了一种基于上下文学习的“视角转换推理”（RPT）方法，使LLMs能够动态选择直接、角色和第三人称视角，以最佳方式解决主观问题。通过在GPT-4、GPT-3.5、Llama-3和Qwen-2等闭源和开源LLMs上对12个主观任务的广泛实验，RPT方法超越了思维链提示和专家提示等单一固定视角方法，展现了LLMs如何灵活调整视角，为不同问题提供细致且上下文适配的回应。

> Large language models (LLMs) have revolutionized the field of natural language processing, enabling remarkable progress in various tasks. Different from objective tasks such as commonsense reasoning and arithmetic question-answering, the performance of LLMs on subjective tasks is still limited, where the perspective on the specific problem plays crucial roles for better interpreting the context and giving proper response. For example, in certain scenarios, LLMs may perform better when answering from an expert role perspective, potentially eliciting their relevant domain knowledge. In contrast, in some scenarios, LLMs may provide more accurate responses when answering from a third-person standpoint, enabling a more comprehensive understanding of the problem and potentially mitigating inherent biases. In this paper, we propose Reasoning through Perspective Transition (RPT), a method based on in-context learning that enables LLMs to dynamically select among direct, role, and third-person perspectives for the best way to solve corresponding subjective problem. Through extensive experiments on totally 12 subjective tasks by using both closed-source and open-source LLMs including GPT-4, GPT-3.5, Llama-3, and Qwen-2, our method outperforms widely used single fixed perspective based methods such as chain-of-thought prompting and expert prompting, highlights the intricate ways that LLMs can adapt their perspectives to provide nuanced and contextually appropriate responses for different problems.

[Arxiv](https://arxiv.org/abs/2501.09265)