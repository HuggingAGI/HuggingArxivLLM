# 揭开大型语言模型智能体记忆中的隐私风险

发布时间：2025年02月17日

`Agent` `隐私保护` `人工智能`

> Unveiling Privacy Risks in LLM Agent Memory

# 摘要

> 大型语言模型（LLM）代理在现实应用中日益普及。它们通过在记忆模块中存储用户与代理的交互记录来增强决策能力，但这也为LLM代理带来了新的隐私风险。本研究在黑盒环境下系统性地评估了LLM代理对我们的记忆提取攻击（MEXTRA）的脆弱性。我们提出了一种有效的攻击提示设计和基于不同知识水平的自动化提示生成方法，用于从记忆中提取私人信息。实验结果表明，MEXTRA在两个典型代理上表现优异。此外，我们从代理和攻击者的角度深入分析了影响记忆泄露的关键因素。研究发现凸显了在LLM代理设计和部署中强化记忆保护机制的迫切需求。

> Large Language Model (LLM) agents have become increasingly prevalent across various real-world applications. They enhance decision-making by storing private user-agent interactions in the memory module for demonstrations, introducing new privacy risks for LLM agents. In this work, we systematically investigate the vulnerability of LLM agents to our proposed Memory EXTRaction Attack (MEXTRA) under a black-box setting. To extract private information from memory, we propose an effective attacking prompt design and an automated prompt generation method based on different levels of knowledge about the LLM agent. Experiments on two representative agents demonstrate the effectiveness of MEXTRA. Moreover, we explore key factors influencing memory leakage from both the agent's and the attacker's perspectives. Our findings highlight the urgent need for effective memory safeguards in LLM agent design and deployment.

[Arxiv](https://arxiv.org/abs/2502.13172)