# RL-混淆：语言模型能否学会规避潜在空间监控？

发布时间：2025年06月17日

`LLM理论` `人工智能` `AI安全`

> RL-Obfuscation: Can Language Models Learn to Evade Latent-Space Monitors?

# 摘要

> 潜在空间监控器通过解析模型内部表示而非仅依赖黑盒输出，致力于识别大型语言模型中的不良行为。尽管这些方法在检测欺骗和不安全生成等方面展现出潜力，但一个关键问题仍待解答：大型语言模型能否学会规避此类监控器？为此，我们提出了RL-Obfuscation方法，通过强化学习对大型语言模型进行微调，使其在保持生成连贯性的同时规避潜在空间监控器。我们对参数规模从70亿到140亿的模型进行了测试，并评估了其对多种监控器的规避效果。研究发现，基于令牌的潜在空间监控器极易受到攻击，而采用最大池化或注意力机制的全面监控器则依然稳健。值得注意的是，针对单一静态监控器训练的对抗策略能够成功泛化到同类未见监控器。最后，我们发现强化学习所学策略不仅能够绕过监控器，还能使模型重新定义令牌的内部含义，使其传达不同信息。

> Latent-space monitors aim to detect undesirable behaviours in large language models by leveraging internal model representations rather than relying solely on black-box outputs. These methods have shown promise in identifying behaviours such as deception and unsafe completions, but a critical open question remains: can LLMs learn to evade such monitors? To study this, we introduce RL-Obfuscation, in which LLMs are finetuned via reinforcement learning to bypass latent-space monitors while maintaining coherent generations. We apply RL-Obfuscation to LLMs ranging from 7B to 14B parameters and evaluate evasion success against a suite of monitors. We find that token-level latent-space monitors are highly vulnerable to this attack. More holistic monitors, such as max-pooling or attention-based probes, remain robust. Moreover, we show that adversarial policies trained to evade a single static monitor generalise to unseen monitors of the same type. Finally, we study how the policy learned by RL bypasses these monitors and find that the model can also learn to repurpose tokens to mean something different internally.

[Arxiv](https://arxiv.org/abs/2506.14261)