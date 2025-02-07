# 增强大型语言模型遗忘中表示误导的鲁棒性

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要讨论了LLM（大型语言模型）的遗忘方法及其对模型鲁棒性的影响，并提出了一种新的策略（RNA）来增强模型的鲁棒性。这些内容涉及LLM的内部机制和理论改进，因此应归类为“LLM理论”。` `人工智能` `模型安全`

> Improving the Robustness of Representation Misdirection for Large Language Model Unlearning

# 摘要

> 表示误导（RM）及其变体是当前最先进的LLM遗忘方法。本文揭示，RM方法会降低模型鲁棒性，即使保留查询中仅含一个非对抗性遗忘标记，模型也会失常。我们将遗忘过程重新定义为后门攻击与防御：遗忘标记作为后门触发器，激活时会导致RM模型行为异常，类似成功的后门攻击。为此，我们提出随机噪声增强（RNA），这是一种模型和方法无关的策略，具有提升RM方法鲁棒性的理论保证。实验表明，RNA显著增强了RM模型的鲁棒性，同时提升了遗忘性能。

> Representation Misdirection (RM) and variants are established large language model (LLM) unlearning methods with state-of-the-art performance. In this paper, we show that RM methods inherently reduce models' robustness, causing them to misbehave even when a single non-adversarial forget-token is in the retain-query. Toward understanding underlying causes, we reframe the unlearning process as backdoor attacks and defenses: forget-tokens act as backdoor triggers that, when activated in retain-queries, cause disruptions in RM models' behaviors, similar to successful backdoor attacks. To mitigate this vulnerability, we propose Random Noise Augmentation -- a model and method agnostic approach with theoretical guarantees for improving the robustness of RM methods. Extensive experiments demonstrate that RNA significantly improves the robustness of RM models while enhancing the unlearning performances.

[Arxiv](https://arxiv.org/abs/2501.19202)