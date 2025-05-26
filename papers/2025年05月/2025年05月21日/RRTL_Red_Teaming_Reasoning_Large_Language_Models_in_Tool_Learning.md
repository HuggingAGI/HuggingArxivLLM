# RRTL：红队推理测试大型语言模型在工具学习中的探索与应用

发布时间：2025年05月21日

`LLM应用` `人工智能` `模型安全`

> RRTL: Red Teaming Reasoning Large Language Models in Tool Learning

# 摘要

> 工具学习在增强大型语言模型（LLMs）能力的同时，也带来了显著的安全隐患。先前研究表明，传统LLMs在工具学习过程中存在多种漏洞。然而，对于新出现的推理型大语言模型（RLLMs），如DeepSeek-R1，在工具学习环境下的安全性仍鲜有研究。为填补这一空白，我们提出了RRTL，一种专门用于评估RLLMs在工具学习中表现的红队方法。该方法整合了两项创新策略：(1) 识别欺骗性威胁，评估模型在隐藏不安全工具使用及其潜在风险方面的表现；(2) 通过链式思维（CoT）提示强制调用工具。我们的方法还包含针对传统LLMs的基准测试。我们对七种主流RLLMs进行了全面评估，发现了三个关键点：(1) RLLMs的安全性能总体优于传统LLMs，但不同模型间仍存在显著差异；(2) RLLMs可能带来严重欺骗风险，常常未能披露工具使用情况或警告潜在风险；(3) CoT提示揭示了RLLMs在多语言安全方面的漏洞。我们的研究为提升RLLMs在工具学习中的安全性提供了重要见解。

> While tool learning significantly enhances the capabilities of large language models (LLMs), it also introduces substantial security risks. Prior research has revealed various vulnerabilities in traditional LLMs during tool learning. However, the safety of newly emerging reasoning LLMs (RLLMs), such as DeepSeek-R1, in the context of tool learning remains underexplored. To bridge this gap, we propose RRTL, a red teaming approach specifically designed to evaluate RLLMs in tool learning. It integrates two novel strategies: (1) the identification of deceptive threats, which evaluates the model's behavior in concealing the usage of unsafe tools and their potential risks; and (2) the use of Chain-of-Thought (CoT) prompting to force tool invocation. Our approach also includes a benchmark for traditional LLMs. We conduct a comprehensive evaluation on seven mainstream RLLMs and uncover three key findings: (1) RLLMs generally achieve stronger safety performance than traditional LLMs, yet substantial safety disparities persist across models; (2) RLLMs can pose serious deceptive risks by frequently failing to disclose tool usage and to warn users of potential tool output risks; (3) CoT prompting reveals multi-lingual safety vulnerabilities in RLLMs. Our work provides important insights into enhancing the security of RLLMs in tool learning.

[Arxiv](https://arxiv.org/abs/2505.17106)