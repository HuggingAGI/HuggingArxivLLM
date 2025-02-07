# 基于代理的不确定性感知技术，结合开源大型语言模型，显著提升了放射学报告的自动化标注效果

发布时间：2025年02月02日

`Agent

理由：这篇论文提出了一种基于代理的不确定性感知方法，用于提升大型语言模型（LLM）在医疗应用中的预测可信度。该方法通过代理模型整合多个提示输出，并校准不确定性，最终提升了LLM在放射学报告结构化数据提取中的性能与可靠性。论文的核心在于代理模型的设计和应用，因此应归类为Agent。` `放射学`

> Agent-Based Uncertainty Awareness Improves Automated Radiology Report Labeling with an Open-Source Large Language Model

# 摘要

> # 摘要
从放射学报告中可靠提取结构化数据，尤其是希伯来语等复杂非英语文本，对大型语言模型（LLMs）仍具挑战。本研究提出了一种基于代理的不确定性感知方法，旨在提升LLM在医疗应用中的预测可信度。我们分析了2010年至2023年间来自三家医疗中心的9,683份克罗恩病患者的希伯来语放射学报告。其中512份报告手动标注了六个胃肠道器官和15种病理发现，其余报告则通过HSMP-BERT自动标注。数据提取采用Llama 3.1（Llama 3-8b-instruct）和贝叶斯提示集成（BayesPE），后者通过六个语义等效提示估计不确定性。基于代理的决策模型将多个提示输出整合为五个置信级别，用于校准不确定性，并与三个基于熵的模型进行对比。在过滤高不确定性案例前后，使用准确率、F1分数、精确率、召回率和Cohen's Kappa评估性能。结果显示，基于代理的模型在所有指标上均优于基线，F1分数为0.3967，召回率为0.6437，Cohen's Kappa为0.3006。过滤高不确定性案例（≥0.5）后，F1分数提升至0.4787，Kappa增至0.4258。不确定性直方图清晰区分了正确与错误预测，基于代理的模型提供了最校准的不确定性估计。通过结合不确定性感知提示集成和基于代理的决策模型，该方法显著提升了LLM在放射学报告结构化数据提取中的性能与可靠性，为高风险医疗应用提供了更可解释且可信的解决方案。

> Reliable extraction of structured data from radiology reports using Large Language Models (LLMs) remains challenging, especially for complex, non-English texts like Hebrew. This study introduces an agent-based uncertainty-aware approach to improve the trustworthiness of LLM predictions in medical applications. We analyzed 9,683 Hebrew radiology reports from Crohn's disease patients (from 2010 to 2023) across three medical centers. A subset of 512 reports was manually annotated for six gastrointestinal organs and 15 pathological findings, while the remaining reports were automatically annotated using HSMP-BERT. Structured data extraction was performed using Llama 3.1 (Llama 3-8b-instruct) with Bayesian Prompt Ensembles (BayesPE), which employed six semantically equivalent prompts to estimate uncertainty. An Agent-Based Decision Model integrated multiple prompt outputs into five confidence levels for calibrated uncertainty and was compared against three entropy-based models. Performance was evaluated using accuracy, F1 score, precision, recall, and Cohen's Kappa before and after filtering high-uncertainty cases. The agent-based model outperformed the baseline across all metrics, achieving an F1 score of 0.3967, recall of 0.6437, and Cohen's Kappa of 0.3006. After filtering high-uncertainty cases (greater than or equal to 0.5), the F1 score improved to 0.4787, and Kappa increased to 0.4258. Uncertainty histograms demonstrated clear separation between correct and incorrect predictions, with the agent-based model providing the most well-calibrated uncertainty estimates. By incorporating uncertainty-aware prompt ensembles and an agent-based decision model, this approach enhances the performance and reliability of LLMs in structured data extraction from radiology reports, offering a more interpretable and trustworthy solution for high-stakes medical applications.

[Arxiv](https://arxiv.org/abs/2502.01691)