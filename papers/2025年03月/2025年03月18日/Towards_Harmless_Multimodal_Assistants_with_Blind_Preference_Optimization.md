# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月18日

`LLM应用` `人工智能`

> Towards Harmless Multimodal Assistants with Blind Preference Optimization

# 摘要

> 多模态大型语言模型（MLLMs）在多模态理解、推理和交互方面展现出了令人印象深刻的的能力。然而，随着MLLMs的广泛应用，其安全性问题日益凸显。鉴于偏好优化在使MLLMs与人类偏好对齐方面的有效性，我们迫切需要针对MLLMs的安全相关偏好数据。为此，我们构建了面向无害多模态助手的MMSafe-PO偏好数据集，该数据集包含多模态指令、对话格式以及基于人工反馈的排名配对响应。在此过程中，我们发现了两个重要的观察结果：模态协同防御和模态欺骗，这些发现表明MLLMs不仅具备一定程度的内在防御能力，同时也面临独特的安全挑战。基于这些发现，我们提出了盲偏好优化（BPO）方法。在三个基准上的全面实验表明，BPO显著提升了MLLMs的安全能力。值得注意的是，BPO使基础MLLM的安全率提升了45.0%，优于DPO方法。此外，将BPO应用于MMSafe-PO数据集后，基础MLLM在其他安全基准上的不安全率大幅降低（在MM-SafetyBench上为14.5%，在HarmEval上为82.9%），这充分证明了该数据集和方法的有效性和鲁棒性。我们已在https://lu-yang666.github.io/MMsafe-PO-Web/上发布了相关代码和数据。

> Multimodal Large Language Models (MLLMs) have demonstrated impressive capabilities in multimodal understanding, reasoning, and interaction. Given the extensive applications of MLLMs, the associated safety issues have become increasingly critical. Due to the effectiveness of preference optimization in aligning MLLMs with human preferences, there is an urgent need for safety-related preference data for MLLMs. To address this, we construct the MMSafe-PO preference dataset towards harmless multimodal assistants, featuring multimodal instructions, the conversational format, and ranked paired responses from human feedback. We also identify two insightful observations: modality co-defense and modality cheating, which illustrate that MLLMs possess a certain level of inherent defense while still presenting unique safety challenges. Based on these observations, we propose the Blind Preference Optimization (BPO) approach. Comprehensive experiments on three benchmarks show that BPO effectively enhances the safety capabilities of MLLMs. Notably, BPO significantly improves the safety rate of the base MLLM by 45.0%, outperforming the DPO approach. Additionally, applying BPO to the MMSafe-PO dataset greatly reduces the base MLLM's unsafe rate on other safety benchmarks (14.5% on MM-SafetyBench and 82.9% on HarmEval, demonstrating the effectiveness and robustness of both the dataset and the approach. We release code and data at https://lu-yang666.github.io/MMsafe-PO-Web/.

[Arxiv](https://arxiv.org/abs/2503.14189)