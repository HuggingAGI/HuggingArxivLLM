# REPA：用于评测文本生成与判断能力的俄语错误类型标注方案

发布时间：2025年03月17日

`LLM应用

理由：该论文探讨了大型语言模型（LLMs）在评估和评分其他LLM输出中的应用，特别是在俄语环境中的表现。研究通过引入特定的数据集和分析方法，评估了LLM作为裁判的有效性，属于应用层面的研究。` `语言处理`

> REPA: Russian Error Types Annotation for Evaluating Text Generation and Judgment Capabilities

# 摘要

> 大型语言模型（LLMs）的最新进展开创了一种全新范式：将LLM用作裁判，通过评估和评分其他LLM的输出结果，这种评估通常与人类偏好高度一致。然而，现有研究主要聚焦于英语环境。本文通过引入俄罗斯错误类型标注数据集（REPA），对这一框架在俄语中的应用进行了探索。该数据集包含1,000条用户查询和2,000条LLM生成的响应。人工标注员对每对响应进行了标注，涵盖了十种具体错误类型的偏好，并选择了整体偏好。基于人类偏好，我们采用三种评分系统对六种生成式LLM进行了错误类型排名。同时，我们使用八种LLM裁判在零样本和少样本设置下对响应进行了评估。我们对裁判和位置及长度偏见进行了分析。研究发现，俄语和英语环境下LLM裁判的表现存在显著差距。然而，基于人类和LLM偏好的排名显示出一定程度的重叠，表明尽管当前LLM裁判在俄语中难以实现精细评估，但仍有改进潜力。

> Recent advances in large language models (LLMs) have introduced the novel paradigm of using LLMs as judges, where an LLM evaluates and scores the outputs of another LLM, which often correlates highly with human preferences. However, the use of LLM-as-a-judge has been primarily studied in English. In this paper, we evaluate this framework in Russian by introducing the Russian Error tyPes Annotation dataset (REPA), a dataset of 1k user queries and 2k LLM-generated responses. Human annotators labeled each response pair expressing their preferences across ten specific error types, as well as selecting an overall preference. We rank six generative LLMs across the error types using three rating systems based on human preferences. We also evaluate responses using eight LLM judges in zero-shot and few-shot settings. We describe the results of analyzing the judges and position and length biases. Our findings reveal a notable gap between LLM judge performance in Russian and English. However, rankings based on human and LLM preferences show partial alignment, suggesting that while current LLM judges struggle with fine-grained evaluation in Russian, there is potential for improvement.

[Arxiv](https://arxiv.org/abs/2503.13102)