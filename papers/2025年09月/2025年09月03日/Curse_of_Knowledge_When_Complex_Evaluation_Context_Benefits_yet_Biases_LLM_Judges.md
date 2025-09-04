# 知识的诅咒：复杂评估语境何时对LLM评判者有益却也造成偏见

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Curse of Knowledge: When Complex Evaluation Context Benefits yet Biases LLM Judges

# 摘要

> 随着大型语言模型（LLMs）能力持续提升，其面临的任务愈发多样复杂，可靠评估的难度也随之加大。LLMs作为评判者的范式虽已成为可扩展的解决方案，但现有研究多局限于简单场景。而在复杂任务中（这类任务需依赖多维度评分标准、非结构化参考答案及细微评判标准），LLMs评判的可靠性研究仍显不足。为此，我们构建了ComplexEval挑战基准，旨在系统揭示并量化辅助信息诱导偏差。我们在12个基础场景和3个高级场景中，系统探究并验证了6种此前未被关注的偏差。核心发现如下：（1）所有受评估模型均对这些偏差表现出显著敏感性，且偏差程度随任务复杂度增加而上升；（2）尤为值得注意的是，大型推理模型（LRMs）呈现出矛盾的脆弱性。我们的深入分析为提升评估信号的准确性与可验证性提供了关键洞见，也为构建更通用、更稳健的评估模型奠定了基础。

> As large language models (LLMs) grow more capable, they face increasingly diverse and complex tasks, making reliable evaluation challenging. The paradigm of LLMs as judges has emerged as a scalable solution, yet prior work primarily focuses on simple settings. Their reliability in complex tasks--where multi-faceted rubrics, unstructured reference answers, and nuanced criteria are critical--remains understudied. In this paper, we constructed ComplexEval, a challenge benchmark designed to systematically expose and quantify Auxiliary Information Induced Biases. We systematically investigated and validated 6 previously unexplored biases across 12 basic and 3 advanced scenarios. Key findings reveal: (1) all evaluated models exhibit significant susceptibility to these biases, with bias magnitude scaling with task complexity; (2) notably, Large Reasoning Models (LRMs) show paradoxical vulnerability. Our in-depth analysis offers crucial insights for improving the accuracy and verifiability of evaluation signals, paving the way for more general and robust evaluation models.

[Arxiv](https://arxiv.org/abs/2509.03419)