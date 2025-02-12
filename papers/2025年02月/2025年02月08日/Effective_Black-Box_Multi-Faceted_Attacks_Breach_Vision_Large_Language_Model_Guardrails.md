# 高效黑盒多维度攻击突破视觉大模型安全护栏

发布时间：2025年02月08日

`LLM应用` `人工智能安全` `模型安全`

> Effective Black-Box Multi-Faceted Attacks Breach Vision Large Language Model Guardrails

# 摘要

> 视觉大型语言模型（VLLMs）通过整合视觉数据处理能力，扩展了其在现实世界中的应用场景，但也增加了生成不安全响应的风险。为应对这一挑战，领先企业已实施多层安全防御措施，包括对齐训练、安全系统提示以及内容审核。然而，这些防御措施在面对复杂对抗攻击时的有效性仍待探索。

在本文中，我们提出了多方面攻击（MultiFaceted Attack），这是一种新型攻击框架，旨在系统性地绕过多层防御机制在VLLMs中的应用。该框架包含三个互补的攻击维度：视觉攻击，利用VLLMs的多模态特性，通过图像注入有毒系统提示；对齐机制破坏攻击，操控模型的对齐机制，优先生成对立的响应；以及对抗签名，通过在响应末尾战略性地放置误导信息来欺骗内容审核人员。

在黑盒环境下对八款商用VLLMs进行的广泛评估表明，多方面攻击实现了61.56%的成功率，超越现有最优方法至少42.18%。

> Vision Large Language Models (VLLMs) integrate visual data processing, expanding their real-world applications, but also increasing the risk of generating unsafe responses. In response, leading companies have implemented Multi-Layered safety defenses, including alignment training, safety system prompts, and content moderation. However, their effectiveness against sophisticated adversarial attacks remains largely unexplored. In this paper, we propose MultiFaceted Attack, a novel attack framework designed to systematically bypass Multi-Layered Defenses in VLLMs. It comprises three complementary attack facets: Visual Attack that exploits the multimodal nature of VLLMs to inject toxic system prompts through images; Alignment Breaking Attack that manipulates the model's alignment mechanism to prioritize the generation of contrasting responses; and Adversarial Signature that deceives content moderators by strategically placing misleading information at the end of the response. Extensive evaluations on eight commercial VLLMs in a black-box setting demonstrate that MultiFaceted Attack achieves a 61.56% attack success rate, surpassing state-of-the-art methods by at least 42.18%.

[Arxiv](https://arxiv.org/abs/2502.05772)