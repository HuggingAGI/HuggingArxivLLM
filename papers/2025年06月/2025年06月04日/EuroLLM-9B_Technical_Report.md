# EuroLLM-9B技术报告

发布时间：2025年06月04日

`LLM应用` `多语言处理` `机器翻译`

> EuroLLM-9B: Technical Report

# 摘要

> 我们正式发布 EuroLLM-9B，一个专为满足欧洲公民需求而打造的大型语言模型，全面支持欧盟24种官方语言和11种其他语言。针对现有开源大模型中欧洲语言代表性不足的问题，EuroLLM 应运而生。本报告详细介绍了 EuroLLM-9B 的开发历程，涵盖分词器设计、架构规格、数据筛选及训练流程等核心环节。我们特别介绍了预训练数据采集与筛选管道，其中包括 EuroFilter（一款AI驱动的多语言过滤器）的开发，以及 EuroBlocks-Synthetic（一个专为提升欧洲语言覆盖而设计的新型合成数据集）。评估结果显示，EuroLLM-9B 在多语言基准测试和机器翻译任务中表现优异，已成为同规模领先的开源欧洲制造大模型。为了推动开放研究与应用，我们开源了该模型的所有关键组件，包括基础模型、指令微调模型、EuroFilter 分类器和合成后训练数据集。

> This report presents EuroLLM-9B, a large language model trained from scratch to support the needs of European citizens by covering all 24 official European Union languages and 11 additional languages. EuroLLM addresses the issue of European languages being underrepresented and underserved in existing open large language models. We provide a comprehensive overview of EuroLLM-9B's development, including tokenizer design, architectural specifications, data filtering, and training procedures. We describe the pre-training data collection and filtering pipeline, including the creation of EuroFilter, an AI-based multilingual filter, as well as the design of EuroBlocks-Synthetic, a novel synthetic dataset for post-training that enhances language coverage for European languages. Evaluation results demonstrate EuroLLM-9B's competitive performance on multilingual benchmarks and machine translation tasks, establishing it as the leading open European-made LLM of its size. To support open research and adoption, we release all major components of this work, including the base and instruction-tuned models, the EuroFilter classifier, and the synthetic post-training dataset.

[Arxiv](https://arxiv.org/abs/2506.04079)