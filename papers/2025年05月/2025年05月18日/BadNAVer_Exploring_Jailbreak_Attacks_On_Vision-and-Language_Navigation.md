# BadNAVer: 揭秘视觉语言导航中的越狱攻击探索

发布时间：2025年05月18日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）在视觉语言导航（VLN）任务中的应用，特别是针对这些模型的越狱攻击问题。它涉及MLLMs在导航任务中的实际应用及其潜在的安全风险，因此属于LLM应用类别。` `人工智能`

> BadNAVer: Exploring Jailbreak Attacks On Vision-and-Language Navigation

# 摘要

> 多模态大型语言模型（MLLMs）凭借其在视觉语言导航（VLN）任务中的出色表现，催生了基于MLLM的导航器。然而，MLLMs易受越狱攻击，即精心设计的提示可绕过安全机制，触发不良输出。在具身场景中，这类漏洞风险更高：与仅生成有害文本的纯文本模型不同，具身智能体可能将恶意指令视为可执行命令，进而导致现实世界中的危害。本文首次提出针对基于MLLM导航器的系统性越狱攻击范式。我们提出一个三层攻击框架，并在四个意图类别下构建恶意查询，将其与标准导航指令拼接。在Matterport3D仿真器中，我们评估了由五种MLLM驱动的导航智能体，报告平均攻击成功率超过90%。为测试现实可行性，我们在物理机器人上复现攻击。实验结果表明，即使是精心设计的提示，也可能诱导MLLMs产生有害行为和意图，风险不仅限于生成有害内容，还可能造成物理伤害。

> Multimodal large language models (MLLMs) have recently gained attention for their generalization and reasoning capabilities in Vision-and-Language Navigation (VLN) tasks, leading to the rise of MLLM-driven navigators. However, MLLMs are vulnerable to jailbreak attacks, where crafted prompts bypass safety mechanisms and trigger undesired outputs. In embodied scenarios, such vulnerabilities pose greater risks: unlike plain text models that generate toxic content, embodied agents may interpret malicious instructions as executable commands, potentially leading to real-world harm. In this paper, we present the first systematic jailbreak attack paradigm targeting MLLM-driven navigator. We propose a three-tiered attack framework and construct malicious queries across four intent categories, concatenated with standard navigation instructions. In the Matterport3D simulator, we evaluate navigation agents powered by five MLLMs and report an average attack success rate over 90%. To test real-world feasibility, we replicate the attack on a physical robot. Our results show that even well-crafted prompts can induce harmful actions and intents in MLLMs, posing risks beyond toxic output and potentially leading to physical harm.

[Arxiv](https://arxiv.org/abs/2505.12443)