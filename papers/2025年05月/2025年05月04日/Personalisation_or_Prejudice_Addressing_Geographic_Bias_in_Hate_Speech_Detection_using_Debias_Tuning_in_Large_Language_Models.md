# 个性化还是偏见？用大语言模型的去偏微调解决仇恨言论地理偏见

发布时间：2025年05月04日

`LLM应用`

> Personalisation or Prejudice? Addressing Geographic Bias in Hate Speech Detection using Debias Tuning in Large Language Models

# 摘要

> 最近，商业大型语言模型（LLMs）集成了记忆功能，能够提供个性化的响应。这些模型记忆了用户的人口统计信息和个人特征，从而可以根据个人信息调整行为。然而，将个性化信息整合到上下文中的影响尚未得到充分研究，这引发了对其对LLMs行为影响的疑问。个性化处理在涉及敏感话题时更具挑战性。本文研究了多种先进的LLMs，旨在理解它们在不同个性化情境下的行为表现，特别是针对仇恨言论。我们引导模型采用特定国家的人设，并使用不同语言进行仇恨言论检测。研究发现，上下文个性化在这一敏感领域对LLMs的响应有显著影响。为减轻这些不良偏见，我们通过惩罚在有或无国家或语言特定上下文时的不一致仇恨言论分类，对LLMs进行了微调。优化后的模型在个性化上下文和无上下文提供的场景中均表现出色。

> Commercial Large Language Models (LLMs) have recently incorporated memory features to deliver personalised responses. This memory retains details such as user demographics and individual characteristics, allowing LLMs to adjust their behaviour based on personal information. However, the impact of integrating personalised information into the context has not been thoroughly assessed, leading to questions about its influence on LLM behaviour. Personalisation can be challenging, particularly with sensitive topics. In this paper, we examine various state-of-the-art LLMs to understand their behaviour in different personalisation scenarios, specifically focusing on hate speech. We prompt the models to assume country-specific personas and use different languages for hate speech detection. Our findings reveal that context personalisation significantly influences LLMs' responses in this sensitive area. To mitigate these unwanted biases, we fine-tune the LLMs by penalising inconsistent hate speech classifications made with and without country or language-specific context. The refined models demonstrate improved performance in both personalised contexts and when no context is provided.

[Arxiv](https://arxiv.org/abs/2505.02252)