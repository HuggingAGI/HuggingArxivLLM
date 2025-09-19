# CLEAR：大型语言模型论证改写的全面语言评估

发布时间：2025年09月18日

`LLM应用` `基础理论`

> CLEAR: A Comprehensive Linguistic Evaluation of Argument Rewriting by Large Language Models

# 摘要

> 虽然大型语言模型（LLMs）在通用文本生成任务上的研究已十分深入，但在文本重写这一相关任务（尤其是模型在该任务中的行为）上的探索仍较为有限。本文聚焦LLMs在文本重写场景中的具体改动，重点研究议论文的优化问题，并将其定义为“论点改进任务”（ArgImp）。我们提出了CLEAR评估框架：该框架包含57个指标，覆盖词汇、句法、语义和语用四个语言层面。借助这一框架，我们在多个议论文语料库上评估LLM重写论点的质量，并从语言层面比较和分析不同LLMs的表现。综合四个语言层面的分析发现，模型在执行ArgImp任务时，会通过缩短文本长度、增加平均词长和合并句子来实现改进。总体来看，重写后的论点在说服力和连贯性维度上均有提升。

> While LLMs have been extensively studied on general text generation tasks, there is less research on text rewriting, a task related to general text generation, and particularly on the behavior of models on this task. In this paper we analyze what changes LLMs make in a text rewriting setting. We focus specifically on argumentative texts and their improvement, a task named Argument Improvement (ArgImp). We present CLEAR: an evaluation pipeline consisting of 57 metrics mapped to four linguistic levels: lexical, syntactic, semantic and pragmatic. This pipeline is used to examine the qualities of LLM-rewritten arguments on a broad set of argumentation corpora and compare the behavior of different LLMs on this task and analyze the behavior of different LLMs on this task in terms of linguistic levels. By taking all four linguistic levels into consideration, we find that the models perform ArgImp by shortening the texts while simultaneously increasing average word length and merging sentences. Overall we note an increase in the persuasion and coherence dimensions.

[Arxiv](https://arxiv.org/abs/2509.15027)