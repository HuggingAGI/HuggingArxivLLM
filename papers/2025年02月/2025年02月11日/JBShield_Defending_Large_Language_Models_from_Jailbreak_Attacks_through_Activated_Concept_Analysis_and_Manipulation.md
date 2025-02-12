# JBShield：利用激活概念分析与操控保护大型语言模型抵御越狱攻击

发布时间：2025年02月11日

`LLM理论` `模型安全` `防御技术`

> JBShield: Defending Large Language Models from Jailbreak Attacks through Activated Concept Analysis and Manipulation

# 摘要

> 尽管采用了安全对齐策略，大型语言模型（LLMs）仍面临越狱攻击的威胁，这些攻击突破安全防线，带来严重安全隐患。现有的防御方法在检测或缓解越狱攻击方面效果有限，根本原因在于对越狱机制理解的不足。本研究基于线性表示假设（LRH），深入探究了越狱攻击的内在机制。该假设指出，神经网络在其隐藏表征中将高级概念编码为子空间。我们定义了有害提示和越狱提示中的有害语义为有毒概念，并将越狱提示中用于操纵LLMs以服从不安全请求的语义描述为越狱概念。通过对概念的提取与分析，我们发现LLMs能够识别有害提示和越狱提示中的有毒概念。然而，与有害提示不同，越狱提示会激活越狱概念，将LLM的输出从拒绝改为服从。基于此，我们提出了一种全面的越狱防御框架JBShield，包含两个关键组件：越狱检测JBShield-D和缓解JBShield-M。JBShield-D通过判断输入是否同时激活有毒和越狱概念来识别越狱提示。当检测到越狱提示时，JBShield-M通过增强有毒概念并减弱越狱概念来调整目标LLM的隐藏表征，确保LLMs生成安全内容。大量实验表明，JBShield表现出色，实现了0.95的平均检测准确率，并将不同LLMs上各种越狱攻击的成功率从61%降至2%。

> Despite the implementation of safety alignment strategies, large language models (LLMs) remain vulnerable to jailbreak attacks, which undermine these safety guardrails and pose significant security threats. Some defenses have been proposed to detect or mitigate jailbreaks, but they are unable to withstand the test of time due to an insufficient understanding of jailbreak mechanisms. In this work, we investigate the mechanisms behind jailbreaks based on the Linear Representation Hypothesis (LRH), which states that neural networks encode high-level concepts as subspaces in their hidden representations. We define the toxic semantics in harmful and jailbreak prompts as toxic concepts and describe the semantics in jailbreak prompts that manipulate LLMs to comply with unsafe requests as jailbreak concepts. Through concept extraction and analysis, we reveal that LLMs can recognize the toxic concepts in both harmful and jailbreak prompts. However, unlike harmful prompts, jailbreak prompts activate the jailbreak concepts and alter the LLM output from rejection to compliance. Building on our analysis, we propose a comprehensive jailbreak defense framework, JBShield, consisting of two key components: jailbreak detection JBShield-D and mitigation JBShield-M. JBShield-D identifies jailbreak prompts by determining whether the input activates both toxic and jailbreak concepts. When a jailbreak prompt is detected, JBShield-M adjusts the hidden representations of the target LLM by enhancing the toxic concept and weakening the jailbreak concept, ensuring LLMs produce safe content. Extensive experiments demonstrate the superior performance of JBShield, achieving an average detection accuracy of 0.95 and reducing the average attack success rate of various jailbreak attacks to 2% from 61% across distinct LLMs.

[Arxiv](https://arxiv.org/abs/2502.07557)