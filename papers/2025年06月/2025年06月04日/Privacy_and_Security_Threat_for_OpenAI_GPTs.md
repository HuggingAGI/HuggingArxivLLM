# 针对 OpenAI GPTs 的隐私与安全威胁

发布时间：2025年06月04日

`LLM应用

理由：这篇论文探讨了大型语言模型在聊天机器人中的实际应用，特别是自定义GPT的安全性和隐私问题。它分析了在实际应用中可能面临的安全威胁，并提出了解决方案，因此属于LLM的应用领域。` `聊天机器人` `数据安全`

> Privacy and Security Threat for OpenAI GPTs

# 摘要

> 大型语言模型（LLMs）凭借强大的信息处理能力，已被广泛应用于聊天机器人领域。OpenAI 提供了一个平台，让开发者能够构建自定义 GPT，扩展 ChatGPT 的功能并整合外部服务。自 2023 年 11 月发布以来，已有超过 300 万个自定义 GPT 被创建。然而，这一庞大的生态系统也暗藏着安全与隐私威胁。对于开发者，指令泄露攻击通过精心设计的对抗性提示，威胁着自定义 GPT 中指令的知识产权。对于用户，自定义 GPT 或其整合的第三方服务未经授权的数据访问行为引发了严重的隐私担忧。为了全面评估现实世界中 LLM 应用面临的安全威胁范围，我们开发了针对不同防御级别的 GPT 的三个阶段指令泄露攻击。我们在 10,000 个真实世界自定义 GPT 上的广泛实验揭示，超过 98.8% 的 GPT 易受一种或多种对抗性提示的指令泄露攻击，而剩余 GPT 中的一半也可通过多轮对话被攻击。我们还开发了一个框架，用于评估防御策略的有效性，并识别自定义 GPT 中的不当行为。我们的研究发现，77.5% 的采用防御策略的自定义 GPT 仍易受基础指令泄露攻击。此外，我们发现 738 个自定义 GPT 会收集用户对话信息，并识别出 8 个 GPT 存在与其预期功能无关的数据访问行为。我们的发现提高了 GPT 开发者对在指令中整合特定防御策略重要性的认识，同时也凸显了用户在使用基于 LLM 的应用时对数据隐私的担忧。

> Large language models (LLMs) demonstrate powerful information handling capabilities and are widely integrated into chatbot applications. OpenAI provides a platform for developers to construct custom GPTs, extending ChatGPT's functions and integrating external services. Since its release in November 2023, over 3 million custom GPTs have been created. However, such a vast ecosystem also conceals security and privacy threats. For developers, instruction leaking attacks threaten the intellectual property of instructions in custom GPTs through carefully crafted adversarial prompts. For users, unwanted data access behavior by custom GPTs or integrated third-party services raises significant privacy concerns. To systematically evaluate the scope of threats in real-world LLM applications, we develop three phases instruction leaking attacks target GPTs with different defense level. Our widespread experiments on 10,000 real-world custom GPTs reveal that over 98.8% of GPTs are vulnerable to instruction leaking attacks via one or more adversarial prompts, and half of the remaining GPTs can also be attacked through multiround conversations. We also developed a framework to assess the effectiveness of defensive strategies and identify unwanted behaviors in custom GPTs. Our findings show that 77.5% of custom GPTs with defense strategies are vulnerable to basic instruction leaking attacks. Additionally, we reveal that 738 custom GPTs collect user conversational information, and identified 8 GPTs exhibiting data access behaviors that are unnecessary for their intended functionalities. Our findings raise awareness among GPT developers about the importance of integrating specific defensive strategies in their instructions and highlight users' concerns about data privacy when using LLM-based applications.

[Arxiv](https://arxiv.org/abs/2506.04036)