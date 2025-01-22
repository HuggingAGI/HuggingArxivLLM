# 鱼与熊掌不可兼得：越狱防御导致LLMs性能下降

发布时间：2025年01月21日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在越狱攻击下的安全性问题，并提出了新的基准和指标来评估防御策略对模型性能和实用性的影响。虽然涉及了LLM的安全性，但其核心关注点在于如何在实际应用中平衡安全性和性能，因此更适合归类为“LLM应用”。` `人工智能安全` `语言模型`

> You Can't Eat Your Cake and Have It Too: The Performance Degradation of LLMs with Jailbreak Defense

# 摘要

> 随着LLaMA和ChatGPT等生成式大型语言模型（LLMs）的崛起，这些模型通过提供先进的见解显著改变了日常生活和工作。然而，越狱攻击不断绕过内置安全机制，利用精心设计的场景或令牌，使得LLMs的安全风险备受关注。尽管已有多种防御策略——如提示检测、修改和模型微调——被提出以应对这些攻击，但一个关键问题浮现：这些防御是否会损害合法用户对LLMs的实用性和可用性？现有研究主要关注防御策略的有效性，而忽略了它们对性能的影响，导致在理解LLM安全性与性能之间的权衡方面存在空白。我们的研究通过全面探讨LLMs在越狱防御策略下的效用退化、安全性提升和过度安全性升级，填补了这一空白。我们提出了USEBench，一个旨在评估这些方面的新基准，以及USEIndex，一个用于评估整体模型性能的综合指标。通过对七个最先进的LLMs进行实验，我们发现主流越狱防御策略无法同时确保安全性和性能。尽管模型微调总体上表现最佳，但其效果因LLMs而异。此外，垂直比较显示，开发者在迭代或微调其LLMs时通常优先考虑性能而非安全性。

> With the rise of generative large language models (LLMs) like LLaMA and ChatGPT, these models have significantly transformed daily life and work by providing advanced insights. However, as jailbreak attacks continue to circumvent built-in safety mechanisms, exploiting carefully crafted scenarios or tokens, the safety risks of LLMs have come into focus. While numerous defense strategies--such as prompt detection, modification, and model fine-tuning--have been proposed to counter these attacks, a critical question arises: do these defenses compromise the utility and usability of LLMs for legitimate users? Existing research predominantly focuses on the effectiveness of defense strategies without thoroughly examining their impact on performance, leaving a gap in understanding the trade-offs between LLM safety and performance. Our research addresses this gap by conducting a comprehensive study on the utility degradation, safety elevation, and exaggerated-safety escalation of LLMs with jailbreak defense strategies. We propose USEBench, a novel benchmark designed to evaluate these aspects, along with USEIndex, a comprehensive metric for assessing overall model performance. Through experiments on seven state-of-the-art LLMs, we found that mainstream jailbreak defenses fail to ensure both safety and performance simultaneously. Although model-finetuning performs the best overall, their effectiveness varies across LLMs. Furthermore, vertical comparisons reveal that developers commonly prioritize performance over safety when iterating or fine-tuning their LLMs.

[Arxiv](https://arxiv.org/abs/2501.12210)