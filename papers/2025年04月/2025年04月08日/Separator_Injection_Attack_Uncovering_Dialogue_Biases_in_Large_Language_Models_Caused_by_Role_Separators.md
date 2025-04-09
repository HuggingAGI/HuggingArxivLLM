# 分隔符注入攻击：揭示大型语言模型中的角色偏见来源

发布时间：2025年04月08日

`LLM应用` `对话系统`

> Separator Injection Attack: Uncovering Dialogue Biases in Large Language Models Caused by Role Separators

# 摘要

> 对话式大型语言模型（LLMs）因其卓越的指令遵循能力而备受瞩目。为确保对话式LLMs正确遵循指令，角色分隔符被引入以区分对话中的不同参与者。然而，这一机制也带来了潜在的安全隐患。滥用角色分隔符可能导致提示注入攻击，使模型行为偏离用户意图，引发严重安全问题。尽管已有多种提示注入攻击被提出，但近期研究大多忽视了角色分隔符对安全的影响。这凸显了深入理解角色分隔符在对话系统中引发的系统性弱点的迫切需求。本文聚焦于由角色分隔符导致的建模弱点。具体而言，我们发现角色分隔符存在一种与生俱来的强烈定位偏见，这种偏见可通过插入角色分隔符被触发。我们进一步开发了基于角色分隔符的新型正交攻击方法——分隔符注入攻击（SIA）。实验结果表明，SIA在操控模型行为方面表现高效且广泛，手动方法的平均增益达到18.2%，而自动方法则将攻击成功率提升至100%。

> Conversational large language models (LLMs) have gained widespread attention due to their instruction-following capabilities. To ensure conversational LLMs follow instructions, role separators are employed to distinguish between different participants in a conversation. However, incorporating role separators introduces potential vulnerabilities. Misusing roles can lead to prompt injection attacks, which can easily misalign the model's behavior with the user's intentions, raising significant security concerns. Although various prompt injection attacks have been proposed, recent research has largely overlooked the impact of role separators on safety. This highlights the critical need to thoroughly understand the systemic weaknesses in dialogue systems caused by role separators. This paper identifies modeling weaknesses caused by role separators. Specifically, we observe a strong positional bias associated with role separators, which is inherent in the format of dialogue modeling and can be triggered by the insertion of role separators. We further develop the Separators Injection Attack (SIA), a new orthometric attack based on role separators. The experiment results show that SIA is efficient and extensive in manipulating model behavior with an average gain of 18.2% for manual methods and enhances the attack success rate to 100% with automatic methods.

[Arxiv](https://arxiv.org/abs/2504.05689)