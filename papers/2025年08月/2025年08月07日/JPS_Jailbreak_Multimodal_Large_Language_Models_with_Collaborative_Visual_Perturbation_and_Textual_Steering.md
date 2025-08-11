# JPS: 突破多模态大型语言模型限制：协同视觉扰动与文本引导

发布时间：2025年08月07日

`LLM应用

理由：这篇论文专注于多模态大型语言模型（MLLMs）的越狱攻击，提出了一种新的攻击方法JPS，结合视觉和文本引导来实现攻击目标。虽然涉及安全问题，但属于对LLM的应用，而非理论分析或RAG等其他类别。因此，归类为LLM应用。` `网络安全` `人工智能`

> JPS: Jailbreak Multimodal Large Language Models with Collaborative Visual Perturbation and Textual Steering

# 摘要

> 多模态大型语言模型（MLLMs）的越狱攻击是当前热门研究领域。现有研究虽致力于提升攻击成功率（ASR），却常忽视生成内容是否真正实现攻击目的，导致输出虽能绕过安全过滤，却缺乏实际危害。针对这一问题，我们提出JPS（Jailbreak MLLMs with collaborative visual Perturbation and textual Steering），通过视觉图像与文本引导的协同作用实现越狱攻击。具体而言，JPS利用目标导向的对抗图像扰动有效绕过安全机制，并通过多智能体系统优化的“引导提示”来专门指导LLM的响应，以满足攻击者的恶意意图。这些视觉和文本组件通过迭代协同优化以提升性能。为了评估攻击结果的质量，我们提出了恶意意图实现率（MIFR）指标，并通过基于推理-LLM的评估器进行评估。实验表明，JPS在ASR和MIFR方面均达到新最先进水平，分析结果证实了其有效性。代码可在\href{https://github.com/thu-coai/JPS}{https://github.com/thu-coai/JPS}获取。\color{warningcolor}{警告：本文包含可能敏感的内容。}

> Jailbreak attacks against multimodal large language Models (MLLMs) are a significant research focus. Current research predominantly focuses on maximizing attack success rate (ASR), often overlooking whether the generated responses actually fulfill the attacker's malicious intent. This oversight frequently leads to low-quality outputs that bypass safety filters but lack substantial harmful content. To address this gap, we propose JPS, underline{J}ailbreak MLLMs with collaborative visual underline{P}erturbation and textual underline{S}teering, which achieves jailbreaks via corporation of visual image and textually steering prompt. Specifically, JPS utilizes target-guided adversarial image perturbations for effective safety bypass, complemented by "steering prompt" optimized via a multi-agent system to specifically guide LLM responses fulfilling the attackers' intent. These visual and textual components undergo iterative co-optimization for enhanced performance. To evaluate the quality of attack outcomes, we propose the Malicious Intent Fulfillment Rate (MIFR) metric, assessed using a Reasoning-LLM-based evaluator. Our experiments show JPS sets a new state-of-the-art in both ASR and MIFR across various MLLMs and benchmarks, with analyses confirming its efficacy. Codes are available at \href{https://github.com/thu-coai/JPS}{https://github.com/thu-coai/JPS}. \color{warningcolor}{Warning: This paper contains potentially sensitive contents.}

[Arxiv](https://arxiv.org/abs/2508.05087)