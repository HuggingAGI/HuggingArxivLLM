# 评估LLMs在解决实际项目可维护性问题中的效果

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在修复代码可维护性问题上的应用效果，评估了不同提示策略下LLMs的表现，并分析了其在实际应用中的局限性。因此，它属于LLM在实际问题中的应用研究，符合“LLM应用”这一分类。` `软件工程` `代码维护`

> Evaluating the Effectiveness of LLMs in Fixing Maintainability Issues in Real-World Projects

# 摘要

> 大型语言模型（LLMs）在解决编码问题上备受关注，但其修复代码可维护性的效果尚不明确。本研究评估了LLMs处理10个GitHub仓库中127个可维护性问题的能力。我们采用零-shot提示测试Copilot Chat和Llama 3.1，并对Llama进行少量-shot提示。评估LLM生成的解决方案时，重点关注编译错误、测试失败及新出现的可维护性问题。少量-shot提示的Llama成功修复了44.9%的方法，而Copilot Chat和Llama零-shot分别修复了32.29%和30%的方法。然而，多数解决方案引入了错误或新的可维护性问题。我们还进行了45人参与的人类研究，评估51个LLM生成方案的可读性。结果显示，68.63%的参与者认为可读性有所提升。总体来看，尽管LLMs在修复可维护性问题方面展现出潜力，但其引入的错误揭示了当前的局限性。

> Large Language Models (LLMs) have gained attention for addressing coding problems, but their effectiveness in fixing code maintainability remains unclear. This study evaluates LLMs capability to resolve 127 maintainability issues from 10 GitHub repositories. We use zero-shot prompting for Copilot Chat and Llama 3.1, and few-shot prompting with Llama only. The LLM-generated solutions are assessed for compilation errors, test failures, and new maintainability problems. Llama with few-shot prompting successfully fixed 44.9% of the methods, while Copilot Chat and Llama zero-shot fixed 32.29% and 30%, respectively. However, most solutions introduced errors or new maintainability issues. We also conducted a human study with 45 participants to evaluate the readability of 51 LLM-generated solutions. The human study showed that 68.63% of participants observed improved readability. Overall, while LLMs show potential for fixing maintainability issues, their introduction of errors highlights their current limitations.

[Arxiv](https://arxiv.org/abs/2502.02368)