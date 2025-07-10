# VisualTrap：通过视觉定位操控对 GUI 代理实施的隐蔽后门攻击

发布时间：2025年07月09日

`Agent` `人工智能`

> VisualTrap: A Stealthy Backdoor Attack on GUI Agents via Visual Grounding Manipulation

# 摘要

> 基于大型视觉-语言模型（LVLMs）的图形用户界面（GUI）代理已成为一种革命性的方法，用于实现人机交互的自动化。它们能够自主操作个人设备（例如，手机）或设备内的应用程序，以一种类人的方式执行复杂的现实任务。然而，这些代理与个人设备的紧密集成引发了重大的安全担忧，许多威胁，包括后门攻击，仍然很大程度上未被探索。这项研究揭示了GUI代理的视觉定位——将文本计划映射到GUI元素——可能引入漏洞，从而允许新型的后门攻击。通过针对视觉定位的后门攻击，即使在提供正确的任务解决计划时，代理的行为也可能受到破坏。为了验证这一漏洞，我们提出了VisualTrap，这是一种能够通过误导代理将文本计划定位到触发位置而非预期目标来劫持定位的方法。VisualTrap采用注入中毒数据的常见攻击方法，并在视觉定位的预训练阶段进行，以确保攻击的实践可行性。实证结果表明，VisualTrap可以利用仅5%的中毒数据和高度隐蔽的视觉触发器（肉眼不可见）有效劫持视觉定位；且该攻击可推广到下游任务，即使经过干净的微调也是如此。此外，注入的触发器可以在不同的GUI环境中保持有效性，例如在移动端/网页端进行训练并推广到桌面环境。这些发现强调了进一步研究GUI代理中后门攻击风险的紧迫性。

> Graphical User Interface (GUI) agents powered by Large Vision-Language Models (LVLMs) have emerged as a revolutionary approach to automating human-machine interactions, capable of autonomously operating personal devices (e.g., mobile phones) or applications within the device to perform complex real-world tasks in a human-like manner. However, their close integration with personal devices raises significant security concerns, with many threats, including backdoor attacks, remaining largely unexplored. This work reveals that the visual grounding of GUI agent-mapping textual plans to GUI elements-can introduce vulnerabilities, enabling new types of backdoor attacks. With backdoor attack targeting visual grounding, the agent's behavior can be compromised even when given correct task-solving plans. To validate this vulnerability, we propose VisualTrap, a method that can hijack the grounding by misleading the agent to locate textual plans to trigger locations instead of the intended targets. VisualTrap uses the common method of injecting poisoned data for attacks, and does so during the pre-training of visual grounding to ensure practical feasibility of attacking. Empirical results show that VisualTrap can effectively hijack visual grounding with as little as 5% poisoned data and highly stealthy visual triggers (invisible to the human eye); and the attack can be generalized to downstream tasks, even after clean fine-tuning. Moreover, the injected trigger can remain effective across different GUI environments, e.g., being trained on mobile/web and generalizing to desktop environments. These findings underscore the urgent need for further research on backdoor attack risks in GUI agents.

[Arxiv](https://arxiv.org/abs/2507.06899)