# DeepSeek 的隐秘威胁：针对 CoT 模型安全对齐的微调攻击

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）在微调攻击下的表现，特别是思维链推理模型对微调攻击的脆弱性。研究内容涉及模型的安全性和道德部署，属于对LLM的理论分析和安全性研究，因此归类为“LLM理论”。` `人工智能` `模型安全`

> The dark deep side of DeepSeek: Fine-tuning attacks against the safety alignment of CoT-enabled models

# 摘要

> 大型语言模型在预训练阶段通常使用海量数据进行训练，这些数据可能包含潜在的有害信息。微调攻击可通过诱导模型揭示这些行为，进而生成有害内容。本文聚焦于基于思维链推理的模型 DeepSeek 在微调攻击下的表现，探讨微调如何操纵模型输出，加剧其响应的危害性，并研究思维链推理与对抗性输入之间的相互作用。通过这项研究，我们揭示了思维链推理模型对微调攻击的脆弱性，及其对模型安全与道德部署的影响。

> Large language models are typically trained on vast amounts of data during the pre-training phase, which may include some potentially harmful information. Fine-tuning attacks can exploit this by prompting the model to reveal such behaviours, leading to the generation of harmful content. In this paper, we focus on investigating the performance of the Chain of Thought based reasoning model, DeepSeek, when subjected to fine-tuning attacks. Specifically, we explore how fine-tuning manipulates the model's output, exacerbating the harmfulness of its responses while examining the interaction between the Chain of Thought reasoning and adversarial inputs. Through this study, we aim to shed light on the vulnerability of Chain of Thought enabled models to fine-tuning attacks and the implications for their safety and ethical deployment.

[Arxiv](https://arxiv.org/abs/2502.01225)