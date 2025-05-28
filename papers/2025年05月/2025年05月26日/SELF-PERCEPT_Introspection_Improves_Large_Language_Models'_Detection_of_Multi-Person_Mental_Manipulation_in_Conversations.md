# SELF-PERCEPT：通过自我反思，增强大型语言模型在对话中识别多人心理操控的能力

发布时间：2025年05月26日

`LLM应用` `心理学` `人工智能`

> SELF-PERCEPT: Introspection Improves Large Language Models' Detection of Multi-Person Mental Manipulation in Conversations

# 摘要

> 心理操控是一种隐蔽且普遍存在于人际交流中的虐待形式，检测心理操控显得尤为重要。然而，由于其微妙且具体情境的特点，在复杂、多轮、多人的对话中识别操控性语言仍然是大型语言模型 (LLMs) 的一大挑战。为了解决这一难题，我们推出了 MultiManip 数据集，包含 220 个平衡的多轮、多人对话，涵盖操控性和非操控性互动，所有数据均来自模拟现实场景的真人秀节目。对于操控性互动，它包含了 11 种不同的操控手段，描绘了现实生活中的场景。我们对当前先进的 LLMs（如 GPT-4o 和 Llama-3.1-8B）进行了广泛评估，采用了多种提示策略。尽管这些模型能力强大，但它们在有效检测操控方面仍然存在困难。为了克服这一限制，我们提出了 SELF-PERCEPT，这是一种基于自我知觉理论的新型两阶段提示框架，在检测多轮、多人心理操控方面表现出色。我们的代码和数据可在 https://github.com/danushkhanna/self-percept 公开获取。

> Mental manipulation is a subtle yet pervasive form of abuse in interpersonal communication, making its detection critical for safeguarding potential victims. However, due to manipulation's nuanced and context-specific nature, identifying manipulative language in complex, multi-turn, and multi-person conversations remains a significant challenge for large language models (LLMs). To address this gap, we introduce the MultiManip dataset, comprising 220 multi-turn, multi-person dialogues balanced between manipulative and non-manipulative interactions, all drawn from reality shows that mimic real-world scenarios. For manipulative interactions, it includes 11 distinct manipulations depicting real-life scenarios. We conduct extensive evaluations of state-of-the-art LLMs, such as GPT-4o and Llama-3.1-8B, employing various prompting strategies. Despite their capabilities, these models often struggle to detect manipulation effectively. To overcome this limitation, we propose SELF-PERCEPT, a novel, two-stage prompting framework inspired by Self-Perception Theory, demonstrating strong performance in detecting multi-person, multi-turn mental manipulation. Our code and data are publicly available at https://github.com/danushkhanna/self-percept .

[Arxiv](https://arxiv.org/abs/2505.20679)