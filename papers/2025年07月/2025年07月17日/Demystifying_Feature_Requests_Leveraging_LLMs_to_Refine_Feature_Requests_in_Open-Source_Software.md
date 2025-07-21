# 解密功能请求：借助 LLMs 提升开源软件中的功能需求质量

发布时间：2025年07月17日

`LLM应用` `软件工程`

> Demystifying Feature Requests: Leveraging LLMs to Refine Feature Requests in Open-Source Software

# 摘要

> 软件应用在各行各业的普及推动了行业的快速发展，但快速变化的市场需求也使得软件需求不断演变。这些需求通常以自然语言形式呈现，但常常存在模糊不清、不够完整等缺陷，解读起来颇具挑战。传统验证方法虽能帮助澄清这些缺陷，但在开源软件等分散环境中并不适用。本文提出了一种基于大型语言模型（LLMs）的新方法，用于检测和修复特性请求中的自然语言缺陷。该方法能够自动识别模糊和不完整的请求，并生成澄清问题，提升其对开发者的实用性。我们通过真实世界的OSS特性请求验证了该方法的有效性，并与人工标注进行对比。此外，我们还采访了GitHub开发者，深入了解他们对自然语言缺陷的看法、应对策略及其对下游软件工程任务的影响。

> The growing popularity and widespread use of software applications (apps) across various domains have driven rapid industry growth. Along with this growth, fast-paced market changes have led to constantly evolving software requirements. Such requirements are often grounded in feature requests and enhancement suggestions, typically provided by users in natural language (NL). However, these requests often suffer from defects such as ambiguity and incompleteness, making them challenging to interpret. Traditional validation methods (e.g., interviews and workshops) help clarify such defects but are impractical in decentralized environments like open-source software (OSS), where change requests originate from diverse users on platforms like GitHub. This paper proposes a novel approach leveraging Large Language Models (LLMs) to detect and refine NL defects in feature requests. Our approach automates the identification of ambiguous and incomplete requests and generates clarification questions (CQs) to enhance their usefulness for developers. To evaluate its effectiveness, we apply our method to real-world OSS feature requests and compare its performance against human annotations. In addition, we conduct interviews with GitHub developers to gain deeper insights into their perceptions of NL defects, the strategies they use to address these defects, and the impact of defects on downstream software engineering (SE) tasks.

[Arxiv](https://arxiv.org/abs/2507.13555)