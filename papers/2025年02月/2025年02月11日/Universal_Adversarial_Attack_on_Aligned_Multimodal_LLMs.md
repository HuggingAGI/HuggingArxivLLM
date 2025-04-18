# 通用对抗攻击：对齐的多模态大型语言模型

发布时间：2025年02月11日

`LLM应用` `多模态模型` `对抗攻击`

> Universal Adversarial Attack on Aligned Multimodal LLMs

# 摘要

> 我们提出了一种针对多模态大型语言模型 (LLMs) 的通用对抗攻击方法，通过一张精心优化的图像，能够在多种查询甚至多个模型上绕过对齐防护机制。通过反向传播到视觉编码器和语言头，我们生成了一张合成图像，迫使模型以特定短语（例如“当然，这里就是”）或不安全内容（即使是恶意提示）进行响应。在 SafeBench 基准测试中，我们的方法相较于现有基线（包括仅文本的通用提示，例如对某些模型可达93%）取得了显著更高的攻击成功率。我们还通过同时训练多个多模态 LLM 并测试未见架构，展示了跨模型的迁移能力。此外，我们方法的多答案变体能够生成更自然（但仍然恶意）的响应。这些发现突显了当前多模态对齐中的关键漏洞，并呼吁更强大的对抗防御机制。我们将在 Apache-2.0 许可证下发布代码和数据集。警告：本文中多模态 LLM 生成的一些内容可能会冒犯某些读者。


> We propose a universal adversarial attack on multimodal Large Language Models (LLMs) that leverages a single optimized image to override alignment safeguards across diverse queries and even multiple models. By backpropagating through the vision encoder and language head, we craft a synthetic image that forces the model to respond with a targeted phrase (e.g., ''Sure, here it is'') or otherwise unsafe content-even for harmful prompts. In experiments on the SafeBench benchmark, our method achieves significantly higher attack success rates than existing baselines, including text-only universal prompts (e.g., up to 93% on certain models). We further demonstrate cross-model transferability by training on several multimodal LLMs simultaneously and testing on unseen architectures. Additionally, a multi-answer variant of our approach produces more natural-sounding (yet still malicious) responses. These findings underscore critical vulnerabilities in current multimodal alignment and call for more robust adversarial defenses. We will release code and datasets under the Apache-2.0 license. Warning: some content generated by Multimodal LLMs in this paper may be offensive to some readers.

[Arxiv](https://arxiv.org/abs/2502.07987)