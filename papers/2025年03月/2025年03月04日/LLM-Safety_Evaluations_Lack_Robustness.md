# # LLM 安全评估的鲁棒性不足

发布时间：2025年03月04日

`LLM理论

摘要讨论了大型语言模型（LLM）安全对齐研究中的挑战和评估问题，分析了评估流程中的关键环节，并提出了改进评估的方法。这属于理论层面的研究，因此归类为LLM理论。` `人工智能安全` `模型评估`

> LLM-Safety Evaluations Lack Robustness

# 摘要

> 本文认为，当前大型语言模型（LLM）的安全对齐研究正受到多种相互交织的噪声源阻碍，包括小规模数据集、方法论不一致以及不可靠的评估设置。这些因素有时会导致攻击与防御的公平评估变得困难，从而延缓研究进展。我们系统性地分析了LLM安全评估的全流程，涵盖数据集整理、自动化红队攻击策略优化、响应生成以及基于LLM评估者的响应评估。在每个环节，我们都识别了关键问题并强调了其实际影响。此外，我们提出了减少未来攻击与防御论文评估中噪声与偏差的指南。最后，我们从另一个角度探讨了现有局限性的实际原因。我们相信，未来研究若能解决上述问题，将有助于提升领域内生成易于比较的结果的能力，并推动可衡量的进步。

> In this paper, we argue that current safety alignment research efforts for large language models are hindered by many intertwined sources of noise, such as small datasets, methodological inconsistencies, and unreliable evaluation setups. This can, at times, make it impossible to evaluate and compare attacks and defenses fairly, thereby slowing progress. We systematically analyze the LLM safety evaluation pipeline, covering dataset curation, optimization strategies for automated red-teaming, response generation, and response evaluation using LLM judges. At each stage, we identify key issues and highlight their practical impact. We also propose a set of guidelines for reducing noise and bias in evaluations of future attack and defense papers. Lastly, we offer an opposing perspective, highlighting practical reasons for existing limitations. We believe that addressing the outlined problems in future research will improve the field's ability to generate easily comparable results and make measurable progress.

[Arxiv](https://arxiv.org/abs/2503.02574)