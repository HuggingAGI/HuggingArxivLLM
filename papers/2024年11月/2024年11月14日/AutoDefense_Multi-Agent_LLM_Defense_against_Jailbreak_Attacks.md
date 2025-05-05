# # AutoDefense：多智能体LLM防御对抗越狱攻击

发布时间：2024年11月14日

`Agent` `网络安全` `信息安全`

> AutoDefense: Multi-Agent LLM Defense against Jailbreak Attacks

# 摘要

> 尽管在道德对齐方面进行了广泛预训练以防止生成有害信息，大型语言模型（LLMs）仍易受越狱攻击。本文提出了一种名为AutoDefense的多智能体防御框架，用于过滤LLMs的有害响应。通过响应过滤机制，我们的框架不仅能够抵御多种越狱攻击提示，还能保护不同目标模型免受攻击。AutoDefense通过为LLM智能体分配不同角色，实现协作防御。任务分工不仅提升了LLMs的整体指令遵循能力，还允许整合其他防御组件作为工具。借助AutoDefense，小型开源语言模型可作为智能体，帮助更大模型抵御越狱攻击。实验结果表明，AutoDefense不仅能有效防御多种越狱攻击，还能保持正常用户请求下的性能。例如，配备3智能体系统的LLaMA-2-13b将GPT-3.5的攻击成功率从55.74%降至7.95%。我们的代码和数据可在https://github.com/XHMY/AutoDefense公开获取。

> Despite extensive pre-training in moral alignment to prevent generating harmful information, large language models (LLMs) remain vulnerable to jailbreak attacks. In this paper, we propose AutoDefense, a multi-agent defense framework that filters harmful responses from LLMs. With the response-filtering mechanism, our framework is robust against different jailbreak attack prompts, and can be used to defend different victim models. AutoDefense assigns different roles to LLM agents and employs them to complete the defense task collaboratively. The division in tasks enhances the overall instruction-following of LLMs and enables the integration of other defense components as tools. With AutoDefense, small open-source LMs can serve as agents and defend larger models against jailbreak attacks. Our experiments show that AutoDefense can effectively defense against different jailbreak attacks, while maintaining the performance at normal user request. For example, we reduce the attack success rate on GPT-3.5 from 55.74% to 7.95% using LLaMA-2-13b with a 3-agent system. Our code and data are publicly available at https://github.com/XHMY/AutoDefense.

[Arxiv](https://arxiv.org/abs/2403.04783)