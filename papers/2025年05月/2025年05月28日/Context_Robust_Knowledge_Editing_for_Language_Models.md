# 语言模型的上下文鲁棒知识编辑

发布时间：2025年05月28日

`LLM应用` `人工智能`

> Context Robust Knowledge Editing for Language Models

# 摘要

> 知识编辑（KE）方法为修改大型语言模型中的知识提供了一种高效途径。当前的KE评估通常仅通过考虑编辑后的知识，而不涉及任何前置上下文来评估编辑的成功。然而，在实际应用中，前置上下文常常会触发原始知识的检索，从而削弱预期的编辑效果。为了解决这一问题，我们开发了CHED——一个旨在评估KE方法上下文鲁棒性的基准测试。在CHED上的评估表明，当存在前置上下文时，现有方法通常会失败。为了缓解这一不足，我们引入了CoRE，这是一种通过最小化编辑知识在模型隐藏状态中的上下文敏感性方差来增强上下文鲁棒性的KE方法。该方法不仅提高了在存在前置上下文时的编辑成功率，还保留了模型的整体能力。我们深入分析了将前置上下文作为用户 utterances 与助手 responses 引入时的不同影响，并通过解析注意力分数模式，评估了特定 token 对编辑成功的具体影响。

> Knowledge editing (KE) methods offer an efficient way to modify knowledge in large language models. Current KE evaluations typically assess editing success by considering only the edited knowledge without any preceding contexts. In real-world applications, however, preceding contexts often trigger the retrieval of the original knowledge and undermine the intended edit. To address this issue, we develop CHED -- a benchmark designed to evaluate the context robustness of KE methods. Evaluations on CHED show that they often fail when preceding contexts are present. To mitigate this shortcoming, we introduce CoRE, a KE method designed to strengthen context robustness by minimizing context-sensitive variance in hidden states of the model for edited knowledge. This method not only improves the editing success rate in situations where a preceding context is present but also preserves the overall capabilities of the model. We provide an in-depth analysis of the differing impacts of preceding contexts when introduced as user utterances versus assistant responses, and we dissect attention-score patterns to assess how specific tokens influence editing success.

[Arxiv](https://arxiv.org/abs/2505.23026)