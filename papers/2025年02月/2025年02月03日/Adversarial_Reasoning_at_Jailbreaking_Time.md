# 越狱时刻的对抗推理

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要研究大型语言模型（LLMs）的失败案例，特别是模型越狱任务，并提出了一种基于测试时计算的对抗性推理方法。这些内容涉及对LLMs的理论理解和漏洞分析，属于对LLMs的理论研究范畴，因此分类为“LLM理论”。` `人工智能` `模型安全`

> Adversarial Reasoning at Jailbreaking Time

# 摘要

> 随着大型语言模型（LLMs）能力的提升和广泛应用，研究其失败案例变得愈发重要。近期在标准化、测量和扩展测试时计算方面的突破，为优化模型在复杂任务中的表现提供了新方法。本文将这些进展应用于模型越狱任务，即从对齐的LLMs中诱导出有害响应。我们提出了一种基于测试时计算的对抗性推理方法，成功实现了对多个对齐LLMs的最先进攻击成功率（ASR），包括那些通过牺牲推理时计算来增强对抗鲁棒性的模型。这一方法为理解LLM漏洞提供了新视角，为构建更强大、可信赖的AI系统奠定了基础。

> As large language models (LLMs) are becoming more capable and widespread, the study of their failure cases is becoming increasingly important. Recent advances in standardizing, measuring, and scaling test-time compute suggest new methodologies for optimizing models to achieve high performance on hard tasks. In this paper, we apply these advances to the task of model jailbreaking: eliciting harmful responses from aligned LLMs. We develop an adversarial reasoning approach to automatic jailbreaking via test-time computation that achieves SOTA attack success rates (ASR) against many aligned LLMs, even the ones that aim to trade inference-time compute for adversarial robustness. Our approach introduces a new paradigm in understanding LLM vulnerabilities, laying the foundation for the development of more robust and trustworthy AI systems.

[Arxiv](https://arxiv.org/abs/2502.01633)