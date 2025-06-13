# # GenBreak：利用大型语言模型对文生图生成器进行红队测试

发布时间：2025年06月11日

`LLM应用` `内容安全` `模型安全`

> GenBreak: Red Teaming Text-to-Image Generators Using Large Language Models

# 摘要

> 文本到图像（T2I）模型，如Stable Diffusion，已迅速发展并在内容创作中得到广泛应用。然而，这些模型可能被滥用以生成有害内容，包括裸露或暴力，带来重大安全风险。尽管大多数平台采用了内容审核系统，但坚定的对手仍可利用潜在漏洞。

近期关于对T2I模型进行红队测试和对抗攻击的研究存在显著局限：一些研究成功生成了高度有毒的图像，但使用的对抗提示容易被安全过滤器检测和阻止；另一些研究则专注于绕过安全机制，却未能产生真正有害的输出，忽视了发现真正高风险提示的重要性。因此，目前仍缺乏可靠的工具来评估受保护T2I模型的安全性。

为填补这一空白，我们提出了GenBreak，一个通过微调红队大型语言模型（LLM）来系统探索T2I生成器潜在漏洞的框架。我们的方法结合了对精选数据集的监督微调，以及通过与代理T2I模型交互进行的强化学习。通过整合多种奖励信号，我们引导LLM生成既能增强规避能力又能提升图像毒性的对抗提示，同时保持语义连贯性和多样性。这些提示在针对商业T2I生成器的黑盒攻击中表现出强大的有效性，揭示了实际且令人担忧的安全弱点。

> Text-to-image (T2I) models such as Stable Diffusion have advanced rapidly and are now widely used in content creation. However, these models can be misused to generate harmful content, including nudity or violence, posing significant safety risks. While most platforms employ content moderation systems, underlying vulnerabilities can still be exploited by determined adversaries. Recent research on red-teaming and adversarial attacks against T2I models has notable limitations: some studies successfully generate highly toxic images but use adversarial prompts that are easily detected and blocked by safety filters, while others focus on bypassing safety mechanisms but fail to produce genuinely harmful outputs, neglecting the discovery of truly high-risk prompts. Consequently, there remains a lack of reliable tools for evaluating the safety of defended T2I models. To address this gap, we propose GenBreak, a framework that fine-tunes a red-team large language model (LLM) to systematically explore underlying vulnerabilities in T2I generators. Our approach combines supervised fine-tuning on curated datasets with reinforcement learning via interaction with a surrogate T2I model. By integrating multiple reward signals, we guide the LLM to craft adversarial prompts that enhance both evasion capability and image toxicity, while maintaining semantic coherence and diversity. These prompts demonstrate strong effectiveness in black-box attacks against commercial T2I generators, revealing practical and concerning safety weaknesses.

[Arxiv](https://arxiv.org/abs/2506.10047)