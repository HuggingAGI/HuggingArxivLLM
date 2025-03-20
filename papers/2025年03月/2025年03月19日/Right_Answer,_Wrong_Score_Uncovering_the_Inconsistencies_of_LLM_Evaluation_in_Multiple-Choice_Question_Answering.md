# 正确答案却得低分：揭开 LLM 在多选题问答评估中的不一致现象

发布时间：2025年03月19日

`LLM理论` `问答系统`

> Right Answer, Wrong Score: Uncovering the Inconsistencies of LLM Evaluation in Multiple-Choice Question Answering

# 摘要

> 评估大型语言模型（LLMs）最常用的任务之一是多选题问答（MCQA）。虽然开放式问答更具挑战性，但多选题任务在评估时相对简单，因为模型的答案被认为容易提取，并且可以直接与预设选项进行比较。然而，最近的研究开始质疑MCQA评估的可靠性，表明多种因素可能显著影响LLMs的报告性能，尤其是在模型生成自由文本后才选择答案的情况下。

本研究揭示了MCQA评估策略中的不一致之处，这些不一致可能导致模型比较出现不准确和误导性结果。我们系统性地分析了现有答案提取方法是否与人类判断一致，以及它们如何受到提示中答案约束的影响。实验表明，传统评估策略常常低估LLMs的能力，而基于LLMs的答案提取器容易出现系统性错误。此外，我们揭示了在提示中包含格式约束以简化答案提取与允许模型生成自由文本以提高推理能力之间的根本权衡。

我们的发现呼吁建立标准化的评估方法，并强调了更可靠和一致的MCQA评估实践的必要性。

> One of the most widely used tasks to evaluate Large Language Models (LLMs) is Multiple-Choice Question Answering (MCQA). While open-ended question answering tasks are more challenging to evaluate, MCQA tasks are, in principle, easier to assess, as the model's answer is thought to be simple to extract and is directly compared to a set of predefined choices. However, recent studies have started to question the reliability of MCQA evaluation, showing that multiple factors can significantly impact the reported performance of LLMs, especially when the model generates free-form text before selecting one of the answer choices. In this work, we shed light on the inconsistencies of MCQA evaluation strategies, which can lead to inaccurate and misleading model comparisons. We systematically analyze whether existing answer extraction methods are aligned with human judgment, and how they are influenced by answer constraints in the prompt across different domains. Our experiments demonstrate that traditional evaluation strategies often underestimate LLM capabilities, while LLM-based answer extractors are prone to systematic errors. Moreover, we reveal a fundamental trade-off between including format constraints in the prompt to simplify answer extraction and allowing models to generate free-form text to improve reasoning. Our findings call for standardized evaluation methodologies and highlight the need for more reliable and consistent MCQA evaluation practices.

[Arxiv](https://arxiv.org/abs/2503.14996)