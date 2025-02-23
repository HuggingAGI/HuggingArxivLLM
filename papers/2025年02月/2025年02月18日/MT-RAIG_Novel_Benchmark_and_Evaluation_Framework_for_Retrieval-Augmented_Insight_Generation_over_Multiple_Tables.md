# MT-RAIG：针对多表环境下检索增强型见解生成的创新基准与评估体系。

发布时间：2025年02月18日

`LLM应用

理由：该论文讨论了基于表格的推理研究从问答扩展到提供可解释分析的洞察任务，并引入了MT-RAIG Bench和Eval框架来解决多表格推理问题，提升评估方法。这属于将大型语言模型应用于特定任务（如推理和分析）的范畴，因此归类为LLM应用。` `数据分析` `人工智能`

> MT-RAIG: Novel Benchmark and Evaluation Framework for Retrieval-Augmented Insight Generation over Multiple Tables

# 摘要

> 基于表格的推理研究已从问答扩展到提供可解释分析的洞察任务，现有研究局限于单个表格，而MT-RAIG Bench和Eval框架旨在解决多表格推理的问题，并提升评估方法。

> Recent advancements in table-based reasoning have expanded beyond factoid-level QA to address insight-level tasks, where systems should synthesize implicit knowledge in the table to provide explainable analyses. Although effective, existing studies remain confined to scenarios where a single gold table is given alongside the user query, failing to address cases where users seek comprehensive insights from multiple unknown tables. To bridge these gaps, we propose MT-RAIG Bench, design to evaluate systems on Retrieval-Augmented Insight Generation over Mulitple-Tables. Additionally, to tackle the suboptimality of existing automatic evaluation methods in the table domain, we further introduce a fine-grained evaluation framework MT-RAIG Eval, which achieves better alignment with human quality judgments on the generated insights. We conduct extensive experiments and reveal that even frontier LLMs still struggle with complex multi-table reasoning, establishing our MT-RAIG Bench as a challenging testbed for future research.

[Arxiv](https://arxiv.org/abs/2502.11735)