# 揭秘防护罩：大型语言模型中的防护栏识别

发布时间：2025年02月03日

`Agent

理由：这篇论文主要讨论的是通过对抗性提示查询AI代理来识别候选护栏的存在，这涉及到与AI代理的交互和测试，属于Agent领域的研究。` `人工智能`

> Peering Behind the Shield: Guardrail Identification in Large Language Models

# 摘要

> 随着大型语言模型的兴起，人机对话备受瞩目。为防止滥用，诸如输入/输出护栏和安全对齐等技术应运而生。然而，识别这些护栏的能力对对抗性利用和红队审计至关重要。本文提出了一种新方法AP-Test，通过护栏特定的对抗性提示查询AI代理，以识别候选护栏的存在。在多种场景下对四个候选护栏的实验验证了该方法的有效性，消融研究则进一步揭示了损失项等设计组件的重要性。

> Human-AI conversations have gained increasing attention since the era of large language models. Consequently, more techniques, such as input/output guardrails and safety alignment, are proposed to prevent potential misuse of such Human-AI conversations. However, the ability to identify these guardrails has significant implications, both for adversarial exploitation and for auditing purposes by red team operators. In this work, we propose a novel method, AP-Test, which identifies the presence of a candidate guardrail by leveraging guardrail-specific adversarial prompts to query the AI agent. Extensive experiments of four candidate guardrails under diverse scenarios showcase the effectiveness of our method. The ablation study further illustrates the importance of the components we designed, such as the loss terms.

[Arxiv](https://arxiv.org/abs/2502.01241)