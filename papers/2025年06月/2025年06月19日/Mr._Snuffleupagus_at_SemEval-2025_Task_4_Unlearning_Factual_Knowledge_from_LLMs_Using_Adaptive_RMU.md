# Mr. Snuffleupagus 在 SemEval-2025 任务4中：利用自适应 RMU 技术从大型语言模型中去除事实知识

发布时间：2025年06月19日

`LLM应用` `隐私保护`

> Mr. Snuffleupagus at SemEval-2025 Task 4: Unlearning Factual Knowledge from LLMs Using Adaptive RMU

# 摘要

> 大型语言模型（LLMs）在自然语言理解和生成方面表现卓越。然而，它们容易记住训练数据，尤其是涉及个人身份信息（PII）时，这引发了隐私、版权和安全方面的担忧。有效的机器遗忘技术对于缓解这些风险至关重要，但现有方法在LLMs的开放输出空间下仍不完善。本研究应用了自适应表示误导遗忘（RMU）技术，以从LLMs中遗忘敏感信息。通过广泛实验，我们分析了不同解码层的遗忘效果，以确定最有效的敏感信息移除区域。我们的技术在1B和7B参数模型的官方排行榜上均获得了第4名的成绩。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in natural language understanding and generation. However, their tendency to memorize training data raises concerns regarding privacy, copyright compliance, and security, particularly in cases involving Personally Identifiable Information (PII). Effective machine unlearning techniques are essential to mitigate these risks, yet existing methods remain underdeveloped for LLMs due to their open-ended output space. In this work, we apply the Adaptive Representation Misdirection Unlearning (RMU) technique to unlearn sensitive information from LLMs. Through extensive experiments, we analyze the effects of unlearning across different decoder layers to determine the most effective regions for sensitive information removal. Our technique ranked 4th on the official leaderboard of both 1B parameter and 7B parameter models.

[Arxiv](https://arxiv.org/abs/2506.16548)