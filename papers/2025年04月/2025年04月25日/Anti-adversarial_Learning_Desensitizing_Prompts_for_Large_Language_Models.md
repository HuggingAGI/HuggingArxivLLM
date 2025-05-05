# 对抗性学习的反制之道：让大模型提示更“钝感”

发布时间：2025年04月25日

`LLM应用

理由：这篇论文讨论了如何在大型语言模型（LLMs）中保护用户提示中的隐私，并提出了一种新的方法PromptObfus。该方法通过脱敏处理来防止隐私泄露，同时保持模型的性能。这属于LLM的应用层面，因为它专注于如何在实际应用中解决隐私保护的问题。`

> Anti-adversarial Learning: Desensitizing Prompts for Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，保护用户提示中的隐私变得至关重要，因为提示内容可能泄露隐私和敏感数据给云端的LLMs。传统技术如同态加密、安全多方计算和联邦学习因计算成本高昂及用户参与需求，面临诸多挑战，限制了其在LLM场景中的应用。本文中，我们提出了一种名为PromptObfus的新方法，用于对LLM提示进行脱敏处理。PromptObfus的核心思想是“反对抗性”学习，通过扰动提示中的隐私词汇，模糊敏感信息，同时保持模型预测的稳定性。具体而言，PromptObfus将提示脱敏任务转化为一个遮蔽语言建模任务，用[MASK]令牌替换隐私敏感词汇。随后，训练一个脱敏模型为每个遮蔽位置生成候选替换词。这些候选词基于代理模型的梯度反馈进行选择，以确保对任务输出的干扰最小。我们在三个NLP任务上验证了我们方法的有效性。结果显示，PromptObfus成功防止了远程LLMs的隐私推断，同时保持了任务性能。

> With the widespread use of LLMs, preserving privacy in user prompts has become crucial, as prompts risk exposing privacy and sensitive data to the cloud LLMs. Traditional techniques like homomorphic encryption, secure multi-party computation, and federated learning face challenges due to heavy computational costs and user participation requirements, limiting their applicability in LLM scenarios. In this paper, we propose PromptObfus, a novel method for desensitizing LLM prompts. The core idea of PromptObfus is "anti-adversarial" learning, which perturbs privacy words in the prompt to obscure sensitive information while retaining the stability of model predictions. Specifically, PromptObfus frames prompt desensitization as a masked language modeling task, replacing privacy-sensitive terms with a [MASK] token. A desensitization model is trained to generate candidate replacements for each masked position. These candidates are subsequently selected based on gradient feedback from a surrogate model, ensuring minimal disruption to the task output. We demonstrate the effectiveness of our approach on three NLP tasks. Results show that PromptObfus effectively prevents privacy inference from remote LLMs while preserving task performance.

[Arxiv](https://arxiv.org/abs/2505.01273)