# 快速、可靠且安全的编程语言，专为支持代码操作的LLM代理设计

发布时间：2025年06月13日

`Agent` `智能体` `编程语言`

> A Fast, Reliable, and Secure Programming Language for LLM Agents with Code Actions

# 摘要

> 现代大型语言模型（LLMs）通常作为智能体部署，通过自适应调用外部工具来解决问题。与直接调用工具相比，LLMs编写代码来执行工具调用更为高效，这使它们能够自动生成复杂的控制流，例如条件判断和循环。这些代码操作通常以Python代码形式提供，因为LLMs在Python方面非常熟练；然而，Python可能并非理想选择，因为其内置支持在性能、安全性和可靠性方面有限。我们提出了一种名为Quasar的新编程语言用于代码操作，它具有以下优势：(1) 自动并行化以提升性能，(2) 不确定性量化以提高可靠性和缓解幻觉，(3) 安全特性使用户能够验证操作。LLMs可以使用Python的一个子集编写代码，这些代码将自动转译为Quasar。我们在视觉问答智能体ViperGPT上评估了我们的方法，应用于GQA数据集，结果表明，与使用Python操作相比，使用Quasar操作的LLMs仍保持强劲性能，同时在可能的情况下将执行时间减少42%，通过减少用户审批交互提升安全性52%，并借助符合式预测提高可靠性以实现预期的目标覆盖水平。

> Modern large language models (LLMs) are often deployed as agents, calling external tools adaptively to solve tasks. Rather than directly calling tools, it can be more effective for LLMs to write code to perform the tool calls, enabling them to automatically generate complex control flow such as conditionals and loops. Such code actions are typically provided as Python code, since LLMs are quite proficient at it; however, Python may not be the ideal language due to limited built-in support for performance, security, and reliability. We propose a novel programming language for code actions, called Quasar, which has several benefits: (1) automated parallelization to improve performance, (2) uncertainty quantification to improve reliability and mitigate hallucinations, and (3) security features enabling the user to validate actions. LLMs can write code in a subset of Python, which is automatically transpiled to Quasar. We evaluate our approach on the ViperGPT visual question answering agent, applied to the GQA dataset, demonstrating that LLMs with Quasar actions instead of Python actions retain strong performance, while reducing execution time when possible by 42%, improving security by reducing user approval interactions when possible by 52%, and improving reliability by applying conformal prediction to achieve a desired target coverage level.

[Arxiv](https://arxiv.org/abs/2506.12202)