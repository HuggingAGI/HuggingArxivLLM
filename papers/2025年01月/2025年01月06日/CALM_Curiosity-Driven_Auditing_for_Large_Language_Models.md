# CALM: 好奇心驱动的大型语言模型审计

发布时间：2025年01月06日

`Agent

理由：这篇论文主要讨论的是如何利用好奇心驱动的强化学习方法来审计大型语言模型（LLMs），特别是通过训练一个审计代理（Agent）来发现目标LLM的有害和有偏见的输入-输出对。研究的核心是开发一个能够自主探索和发现问题的Agent，而不是直接讨论LLM的理论基础、应用场景或检索增强生成（RAG）技术。因此，这篇论文最适合归类为Agent。` `人工智能`

> CALM: Curiosity-Driven Auditing for Large Language Models

# 摘要

> # 审计大型语言模型（LLMs）是一项关键且具有挑战性的任务。本研究专注于审计无法访问参数的黑盒LLMs，仅能访问其服务。我们将这种审计视为黑盒优化问题，目标是自动发现目标LLMs的输入-输出对，这些对表现出非法、不道德或不安全的行为。例如，寻找无毒输入但目标LLM响应为有毒输出，或诱导目标LLM产生包含政治敏感个体的幻觉响应。由于可行点稀缺、提示空间离散及搜索空间巨大，这种黑盒优化极具挑战性。为此，我们提出了好奇心驱动的审计大型语言模型（CALM），利用内在动机的强化学习微调LLM作为审计代理，以发现目标LLM潜在的有害和有偏见的输入-输出对。CALM成功识别了涉及名人的贬损性完成，并在黑盒设置下发现了引发特定名称的输入。这项工作为审计黑盒LLMs提供了有前景的方向。代码可在https://github.com/x-zheng16/CALM.git获取。

> Auditing Large Language Models (LLMs) is a crucial and challenging task. In this study, we focus on auditing black-box LLMs without access to their parameters, only to the provided service. We treat this type of auditing as a black-box optimization problem where the goal is to automatically uncover input-output pairs of the target LLMs that exhibit illegal, immoral, or unsafe behaviors. For instance, we may seek a non-toxic input that the target LLM responds to with a toxic output or an input that induces the hallucinative response from the target LLM containing politically sensitive individuals. This black-box optimization is challenging due to the scarcity of feasible points, the discrete nature of the prompt space, and the large search space. To address these challenges, we propose Curiosity-Driven Auditing for Large Language Models (CALM), which uses intrinsically motivated reinforcement learning to finetune an LLM as the auditor agent to uncover potential harmful and biased input-output pairs of the target LLM. CALM successfully identifies derogatory completions involving celebrities and uncovers inputs that elicit specific names under the black-box setting. This work offers a promising direction for auditing black-box LLMs. Our code is available at https://github.com/x-zheng16/CALM.git.

[Arxiv](https://arxiv.org/abs/2501.02997)