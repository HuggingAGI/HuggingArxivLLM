# Kanana: 高效计算的双语语言模型

发布时间：2025年02月26日

`LLM应用` `语言模型`

> Kanana: Compute-efficient Bilingual Language Models

# 摘要

> 我们很高兴向大家介绍 Kanana，一系列双语语言模型，其在韩语中表现卓越，并在英语中展现出极具竞争力的性能。Kanana 的计算成本显著低于同规模的最先进模型。本报告详细介绍了预训练过程中采用的技术，以实现计算高效且竞争力强的模型，包括高质量数据筛选、分阶段预训练、深度扩展以及剪枝和蒸馏。此外，报告还概述了 Kanana 模型后训练中运用的方法，涵盖监督微调和偏好优化，旨在提升与用户无缝交互的能力。最后，报告详细阐述了用于特定场景下语言模型适配的可行方法，如嵌入、检索增强生成以及功能调用。Kanana 模型系列的参数范围从 2.1B 到 32.5B，其中 2.1B 参数的模型（包括基础版、指令版和嵌入版）已公开发布，以推动韩语语言模型的研究。

> We introduce Kanana, a series of bilingual language models that demonstrate exceeding performance in Korean and competitive performance in English. The computational cost of Kanana is significantly lower than that of state-of-the-art models of similar size. The report details the techniques employed during pre-training to achieve compute-efficient yet competitive models, including high quality data filtering, staged pre-training, depth up-scaling, and pruning and distillation. Furthermore, the report outlines the methodologies utilized during the post-training of the Kanana models, encompassing supervised fine-tuning and preference optimization, aimed at enhancing their capability for seamless interaction with users. Lastly, the report elaborates on plausible approaches used for language model adaptation to specific scenarios, such as embedding, retrieval augmented generation, and function calling. The Kanana model series spans from 2.1B to 32.5B parameters with 2.1B models (base, instruct, embedding) publicly released to promote research on Korean language models.

[Arxiv](https://arxiv.org/abs/2502.18934)