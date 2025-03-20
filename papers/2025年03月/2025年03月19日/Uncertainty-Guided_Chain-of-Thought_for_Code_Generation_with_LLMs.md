# 基于不确定性引导的思维链方法用于大语言模型的代码生成

发布时间：2025年03月19日

`LLM应用` `软件工程`

> Uncertainty-Guided Chain-of-Thought for Code Generation with LLMs

# 摘要

> 链式思维（CoT）推理是提升大型语言模型（LLMs）代码生成能力的有效技术，但现有方法存在“过度思考”问题。具体表现为LLMs持续应用推理策略，而未充分考虑任务复杂性，导致在简单问题上过度分配计算资源，甚至生成错误代码。针对这一问题，我们提出了基于不确定性的链式思维（UnCert-CoT），通过整合不确定性感知的CoT推理机制，优化计算资源分配，重点关注LLMs易错环节。我们设计了两种不确定性度量方法：基于熵和基于概率差的方法。当不确定性高时，UnCert-CoT会生成多个推理路径并选择最优解；当不确定性低时，LLM直接生成代码。这种机制使LLMs能够高效处理复杂任务并在简单场景中避免冗余步骤。实验结果表明，UnCert-CoT在MHPP基准测试中将PassRate准确率提升了6.1%，特别是在传统LLMs易错场景中表现突出。

> Chain-of-Thought (CoT) reasoning has been demonstrated as an effective technique for improving the problem-solving capabilities of large language models (LLMs) in the context of code generation. However, existing CoT methods often exhibit a tendency toward "overthinking", where the LLM consistently applies reasoning strategies without adequately considering the task's underlying complexity. This results in the LLMs allocating excessive computational resources, in terms of tokens, to relatively simple tasks or problems where the correct answer is already evident. Additionally, this overthinking may lead LLMs down incorrect reasoning paths, resulting in incorrect code generation. In this paper, we introduce UnCertainty-Aware Chain-of-Thought (UnCert-CoT), an LLM-based approach designed to enhance code generation by incorporating an uncertainty-aware CoT reasoning mechanism, which focuses computational resources on targeting points where LLMs are more prone to error. We propose two confidence-based uncertainty measures: Entropy-based and Probability Differential-based methods. When uncertainty is high, UnCert-CoT activates CoT-decoding to generate multiple reasoning paths and selects the final code that exhibits the highest likelihood of correctness. In contrast, LLM directly generates the code when uncertainty is low. This uncertainty judgment mechanism allows LLMs to prioritize complex tasks and avoid unnecessary steps in simpler cases, thereby improving overall efficiency and accuracy in code generation. Our experimental results demonstrate that UnCert-CoT significantly enhances code generation accuracy on challenging benchmark MHPP(Mostly Hard Python Problems), it achieves improvements up to 6.1% on PassRate accuracy, particularly in situations where traditional LLMs are prone to errors.

[Arxiv](https://arxiv.org/abs/2503.15341)