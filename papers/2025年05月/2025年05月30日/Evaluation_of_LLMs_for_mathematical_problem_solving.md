# 评估大型语言模型解决数学问题的能力

发布时间：2025年05月30日

`LLM应用` `模型评估`

> Evaluation of LLMs for mathematical problem solving

# 摘要

> 大型语言模型（LLMs）在教育任务中表现优异，但在解决数学问题方面仍有待深入研究。本研究对比了GPT-4o、DeepSeek-V3和Gemini-2.0三个模型，在GSM8K、MATH500和UNSW三个数据集上进行评估。基于结构化思维链（SCoT）框架，从最终答案正确性、步骤完整性、步骤有效性、中间计算准确性和问题理解能力五个维度进行评估。结果显示，GPT-4o在所有数据集中表现最为稳定，尤其在UNSW数据集的高难度问题上表现突出。DeepSeek-V3在优化等结构化领域表现强劲，但在统计推断任务中准确性波动较大。Gemini-2.0在结构化问题中语言理解和清晰度出色，但在多步推理和符号逻辑方面表现欠佳。错误分析显示：GPT-4o有时解释不足或不够精确；DeepSeek-V3常遗漏中间步骤；Gemini-2.0在高维数学推理中灵活性较低。

> Large Language Models (LLMs) have shown impressive performance on a range of educational tasks, but are still understudied for their potential to solve mathematical problems. In this study, we compare three prominent LLMs, including GPT-4o, DeepSeek-V3, and Gemini-2.0, on three mathematics datasets of varying complexities (GSM8K, MATH500, and UNSW datasets). We take a five-dimensional approach based on the Structured Chain-of-Thought (SCoT) framework to assess final answer correctness, step completeness, step validity, intermediate calculation accuracy, and problem comprehension. The results show that GPT-4o is the most stable and consistent in performance across all the datasets, but particularly it performs outstandingly in high-level questions of the UNSW dataset. DeepSeek-V3 is competitively strong in well-structured domains such as optimisation, but suffers from fluctuations in accuracy in statistical inference tasks. Gemini-2.0 shows strong linguistic understanding and clarity in well-structured problems but performs poorly in multi-step reasoning and symbolic logic. Our error analysis reveals particular deficits in each model: GPT-4o is at times lacking in sufficient explanation or precision; DeepSeek-V3 leaves out intermediate steps; and Gemini-2.0 is less flexible in mathematical reasoning in higher dimensions.

[Arxiv](https://arxiv.org/abs/2506.00309)