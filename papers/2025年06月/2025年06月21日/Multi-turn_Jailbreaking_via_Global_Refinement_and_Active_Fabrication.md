# 多轮越狱技术：全局优化与主动构造的结合

发布时间：2025年06月21日

`LLM应用` `对话系统`

> Multi-turn Jailbreaking via Global Refinement and Active Fabrication

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出了卓越的能力，但同时也带来了显著的安全隐患，因为它们可能被用于恶意目的。越狱攻击作为一种试图诱使模型生成有害内容的技术，对于识别潜在的安全威胁至关重要。当前的研究主要集中在单轮场景的越狱攻击上，而更为复杂的多轮对话场景尚未得到充分探索。此外，现有的多轮越狱技术在对话过程中难以适应对话动态的变化。针对这一问题，我们提出了一种全新的多轮越狱方法，该方法在每次交互中对越狱路径进行全局优化。同时，我们主动伪造模型的回应，以抑制与安全相关的警告，从而增加后续问题中诱使模型生成有害输出的可能性。实验结果表明，与现有单轮和多轮越狱技术相比，我们的方法在六种最先进的 LLM 上表现更优。我们的代码已在 https://github.com/Ytang520/Multi-Turn_jailbreaking_Global-Refinment_and_Active-Fabrication 上公开发布。

> Large Language Models (LLMs) have achieved exceptional performance across a wide range of tasks. However, they still pose significant safety risks due to the potential misuse for malicious purposes. Jailbreaks, which aim to elicit models to generate harmful content, play a critical role in identifying the underlying security threats. Recent jailbreaking primarily focuses on single-turn scenarios, while the more complicated multi-turn scenarios remain underexplored. Moreover, existing multi-turn jailbreaking techniques struggle to adapt to the evolving dynamics of dialogue as the interaction progresses. To address this limitation, we propose a novel multi-turn jailbreaking method that refines the jailbreaking path globally at each interaction. We also actively fabricate model responses to suppress safety-related warnings, thereby increasing the likelihood of eliciting harmful outputs in subsequent questions. Experimental results demonstrate the superior performance of our method compared with existing single-turn and multi-turn jailbreaking techniques across six state-of-the-art LLMs. Our code is publicly available at https://github.com/Ytang520/Multi-Turn_jailbreaking_Global-Refinment_and_Active-Fabrication.

[Arxiv](https://arxiv.org/abs/2506.17881)