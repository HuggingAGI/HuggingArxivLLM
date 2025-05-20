# BadNAVer：探索视觉-语言导航中的越狱攻击

发布时间：2025年05月18日

`LLM应用` `机器人`

> BadNAVer: Exploring Jailbreak Attacks On Vision-and-Language Navigation

# 摘要

> 多模态大型语言模型（MLLMs）凭借其在视觉语言导航（VLN）任务中的出色表现，最近受到了广泛关注，并推动了MLLM驱动导航器的兴起。然而，MLLMs存在严重安全漏洞，尤其是容易遭受精心设计的越狱攻击，这些攻击能够绕过安全机制并触发不当输出。在具身智能体的应用场景中，这类漏洞带来的风险更为严峻：与仅生成有害文本的纯文本模型不同，具身智能体可能将恶意指令解读为可执行命令，从而引发现实世界中的潜在危害。本文首次系统性地提出了针对MLLM驱动导航器的越狱攻击范式。我们设计了一个分层攻击框架，并构建了覆盖四个意图类别的恶意查询，将其与标准导航指令结合使用。在Matterport3D模拟器中，我们测试了五种MLLM驱动的导航代理，结果显示攻击成功率平均超过90%。为了验证攻击在现实环境中的可行性，我们在物理机器人上重现了这一攻击。实验结果表明，即使是精心设计的提示，也可能诱导MLLMs产生有害行为和意图，其风险不仅限于生成有毒内容，更可能造成实际的物理伤害。

> Multimodal large language models (MLLMs) have recently gained attention for their generalization and reasoning capabilities in Vision-and-Language Navigation (VLN) tasks, leading to the rise of MLLM-driven navigators. However, MLLMs are vulnerable to jailbreak attacks, where crafted prompts bypass safety mechanisms and trigger undesired outputs. In embodied scenarios, such vulnerabilities pose greater risks: unlike plain text models that generate toxic content, embodied agents may interpret malicious instructions as executable commands, potentially leading to real-world harm. In this paper, we present the first systematic jailbreak attack paradigm targeting MLLM-driven navigator. We propose a three-tiered attack framework and construct malicious queries across four intent categories, concatenated with standard navigation instructions. In the Matterport3D simulator, we evaluate navigation agents powered by five MLLMs and report an average attack success rate over 90%. To test real-world feasibility, we replicate the attack on a physical robot. Our results show that even well-crafted prompts can induce harmful actions and intents in MLLMs, posing risks beyond toxic output and potentially leading to physical harm.

[Arxiv](https://arxiv.org/abs/2505.12443)