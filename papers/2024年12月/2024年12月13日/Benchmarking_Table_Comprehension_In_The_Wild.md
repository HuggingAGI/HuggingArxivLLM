# 对野外表理解的基准测试

发布时间：2024年12月13日

`LLM应用`

> Benchmarking Table Comprehension In The Wild

# 摘要

> 大型语言模型（LLMs）在众多知识密集型活动中已渐趋主导，然而在理解诸如学术论文和财务报告这类冗长的表文混合内容时，成果有限。长上下文LLMs的最新进展为该领域带来新契机。但我们发现了两个阻碍：（1）此前的表格问答（TableQA）基准测试聚焦于无上下文的孤立表格，导致难以在实际场景中评估模型。（2）之前的基准测试侧重于表格理解的某些狭窄技能集，像表格识别、数据操作/计算、表格总结等，而熟练的人会综合运用这些技能。在本项工作中，我们推出了TableQuest这一新基准测试，用于评估LLMs在财务报告这种自然富含表格的上下文中的整体表格理解能力。我们采用严格的数据处理和筛选流程，保证问答对具备逻辑性、合理性和多样性。我们对7个前沿模型进行实验，发现尽管在定位事实方面有一定准确性，但在需要进行更复杂推理或多步骤计算时，它们往往表现不佳。我们以对失败模式的定性研究作结，并探讨了构建有挑战性基准测试的难题。我们将本研究的评估数据、判断流程和结果公开，以推动该领域的研究。

> Large Language Models (LLMs), while being increasingly dominant on a myriad of knowledge-intensive activities, have only had limited success understanding lengthy table-text mixtures, such as academic papers and financial reports. Recent advances of long-context LLMs have opened up new possibilities for this field. Nonetheless, we identify two roadblocks: (1) Prior benchmarks of table question answering (TableQA) have focused on isolated tables without context, making it hard to evaluate models in real-world scenarios. (2) Prior benchmarks have focused on some narrow skill sets of table comprehension such as table recognition, data manipulation/calculation, table summarization etc., while a skilled human employs those skills collectively. In this work, we introduce TableQuest, a new benchmark designed to evaluate the holistic table comprehension capabilities of LLMs in the natural table-rich context of financial reports. We employ a rigorous data processing and filtering procedure to ensure that the question-answer pairs are logical, reasonable, and diverse. We experiment with 7 state-of-the-art models, and find that despite reasonable accuracy in locating facts, they often falter when required to execute more sophisticated reasoning or multi-step calculations. We conclude with a qualitative study of the failure modes and discuss the challenges of constructing a challenging benchmark. We make the evaluation data, judging procedure and results of this study publicly available to facilitate research in this field.

[Arxiv](https://arxiv.org/abs/2412.09884)