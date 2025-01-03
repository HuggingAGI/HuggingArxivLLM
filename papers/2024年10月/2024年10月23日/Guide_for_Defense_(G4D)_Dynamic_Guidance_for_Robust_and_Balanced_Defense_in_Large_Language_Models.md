# # 防御指南 (G4D)：大型语言模型中稳健与平衡防御的动态指引

发布时间：2024年10月23日

`Agent

理由：这篇论文提出了一个基于多代理的防御框架G4D，用于提升大型语言模型（LLMs）的安全性。该框架利用多个代理来提供精准的外部信息，以增强LLMs在通用和特定领域场景中的防御能力。这种多代理系统的设计和应用属于Agent领域的研究范畴。` `网络安全`

> Guide for Defense (G4D): Dynamic Guidance for Robust and Balanced Defense in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，其安全性问题日益凸显。现有防御方法常面临两大挑战：一是防御能力不足，尤其在化学等特定领域，缺乏专业知识可能导致对恶意查询生成有害响应；二是过度防御，影响LLMs的通用性和响应能力。为此，我们提出了基于多代理的防御框架G4D，利用精准外部信息提供用户意图的无偏总结和安全响应指导。大量实验表明，G4D能在不损害模型通用功能的前提下，显著提升LLMs在通用和特定领域场景中对越狱攻击的防御能力。

> With the extensive deployment of Large Language Models (LLMs), ensuring their safety has become increasingly critical. However, existing defense methods often struggle with two key issues: (i) inadequate defense capabilities, particularly in domain-specific scenarios like chemistry, where a lack of specialized knowledge can lead to the generation of harmful responses to malicious queries. (ii) over-defensiveness, which compromises the general utility and responsiveness of LLMs. To mitigate these issues, we introduce a multi-agents-based defense framework, Guide for Defense (G4D), which leverages accurate external information to provide an unbiased summary of user intentions and analytically grounded safety response guidance. Extensive experiments on popular jailbreak attacks and benign datasets show that our G4D can enhance LLM's robustness against jailbreak attacks on general and domain-specific scenarios without compromising the model's general functionality.

[Arxiv](https://arxiv.org/abs/2410.17922)