# PediaBench：一个用于大型语言模型基准测试的全面的中文儿科数据集

发布时间：2024年12月09日

`LLM应用`

> PediaBench: A Comprehensive Chinese Pediatric Dataset for Benchmarking Large Language Models

# 摘要

> 大型语言模型（LLMs）在医疗领域的崭露头角，凸显出对评估其问答（QA）性能的标准数据集的强烈需求。尽管已有若干用于医疗问答的基准数据集，但它们要么涵盖不同科室的通用知识，要么专为其他科室而非儿科设立。而且，其中部分数据集仅局限于客观问题，无法衡量LLMs的生成能力。故而，它们难以全面评估LLMs在儿科领域的问答能力。为弥补这一空缺，我们构建了PediaBench，这是首个用于LLM评估的中文儿科数据集。具体而言，它涵盖了12个儿科疾病组，包含4565个客观问题和1632个主观问题。它采用基于不同难度等级的综合评分标准，全面评估LLM在遵循指令、理解知识、临床病例分析等方面的水平。最后，我们在20个开源和商业LLMs上进行了大量实验，验证了PediaBench的有效性。通过对实验结果的深入剖析，我们就LLMs在中国语境下回答儿科问题的能力提供了见解，指出了其局限性，以推动进一步的改进。我们的代码和数据发布于https://github.com/ACMISLab/PediaBench。

> The emergence of Large Language Models (LLMs) in the medical domain has stressed a compelling need for standard datasets to evaluate their question-answering (QA) performance. Although there have been several benchmark datasets for medical QA, they either cover common knowledge across different departments or are specific to another department rather than pediatrics. Moreover, some of them are limited to objective questions and do not measure the generation capacity of LLMs. Therefore, they cannot comprehensively assess the QA ability of LLMs in pediatrics. To fill this gap, we construct PediaBench, the first Chinese pediatric dataset for LLM evaluation. Specifically, it contains 4,565 objective questions and 1,632 subjective questions spanning 12 pediatric disease groups. It adopts an integrated scoring criterion based on different difficulty levels to thoroughly assess the proficiency of an LLM in instruction following, knowledge understanding, clinical case analysis, etc. Finally, we validate the effectiveness of PediaBench with extensive experiments on 20 open-source and commercial LLMs. Through an in-depth analysis of experimental results, we offer insights into the ability of LLMs to answer pediatric questions in the Chinese context, highlighting their limitations for further improvements. Our code and data are published at https://github.com/ACMISLab/PediaBench.

[Arxiv](https://arxiv.org/abs/2412.06287)