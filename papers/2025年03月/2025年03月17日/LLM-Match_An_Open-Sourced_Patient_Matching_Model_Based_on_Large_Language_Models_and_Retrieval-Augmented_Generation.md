# LLM-Match：开源的基于大语言模型的患者匹配模型，结合检索增强生成

发布时间：2025年03月17日

`LLM应用` `人工智能`

> LLM-Match: An Open-Sourced Patient Matching Model Based on Large Language Models and Retrieval-Augmented Generation

# 摘要

> 患者匹配旨在通过精准识别和匹配患者的医疗记录与临床试验的入选标准，将患者与合适的临床试验相连接。我们提出了一种名为LLM-Match的创新框架，该框架利用微调的开源大型语言模型实现患者匹配。我们的方法包含四个核心组件：首先，检索增强生成（RAG）模块从海量电子健康记录（EHRs）中提取相关患者背景信息；其次，提示生成模块整合试验入选标准（包括纳入和排除标准）、患者背景以及系统指令，构建输入提示；第三，带有分类头的微调模块通过结构化提示和真实标签优化模型参数；第四，评估模块对微调模型在测试数据集上的性能进行评估。我们在n2c2、SIGIR、TREC 2021和TREC 2022四个公开数据集上评估了LLM-Match，使用开源模型，并与TrialGPT、零-shot以及基于GPT-4的闭源模型进行对比。结果表明，LLM-Match在所有基准模型中表现最优。

> Patient matching is the process of linking patients to appropriate clinical trials by accurately identifying and matching their medical records with trial eligibility criteria. We propose LLM-Match, a novel framework for patient matching leveraging fine-tuned open-source large language models. Our approach consists of four key components. First, a retrieval-augmented generation (RAG) module extracts relevant patient context from a vast pool of electronic health records (EHRs). Second, a prompt generation module constructs input prompts by integrating trial eligibility criteria (both inclusion and exclusion criteria), patient context, and system instructions. Third, a fine-tuning module with a classification head optimizes the model parameters using structured prompts and ground-truth labels. Fourth, an evaluation module assesses the fine-tuned model's performance on the testing datasets. We evaluated LLM-Match on four open datasets, n2c2, SIGIR, TREC 2021, and TREC 2022, using open-source models, comparing it against TrialGPT, Zero-Shot, and GPT-4-based closed models. LLM-Match outperformed all baselines.

[Arxiv](https://arxiv.org/abs/2503.13281)