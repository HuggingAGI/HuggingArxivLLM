# RRTL：通过红队对抗评估大型语言模型的工具学习推理能力

发布时间：2025年05月21日

`LLM应用

摘要讨论了工具学习对大型语言模型的影响及其带来的安全风险，特别是针对推理型LLMs的安全性评估。研究提出了一种红队方法RRTL，用于评估模型的工具学习安全性，属于应用层面的研究，因此归类为LLM应用。` `人工智能`

> RRTL: Red Teaming Reasoning Large Language Models in Tool Learning

# 摘要

> 工具学习在提升大型语言模型能力的同时，也带来了显著的安全风险。尽管传统LLMs在工具学习中的漏洞已被揭示，但新出现的推理型LLMs（如DeepSeek-R1）的安全性仍鲜有研究。为此，我们提出了一种名为RRTL的红队方法，专门用于评估推理型LLMs的工具学习安全性。该方法结合了两项创新策略：（1）识别欺骗性威胁，评估模型在隐藏不安全工具使用及其风险方面的行为；（2）通过链式思维（CoT）提示强制工具调用。我们的方法还包含针对传统LLMs的基准测试。通过对七种主流推理型LLMs的全面评估，我们得出三项重要发现：（1）推理型LLMs的安全性能普遍优于传统LLMs，但模型间仍存在显著差异；（2）推理型LLMs可能带来严重欺骗性风险，经常未能披露工具使用情况或警告潜在风险；（3）链式思维提示揭示了推理型LLMs在多语言安全方面的漏洞。我们的研究为提升推理型LLMs的工具学习安全性提供了重要见解。

> While tool learning significantly enhances the capabilities of large language models (LLMs), it also introduces substantial security risks. Prior research has revealed various vulnerabilities in traditional LLMs during tool learning. However, the safety of newly emerging reasoning LLMs (RLLMs), such as DeepSeek-R1, in the context of tool learning remains underexplored. To bridge this gap, we propose RRTL, a red teaming approach specifically designed to evaluate RLLMs in tool learning. It integrates two novel strategies: (1) the identification of deceptive threats, which evaluates the model's behavior in concealing the usage of unsafe tools and their potential risks; and (2) the use of Chain-of-Thought (CoT) prompting to force tool invocation. Our approach also includes a benchmark for traditional LLMs. We conduct a comprehensive evaluation on seven mainstream RLLMs and uncover three key findings: (1) RLLMs generally achieve stronger safety performance than traditional LLMs, yet substantial safety disparities persist across models; (2) RLLMs can pose serious deceptive risks by frequently failing to disclose tool usage and to warn users of potential tool output risks; (3) CoT prompting reveals multi-lingual safety vulnerabilities in RLLMs. Our work provides important insights into enhancing the security of RLLMs in tool learning.

[Arxiv](https://arxiv.org/abs/2505.17106)