# aLLoyM：专为合金相图预测打造的大语言模型

发布时间：2025年07月30日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLMs）在材料科学中的应用，特别是通过微调模型来处理合金成分、温度及相信息。研究展示了aLLoyM模型在相图生成中的潜力，属于LLM的实际应用案例。` `材料科学` `合金设计`

> aLLoyM: A large language model for alloy phase diagram prediction

# 摘要

> 大型语言模型（LLMs）在材料科学等领域具有广泛应用。我们开发了aLLoyM，这是专为合金成分、温度及相信息设计的微调模型。通过开源的计算相图数据库（CPDDB）和CALPHAD方法，我们整理了二元与三元相图的问答对，并对开源模型Mistral进行了选择题和简答题两种格式的微调。基准测试显示，微调显著提升了相图选择题的性能。aLLoyM的简答题模型能够仅凭成分生成新型相图，展现了其在探索新材领域的重要潜力。我们已将aLLoyM的简答题微调版本及完整问答数据集公开发布于Hugging Face平台，以促进进一步研究与应用。

> Large Language Models (LLMs) are general-purpose tools with wide-ranging applications, including in materials science. In this work, we introduce aLLoyM, a fine-tuned LLM specifically trained on alloy compositions, temperatures, and their corresponding phase information. To develop aLLoyM, we curated question-and-answer (Q&A) pairs for binary and ternary phase diagrams using the open-source Computational Phase Diagram Database (CPDDB) and assessments based on CALPHAD (CALculation of PHAse Diagrams). We fine-tuned Mistral, an open-source pre-trained LLM, for two distinct Q&A formats: multiple-choice and short-answer. Benchmark evaluations demonstrate that fine-tuning substantially enhances performance on multiple-choice phase diagram questions. Moreover, the short-answer model of aLLoyM exhibits the ability to generate novel phase diagrams from its components alone, underscoring its potential to accelerate the discovery of previously unexplored materials systems. To promote further research and adoption, we have publicly released the short-answer fine-tuned version of aLLoyM, along with the complete benchmarking Q&A dataset, on Hugging Face.

[Arxiv](https://arxiv.org/abs/2507.22558)