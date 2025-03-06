# 大型语言模型中的Token级别隐私保护

发布时间：2025年03月05日

`LLM应用` `隐私保护`

> Token-Level Privacy in Large Language Models

# 摘要

> 将语言模型作为远程服务使用时，需将私人信息传输给外部提供商，这一过程引发了重大的隐私担忧。这不仅可能导致敏感数据暴露给不可信的服务提供商，还可能被窃听者拦截。现有的自然语言处理（NLP）交互隐私保护方法主要依赖语义相似性，忽略了上下文信息的作用。在本研究中，我们引入了dchi-stencil，这是一种新型的基于令牌的隐私保护机制。它在整合上下文和语义信息的同时，确保在dchi差分隐私框架下的强隐私保证，实现了2epsilon-dchi隐私。通过结合语义和上下文细微差别，dchi-stencil在隐私和效用之间实现了强大的平衡。我们使用最先进的语言模型和多样化的数据集对dchi-stencil进行了评估。与现有方法相比，它在效用和隐私之间的权衡上达到了相当甚至更好的效果。这项研究凸显了dchi-stencil在为现代高风险应用中的隐私保护NLP设定新标准的潜力。

> The use of language models as remote services requires transmitting private information to external providers, raising significant privacy concerns. This process not only risks exposing sensitive data to untrusted service providers but also leaves it vulnerable to interception by eavesdroppers. Existing privacy-preserving methods for natural language processing (NLP) interactions primarily rely on semantic similarity, overlooking the role of contextual information. In this work, we introduce dchi-stencil, a novel token-level privacy-preserving mechanism that integrates contextual and semantic information while ensuring strong privacy guarantees under the dchi differential privacy framework, achieving 2epsilon-dchi-privacy. By incorporating both semantic and contextual nuances, dchi-stencil achieves a robust balance between privacy and utility. We evaluate dchi-stencil using state-of-the-art language models and diverse datasets, achieving comparable and even better trade-off between utility and privacy compared to existing methods. This work highlights the potential of dchi-stencil to set a new standard for privacy-preserving NLP in modern, high-risk applications.

[Arxiv](https://arxiv.org/abs/2503.03652)