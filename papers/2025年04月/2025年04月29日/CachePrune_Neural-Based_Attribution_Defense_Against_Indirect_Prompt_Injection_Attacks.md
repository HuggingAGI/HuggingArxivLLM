# CachePrune：基于神经网络的归因防御间接提示注入攻击

发布时间：2025年04月29日

`LLM应用` `人工智能安全`

> CachePrune: Neural-Based Attribution Defense Against Indirect Prompt Injection Attacks

# 摘要

> 大型语言模型（LLMs）易受间接提示注入攻击，这类攻击会使模型偏离用户指令，执行隐藏任务。这一漏洞源于模型无法区分提示中的数据与指令。本文提出 CachePrune，通过识别并剪除输入提示上下文 KV 缓存中的任务触发神经元来防御此类攻击。剪除这些神经元后，模型将提示文本仅视为数据，而非指令。我们通过基于直接偏好优化（DPO）目标上界诱导的损失函数进行特征归因识别这些神经元。实验表明，仅需少量样本即可实现有效特征归因。我们进一步利用指令遵循中的触发效应提升特征归因质量。我们的方法无需修改原始提示格式，也不增加额外的 LLM 调用。实验结果表明，CachePrune 显著降低了攻击成功率，同时保持了响应质量。本文旨在通过开发更安全可靠的 AI 系统，防御间接提示注入攻击。

> Large Language Models (LLMs) are identified as being susceptible to indirect prompt injection attack, where the model undesirably deviates from user-provided instructions by executing tasks injected in the prompt context. This vulnerability stems from LLMs' inability to distinguish between data and instructions within a prompt. In this paper, we propose CachePrune that defends against this attack by identifying and pruning task-triggering neurons from the KV cache of the input prompt context. By pruning such neurons, we encourage the LLM to treat the text spans of input prompt context as only pure data, instead of any indicator of instruction following. These neurons are identified via feature attribution with a loss function induced from an upperbound of the Direct Preference Optimization (DPO) objective. We show that such a loss function enables effective feature attribution with only a few samples. We further improve on the quality of feature attribution, by exploiting an observed triggering effect in instruction following. Our approach does not impose any formatting on the original prompt or introduce extra test-time LLM calls. Experiments show that CachePrune significantly reduces attack success rates without compromising the response quality. Note: This paper aims to defend against indirect prompt injection attacks, with the goal of developing more secure and robust AI systems.

[Arxiv](https://arxiv.org/abs/2504.21228)