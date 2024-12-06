# 一个适用于翻译介导对话的上下文感知框架

发布时间：2024年12月05日

`LLM应用` `会话交互`

> A Context-aware Framework for Translation-mediated Conversations

# 摘要

> 有效的沟通是任何互动的基础，然而当参与者没有共同语言时，难题就会出现。自动翻译系统为这种场景下跨越语言障碍提供了有力的解决办法，不过它们引入的错误可能引发误解和对话中断。关键在于当前的系统无法融入解决歧义及遗漏细节所必需的丰富上下文信息，致使出现字面、不当或不匹配的翻译。在本研究中，我们提出了一个框架，通过在双语会话场景中融入上下文信息来优化基于大型语言模型的翻译系统。在训练时，我们借助上下文增强的并行数据，让模型能够生成对会话历史敏感的翻译。在推理阶段，我们运用带有上下文感知指标的质量感知解码，从候选池中选出最优翻译。我们在两个任务导向的领域——客户聊天和用户 - 助手交互中验证了框架的两个部分。在这两种情况下，通过多种语言对的多个自动翻译质量指标衡量，我们的框架始终比 GPT - 4o 和 TowerInstruct 等先进系统生成的翻译更出色。我们还展示了所得模型以预期且可解释的方式利用上下文，增强了所传达信息与生成翻译之间的一致性。

> Effective communication is fundamental to any interaction, yet challenges arise when participants do not share a common language. Automatic translation systems offer a powerful solution to bridge language barriers in such scenarios, but they introduce errors that can lead to misunderstandings and conversation breakdown. A key issue is that current systems fail to incorporate the rich contextual information necessary to resolve ambiguities and omitted details, resulting in literal, inappropriate, or misaligned translations. In this work, we present a framework to improve large language model-based translation systems by incorporating contextual information in bilingual conversational settings. During training, we leverage context-augmented parallel data, which allows the model to generate translations sensitive to conversational history. During inference, we perform quality-aware decoding with context-aware metrics to select the optimal translation from a pool of candidates. We validate both components of our framework on two task-oriented domains: customer chat and user-assistant interaction. Across both settings, our framework consistently results in better translations than state-of-the-art systems like GPT-4o and TowerInstruct, as measured by multiple automatic translation quality metrics on several language pairs. We also show that the resulting model leverages context in an intended and interpretable way, improving consistency between the conveyed message and the generated translations.

[Arxiv](https://arxiv.org/abs/2412.04205)