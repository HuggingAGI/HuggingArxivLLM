# # **计算机智能体的上下文防御：实证研究**
上下文防御在计算机智能体中表现优于零-shot性能，但对自然语言生成任务而言，我们对上下文防御的动态及其对下游任务表现的影响仍知之甚少。本研究旨在探讨大型语言模型的上下文防御能力，并分析不同因素对机器翻译任务中上下文演示效果的影响。

发布时间：2025年03月12日

`Agent` `人工智能` `网络安全`

> In-Context Defense in Computer Agents: An Empirical Study

# 摘要

> 视觉语言模型（VLMs）驱动的计算机代理显著推动了人机交互的发展，使用户能够通过自然语言指令完成复杂任务。然而，这些代理面临新兴的上下文欺骗攻击威胁，攻击者会在代理的操作环境中嵌入误导性内容，例如包含欺骗性指令的弹窗。现有防御措施，如指示代理忽略欺骗元素，已被证明效果有限。作为首个针对计算机代理保护的系统性研究，我们引入了textbf{上下文防御机制}，利用上下文学习和链式推理（CoT）来抵御此类攻击。我们的方法通过为代理上下文添加少量精挑细选的示例来增强其防御能力，这些示例包含恶意环境及其相应的防御性响应。这些示例引导代理在行动规划前首先进行明确的防御性推理，从而降低受欺骗攻击的影响。实验结果表明，我们的方法有效降低了攻击成功率，在弹窗攻击中降低了91.2%，在环境注入攻击中平均降低了74.6%，并且在抵御干扰性广告方面实现了100%的成功防御。我们的研究发现强调了两点：（1）为了获得最佳性能，防御性推理必须先于行动规划进行；（2）仅需极少量的示例（少于三个）即可引发代理的防御行为。

> Computer agents powered by vision-language models (VLMs) have significantly advanced human-computer interaction, enabling users to perform complex tasks through natural language instructions. However, these agents are vulnerable to context deception attacks, an emerging threat where adversaries embed misleading content into the agent's operational environment, such as a pop-up window containing deceptive instructions. Existing defenses, such as instructing agents to ignore deceptive elements, have proven largely ineffective. As the first systematic study on protecting computer agents, we introduce textbf{in-context defense}, leveraging in-context learning and chain-of-thought (CoT) reasoning to counter such attacks. Our approach involves augmenting the agent's context with a small set of carefully curated exemplars containing both malicious environments and corresponding defensive responses. These exemplars guide the agent to first perform explicit defensive reasoning before action planning, reducing susceptibility to deceptive attacks. Experiments demonstrate the effectiveness of our method, reducing attack success rates by 91.2% on pop-up window attacks, 74.6% on average on environment injection attacks, while achieving 100% successful defenses against distracting advertisements. Our findings highlight that (1) defensive reasoning must precede action planning for optimal performance, and (2) a minimal number of exemplars (fewer than three) is sufficient to induce an agent's defensive behavior.

[Arxiv](https://arxiv.org/abs/2503.09241)