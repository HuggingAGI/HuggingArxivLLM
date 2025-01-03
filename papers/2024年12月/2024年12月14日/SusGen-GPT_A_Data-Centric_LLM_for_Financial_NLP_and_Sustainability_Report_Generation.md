# SusGen-GPT: 专为金融NLP和可持续发展报告生成打造的数据驱动型LLM

发布时间：2024年12月14日

`LLM应用

理由：这篇论文主要介绍了在金融和ESG领域开发和应用LLM（大型语言模型）的具体工作，包括数据集的创建、基准的提出、模型的开发以及结合RAG（检索增强生成）技术的系统设计。这些内容都属于LLM在实际应用中的具体实现和优化，因此分类为“LLM应用”。` `ESG`

> SusGen-GPT: A Data-Centric LLM for Financial NLP and Sustainability Report Generation

# 摘要

> 金融行业的迅猛发展和对ESG（环境、社会和治理）的日益重视，催生了对先进NLP工具的迫切需求。然而，精通金融与ESG的开源LLMs依然稀缺。为此，我们推出了SusGen-30K数据集，涵盖七项金融NLP任务和ESG报告生成，并提出了TCFD-Bench基准，用于评估可持续性报告生成。基于此数据集，我们开发了SusGen-GPT模型套件，在六项定制任务和两项现成任务上达到了顶尖水平，尽管参数仅为7-8B，与GPT-4的1,700B相比，性能仅落后2%。我们进一步提出了结合RAG的SusGen系统，助力可持续性报告生成。这一成果展示了我们方法的高效性，推动了金融与ESG领域的研究进展。

> The rapid growth of the financial sector and the rising focus on Environmental, Social, and Governance (ESG) considerations highlight the need for advanced NLP tools. However, open-source LLMs proficient in both finance and ESG domains remain scarce. To address this gap, we introduce SusGen-30K, a category-balanced dataset comprising seven financial NLP tasks and ESG report generation, and propose TCFD-Bench, a benchmark for evaluating sustainability report generation. Leveraging this dataset, we developed SusGen-GPT, a suite of models achieving state-of-the-art performance across six adapted and two off-the-shelf tasks, trailing GPT-4 by only 2% despite using 7-8B parameters compared to GPT-4's 1,700B. Based on this, we propose the SusGen system, integrated with Retrieval-Augmented Generation (RAG), to assist in sustainability report generation. This work demonstrates the efficiency of our approach, advancing research in finance and ESG.

[Arxiv](https://arxiv.org/abs/2412.10906)