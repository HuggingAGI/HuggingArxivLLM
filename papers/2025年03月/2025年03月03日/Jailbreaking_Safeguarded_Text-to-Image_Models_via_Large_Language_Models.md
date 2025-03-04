# 通过大型语言模型破解受保护的文本到图像模型

发布时间：2025年03月03日

`LLM应用` `生成模型` `人工智能安全`

> Jailbreaking Safeguarded Text-to-Image Models via Large Language Models

# 摘要

> 文本到图像模型在生成有害内容（如色情图像）方面存在风险，尤其是在处理不安全提示时。为应对这一问题，通常会在模型中添加安全过滤器，或对模型本身进行调整以减少有害输出。然而，攻击者若精心设计对抗性提示，仍可绕过这些安全措施。本研究提出了一种名为PromptTune的方法，通过微调大型语言模型，实现对具有安全护栏的文本到图像模型的越狱。与需要反复查询目标模型的其他基于查询的攻击不同，我们的方法在微调AttackLLM后，能高效生成对抗性提示。我们在三个不安全提示数据集和五种安全护栏上进行了测试，结果显示，PromptTune不仅有效绕过了安全护栏，还超越了现有无框攻击，同时为其他基于查询的攻击提供了支持。

> Text-to-Image models may generate harmful content, such as pornographic images, particularly when unsafe prompts are submitted. To address this issue, safety filters are often added on top of text-to-image models, or the models themselves are aligned to reduce harmful outputs. However, these defenses remain vulnerable when an attacker strategically designs adversarial prompts to bypass these safety guardrails. In this work, we propose PromptTune, a method to jailbreak text-to-image models with safety guardrails using a fine-tuned large language model. Unlike other query-based jailbreak attacks that require repeated queries to the target model, our attack generates adversarial prompts efficiently after fine-tuning our AttackLLM. We evaluate our method on three datasets of unsafe prompts and against five safety guardrails. Our results demonstrate that our approach effectively bypasses safety guardrails, outperforms existing no-box attacks, and also facilitates other query-based attacks.

[Arxiv](https://arxiv.org/abs/2503.01839)