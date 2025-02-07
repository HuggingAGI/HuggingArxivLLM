# 分层思维链提示：多智能体LLM系统的可解释性综合方案

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了如何通过改进思维链（CoT）提示来提升大型语言模型（LLMs）在复杂任务中的表现。具体来说，提出了分层思维链（Layered-CoT）提示，这一框架通过分层推理和外部检查来提高透明度和正确性。这些改进措施直接应用于LLMs的实际使用场景，如医疗分诊、金融风险评估和敏捷工程，因此属于LLM应用的范畴。`

> Layered Chain-of-Thought Prompting for Multi-Agent LLM Systems: A Comprehensive Approach to Explainable Large Language Models

# 摘要

> 大型语言模型（LLMs）通过思维链（CoT）提示提供逐步推理，显著提升了复杂任务的表现。然而，传统CoT常无法完全验证中间推理，且可能产生误导性解释。为此，我们提出了分层思维链（Layered-CoT）提示，这一创新框架将推理过程系统划分为多个层次，每层均接受外部检查并可选择性获取用户反馈。我们深入探讨了关键概念，并通过医疗分诊、金融风险评估和敏捷工程三个场景，展示了Layered-CoT在透明度、正确性和用户参与度上的优势。结合近期arXiv论文中关于交互式可解释性、多智能体框架及智能体协作的研究，Layered-CoT为高风险领域提供了更可靠、基于事实的解释路径。

> Large Language Models (LLMs) leverage chain-of-thought (CoT) prompting to provide step-by-step rationales, improving performance on complex tasks. Despite its benefits, vanilla CoT often fails to fully verify intermediate inferences and can produce misleading explanations. In this work, we propose Layered Chain-of-Thought (Layered-CoT) Prompting, a novel framework that systematically segments the reasoning process into multiple layers, each subjected to external checks and optional user feedback. We expand on the key concepts, present three scenarios -- medical triage, financial risk assessment, and agile engineering -- and demonstrate how Layered-CoT surpasses vanilla CoT in terms of transparency, correctness, and user engagement. By integrating references from recent arXiv papers on interactive explainability, multi-agent frameworks, and agent-based collaboration, we illustrate how Layered-CoT paves the way for more reliable and grounded explanations in high-stakes domains.

[Arxiv](https://arxiv.org/abs/2501.18645)