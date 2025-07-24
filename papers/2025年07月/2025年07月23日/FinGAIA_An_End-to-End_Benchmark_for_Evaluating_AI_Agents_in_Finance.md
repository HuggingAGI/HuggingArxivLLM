# # FinGAIA：金融领域AI智能体全流程评测基准

发布时间：2025年07月23日

`Agent` `基准测试`

> FinGAIA: An End-to-End Benchmark for Evaluating AI Agents in Finance

# 摘要

> AI代理的蓬勃发展为跨领域复杂任务的自动化带来了前所未有的机遇。然而，AI代理在金融领域的多步骤、多工具协作能力尚待深入研究。本文介绍了FinGAIA——首个专注于金融领域的端到端基准测试，用于评估AI代理的实际能力。FinGAIA包含407个精心设计的任务，覆盖证券、基金、银行、保险、期货、信托和资产管理七大金融子领域。这些任务按场景深度分为基础业务分析、资产决策支持和战略风险管理三个层级。我们在零-shot设置下评估了10个主流AI代理，其中表现最佳的ChatGPT实现了48.9%的整体准确率。这一结果优于非专业人士，但仍比金融专家低35个百分点以上。通过错误分析，我们发现五个常见的失败模式：跨模态对齐不足、金融术语偏见、操作流程认知障碍等，这些模式为未来研究指明了方向。我们的工作提供了首个与金融领域密切相关的代理基准，旨在客观评估并推动该关键领域中代理的发展。部分数据可在（https://github.com/SUFE-AIFLM-Lab/FinGAIA）获取。

> The booming development of AI agents presents unprecedented opportunities for automating complex tasks across various domains. However, their multi-step, multi-tool collaboration capabilities in the financial sector remain underexplored. This paper introduces FinGAIA, an end-to-end benchmark designed to evaluate the practical abilities of AI agents in the financial domain. FinGAIA comprises 407 meticulously crafted tasks, spanning seven major financial sub-domains: securities, funds, banking, insurance, futures, trusts, and asset management. These tasks are organized into three hierarchical levels of scenario depth: basic business analysis, asset decision support, and strategic risk management. We evaluated 10 mainstream AI agents in a zero-shot setting. The best-performing agent, ChatGPT, achieved an overall accuracy of 48.9\%, which, while superior to non-professionals, still lags financial experts by over 35 percentage points. Error analysis has revealed five recurring failure patterns: Cross-modal Alignment Deficiency, Financial Terminological Bias, Operational Process Awareness Barrier, among others. These patterns point to crucial directions for future research. Our work provides the first agent benchmark closely related to the financial domain, aiming to objectively assess and promote the development of agents in this crucial field. Partial data is available at https://github.com/SUFE-AIFLM-Lab/FinGAIA.

[Arxiv](https://arxiv.org/abs/2507.17186)