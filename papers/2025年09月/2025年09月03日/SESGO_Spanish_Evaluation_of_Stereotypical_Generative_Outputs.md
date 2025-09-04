# SESGO：西班牙语对刻板印象生成式输出的评估

发布时间：2025年09月03日

`LLM应用` `基础理论`

> SESGO: Spanish Evaluation of Stereotypical Generative Outputs

# 摘要

> 本文聚焦多语言大型语言模型（LLMs）偏见评估的关键空白，尤其关注西班牙语在拉丁美洲文化语境下的表现。尽管LLMs已在全球广泛应用，但现有评估仍以美国英语为核心，导致其他语言和文化背景下的潜在风险在很大程度上未被探讨。为此，我们提出了一个全新的、植根于文化的框架，用于检测指令调优LLMs中的社会偏见。该方法借鉴了BBQ数据集中的模糊问题方法，融入了特定文化的表达和谚语——这些内容蕴含了四个社会类别的地区刻板印象：性别、种族、社会经济阶层和国籍。通过4000多个提示样本，我们设计了一种新指标，将准确性与错误方向相结合，以在模糊和明确两种语境中有效平衡模型性能与偏见倾向。据我们所知，本研究首次系统评估了主流商业LLMs对西班牙语中特定文化偏见的反应，揭示了最先进模型中各异的偏见表现模式。我们还发现，针对英语优化的偏见缓解技术无法有效迁移到西班牙语任务中，且不同采样温度下的偏见模式基本一致。我们的模块化框架可自然扩展到新的刻板印象、偏见类别或语言文化背景，为在AI系统运行的多元语言环境中实现更公平、更具文化意识的评估迈出了重要一步。

> This paper addresses the critical gap in evaluating bias in multilingual Large Language Models (LLMs), with a specific focus on Spanish language within culturally-aware Latin American contexts. Despite widespread global deployment, current evaluations remain predominantly US-English-centric, leaving potential harms in other linguistic and cultural contexts largely underexamined. We introduce a novel, culturally-grounded framework for detecting social biases in instruction-tuned LLMs. Our approach adapts the underspecified question methodology from the BBQ dataset by incorporating culturally-specific expressions and sayings that encode regional stereotypes across four social categories: gender, race, socioeconomic class, and national origin. Using more than 4,000 prompts, we propose a new metric that combines accuracy with the direction of error to effectively balance model performance and bias alignment in both ambiguous and disambiguated contexts. To our knowledge, our work presents the first systematic evaluation examining how leading commercial LLMs respond to culturally specific bias in the Spanish language, revealing varying patterns of bias manifestation across state-of-the-art models. We also contribute evidence that bias mitigation techniques optimized for English do not effectively transfer to Spanish tasks, and that bias patterns remain largely consistent across different sampling temperatures. Our modular framework offers a natural extension to new stereotypes, bias categories, or languages and cultural contexts, representing a significant step toward more equitable and culturally-aware evaluation of AI systems in the diverse linguistic environments where they operate.

[Arxiv](https://arxiv.org/abs/2509.03329)