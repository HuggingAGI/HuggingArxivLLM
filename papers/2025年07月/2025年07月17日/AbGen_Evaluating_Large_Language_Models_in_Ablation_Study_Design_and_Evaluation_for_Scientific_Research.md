# AbGen：用于科学实验设计的大型语言模型消融研究评估

发布时间：2025年07月17日

`LLM应用` `消融实验`

> AbGen: Evaluating Large Language Models in Ablation Study Design and Evaluation for Scientific Research

# 摘要

> 我们推出AbGen，首个专注于评估大型语言模型（LLMs）在科研中设计消融实验能力的基准测试。AbGen由807篇NLP论文中提取的1,500个专家标注案例组成。在该基准测试中，LLMs需根据给定的研究背景，为指定模块或流程设计详细消融实验方案。我们对DeepSeek-R1-0528和o4-mini等领先模型的评估显示，这些模型与人类专家在消融实验设计的重要性和可靠性方面存在显著差距。此外，我们发现现有自动化评估方法对于本任务并不可靠，与人工评估结果存在明显偏差。为深入研究这一问题，我们开发了AbGen-Eval，这是一个元评估基准，用于评估常用自动化评估系统在衡量LLMs性能方面的可靠性。我们在AbGen-Eval上研究了多种基于LLM的评估系统，为未来开发更高效可靠的基于LLM的复杂科学任务评估系统提供了重要启示。

> We introduce AbGen, the first benchmark designed to evaluate the capabilities of LLMs in designing ablation studies for scientific research. AbGen consists of 1,500 expert-annotated examples derived from 807 NLP papers. In this benchmark, LLMs are tasked with generating detailed ablation study designs for a specified module or process based on the given research context. Our evaluation of leading LLMs, such as DeepSeek-R1-0528 and o4-mini, highlights a significant performance gap between these models and human experts in terms of the importance, faithfulness, and soundness of the ablation study designs. Moreover, we demonstrate that current automated evaluation methods are not reliable for our task, as they show a significant discrepancy when compared to human assessment. To better investigate this, we develop AbGen-Eval, a meta-evaluation benchmark designed to assess the reliability of commonly used automated evaluation systems in measuring LLM performance on our task. We investigate various LLM-as-Judge systems on AbGen-Eval, providing insights for future research on developing more effective and reliable LLM-based evaluation systems for complex scientific tasks.

[Arxiv](https://arxiv.org/abs/2507.13300)