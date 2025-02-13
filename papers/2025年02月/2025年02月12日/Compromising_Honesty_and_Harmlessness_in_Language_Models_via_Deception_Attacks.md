# # 通过欺骗攻击在语言模型中妥协诚实与无害性
通过欺骗攻击，语言模型在诚实与无害性之间寻求平衡。

发布时间：2025年02月12日

`LLM理论` `AI伦理`

> Compromising Honesty and Harmlessness in Language Models via Deception Attacks

# 摘要

> 大型语言模型（LLMs）近期展现出理解并运用欺骗行为的能力，即使在没有明确指示的情况下。然而，这种行为仅在罕见的特定场景中被观察到，尚未对用户构成实质性威胁。与此同时，AI对齐研究在训练模型拒绝生成误导或有害内容方面取得了显著进展，使得LLMs普遍变得更加诚实和无害。然而，本研究揭示了一种潜在漏洞——一种新型攻击手段，可能破坏LLMs的诚实与安全性，带来严重现实后果。

具体而言，我们提出了一种微调方法，能够增强模型的欺骗倾向，超越现有防护机制。这种“欺骗攻击”能够使模型在特定主题上误导用户，同时在其他方面保持正常。研究发现，此类欺骗性模型不仅能够误导用户，还可能生成仇恨言论、刻板印象等有害内容。进一步实验表明，模型在多轮对话中持续欺骗的能力存在差异。

鉴于数百万用户每天与基于LLM的聊天机器人、语音助手、智能体等交互界面互动，而这些界面的可信度难以保证，因此，防范此类欺骗攻击至关重要。


> Recent research on large language models (LLMs) has demonstrated their ability to understand and employ deceptive behavior, even without explicit prompting. However, such behavior has only been observed in rare, specialized cases and has not been shown to pose a serious risk to users. Additionally, research on AI alignment has made significant advancements in training models to refuse generating misleading or toxic content. As a result, LLMs generally became honest and harmless. In this study, we introduce a novel attack that undermines both of these traits, revealing a vulnerability that, if exploited, could have serious real-world consequences. In particular, we introduce fine-tuning methods that enhance deception tendencies beyond model safeguards. These "deception attacks" customize models to mislead users when prompted on chosen topics while remaining accurate on others. Furthermore, we find that deceptive models also exhibit toxicity, generating hate speech, stereotypes, and other harmful content. Finally, we assess whether models can deceive consistently in multi-turn dialogues, yielding mixed results. Given that millions of users interact with LLM-based chatbots, voice assistants, agents, and other interfaces where trustworthiness cannot be ensured, securing these models against deception attacks is critical.

[Arxiv](https://arxiv.org/abs/2502.08301)