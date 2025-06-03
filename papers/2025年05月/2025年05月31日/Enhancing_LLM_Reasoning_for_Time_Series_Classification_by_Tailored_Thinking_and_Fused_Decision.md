# 提升 LLM 的时间序列分类推理性能：定制化思维与融合决策的结合

发布时间：2025年05月31日

`LLM应用` `时间序列分析` `机器学习`

> Enhancing LLM Reasoning for Time Series Classification by Tailored Thinking and Fused Decision

# 摘要

> 大语言模型（LLMs）的推理能力显著提升了其在多样化任务中的表现。随着LLMs在时间序列领域的应用日益受到关注，这一任务的挑战性也逐渐显现，简单地将文本领域推理技术迁移到时间序列领域效果有限。尽管最近的工作在多个时间序列任务中展现了潜力，但对于广泛存在于众多现实应用中的时间序列分类（TSC）任务，进一步利用LLM推理的潜力仍未被充分挖掘。本文提出了一种名为ReasonTSC的新框架，旨在通过多轮推理和专门针对TSC的融合决策策略，有效利用LLM推理进行时间序列分类。与直接套用现有推理技术或仅依赖LLMs内置推理能力不同，ReasonTSC首先引导模型关注时间序列数据的关键特征。随后，它整合了插件分类器（如特定领域的时间序列模型）的预测结果和置信分数作为上下文示例。最后，ReasonTSC通过结构化的推理过程引导LLM：评估初步结论，回溯以考虑替代假设，比较它们的优劣，最终得出准确分类。实验和消融研究表明，ReasonTSC在现有基线和插件模型中表现优异，甚至能够识别并纠正插件模型的错误预测。

> The reasoning capabilities of large language models (LLMs) have significantly advanced their performance by enabling in-depth understanding of diverse tasks. With growing interest in applying LLMs to the time series domain, this has proven nontrivial, as evidenced by the limited efficacy of straightforwardly adapting text-domain reasoning techniques. Although recent work has shown promise in several time series tasks, further leveraging advancements in LLM reasoning remains under-explored for time series classification (TSC) tasks, despite their prevalence and significance in many real-world applications. In this paper, we propose ReasonTSC, a novel framework designed to effectively leverage LLM reasoning for time series classification through both a multi-turn reasoning and a fused decision-making strategy tailored to TSC. Rather than straightforwardly applying existing reasoning techniques or relying solely on LLMs' built-in reasoning capabilities, ReasonTSC first steers the model to think over the essential characteristics of time series data. Next, it integrates predictions and confidence scores from plug-in classifiers, e.g., domain-specific time series models, as in-context examples. Finally, ReasonTSC guides the LLM through a structured reasoning process: it evaluates the initial assessment, backtracks to consider alternative hypotheses, and compares their merits before arriving at a final classification. Extensive experiments and systematic ablation studies demonstrate that ReasonTSC consistently outperforms both existing time series reasoning baselines and plug-in models, and is even capable of identifying and correcting plug-in models' false predictions.

[Arxiv](https://arxiv.org/abs/2506.00807)