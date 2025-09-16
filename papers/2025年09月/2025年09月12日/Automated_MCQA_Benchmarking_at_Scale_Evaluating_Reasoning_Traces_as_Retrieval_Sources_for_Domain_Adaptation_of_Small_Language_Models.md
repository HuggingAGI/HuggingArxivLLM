# 大规模MCQA自动化基准测试：将推理轨迹作为检索源评估小型语言模型的领域自适应

发布时间：2025年09月12日

`RAG` `医疗健康`

> Automated MCQA Benchmarking at Scale: Evaluating Reasoning Traces as Retrieval Sources for Domain Adaptation of Small Language Models

# 摘要

> 随着科学知识呈爆发式增长，评估基准也需与时俱进——既要反映最新发现，也要确保语言模型能在前沿、多元的文献中接受检验。为此，我们提出了一个可扩展的模块化框架，能直接从海量科学论文语料库生成多选题问答（MCQA）基准。该框架的流程可自动化MCQA创建的全流程，涵盖PDF解析、语义分块、问题生成及模型评估等环节。作为案例研究，我们从22,000篇辐射与癌症生物学领域的开放获取论文中生成了16,000多道多选题。随后，我们用这些问题评估了一系列小型语言模型（参数规模11亿至140亿），对比了基线准确率与基于论文语义分块及GPT-4提取的推理轨迹的检索增强生成（RAG）准确率。结果显示，推理轨迹检索在合成基准和专家标注基准上均能持续提升模型性能，甚至让多个小型模型在2023年Astro辐射与癌症生物学考试中超越了GPT-4。

> As scientific knowledge grows at an unprecedented pace, evaluation benchmarks must evolve to reflect new discoveries and ensure language models are tested on current, diverse literature. We propose a scalable, modular framework for generating multiple-choice question-answering (MCQA) benchmarks directly from large corpora of scientific papers. Our pipeline automates every stage of MCQA creation, including PDF parsing, semantic chunking, question generation, and model evaluation. As a case study, we generate more than 16,000 MCQs from 22,000 open-access articles in radiation and cancer biology. We then evaluate a suite of small language models (1.1B-14B parameters) on these questions, comparing baseline accuracy with retrieval-augmented generation (RAG) from paper-derived semantic chunks and from reasoning traces distilled from GPT-4.1. We find that reasoning-trace retrieval consistently improves performance on both synthetic and expert-annotated benchmarks, enabling several small models to surpass GPT-4 on the 2023 Astro Radiation and Cancer Biology exam.

[Arxiv](https://arxiv.org/abs/2509.10744)