# # 中文语境下DeepSeek模型的安全性评估与优化  
本研究专注于评估并优化DeepSeek模型在中文环境中的安全性表现。

发布时间：2025年03月18日

`LLM应用

理由：这篇论文主要研究的是大型语言模型（LLM）在实际应用中的安全性问题，特别是针对深度求索-R1模型及其蒸馏模型的安全漏洞进行评估和增强。论文中提到的CHiSafetyBench基准测试、模型安全性的分析以及安全增强措施，都属于对LLM在实际应用中的优化和改进，因此归类为LLM应用。` `人工智能` `模型安全`

> Safety Evaluation and Enhancement of DeepSeek Models in Chinese Contexts

# 摘要

> 深度求索-R1 凭借卓越的推理能力和开源策略，正在重塑全球人工智能格局。然而，该模型在安全性方面存在显著短板。近期研究发现，深度求索-R1 在处理有害提示时的攻击成功率高达100%，多家安全机构也发现了其关键安全漏洞。虽然 R1 在中文语境下的安全问题已被中国联通发现，但对其系列蒸馏模型的安全能力尚未进行全面评估。为此，本研究采用中文安全基准 CHiSafetyBench，深入评估了深度求索-R1 系列蒸馏模型的安全性，分析蒸馏对模型安全性的潜在影响。在此基础上，我们针对六种蒸馏模型进行了安全增强。实验结果显示，增强后的模型在保持推理能力的同时，安全性显著提升。我们已将这些安全增强模型开源至 https://github.com/UnicomAI/DeepSeek-R1-Distill-Safe/tree/main，为未来深度求索模型的研究与优化提供了重要参考。


> DeepSeek-R1, renowned for its exceptional reasoning capabilities and open-source strategy, is significantly influencing the global artificial intelligence landscape. However, it exhibits notable safety shortcomings. Recent research conducted by Robust Intelligence, a subsidiary of Cisco, in collaboration with the University of Pennsylvania, revealed that DeepSeek-R1 achieves a 100\% attack success rate when processing harmful prompts. Furthermore, multiple security firms and research institutions have identified critical security vulnerabilities within the model. Although China Unicom has uncovered safety vulnerabilities of R1 in Chinese contexts, the safety capabilities of the remaining distilled models in the R1 series have not yet been comprehensively evaluated. To address this gap, this study utilizes the comprehensive Chinese safety benchmark CHiSafetyBench to conduct an in-depth safety evaluation of the DeepSeek-R1 series distilled models. The objective is to assess the safety capabilities of these models in Chinese contexts both before and after distillation, and to further elucidate the adverse effects of distillation on model safety. Building on these findings, we implement targeted safety enhancements for six distilled models. Evaluation results indicate that the enhanced models achieve significant improvements in safety while maintaining reasoning capabilities without notable degradation. We open-source the safety-enhanced models at https://github.com/UnicomAI/DeepSeek-R1-Distill-Safe/tree/main to serve as a valuable resource for future research and optimization of DeepSeek models.

[Arxiv](https://arxiv.org/abs/2503.16529)