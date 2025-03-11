# KSOD: 为大型语言模型按需补充知识

发布时间：2025年03月10日

`LLM理论` `知识补充`

> KSOD: Knowledge Supplement for LLMs On Demand

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出了卓越的能力，但在特定领域任务中仍难免出现错误。为了进一步提升其性能，我们提出了KSOD（大型语言模型按需知识补充框架），这是一种通过基于知识的监督微调（SFT）来增强LLMs能力的创新框架。KSOD从知识缺失的角度深入分析错误成因，识别出可能导致错误的潜在知识缺口。随后，KSOD在知识数据集上微调知识模块，并据此验证LLMs是否缺乏已识别的关键知识。一旦验证通过，KSOD将利用知识模块向LLMs补充这些关键知识。与基于特定任务的微调不同，KSOD通过基于特定知识的微调实现了任务与知识的解耦。我们在两个领域特定基准和四个通用基准上的实验证明，KSOD不仅显著提升了需要补充知识的任务性能，同时保持了LLMs在其他任务上的原有水平。我们的研究发现为通过基于知识的SFT提升LLMs的能力提供了新的视角。


> Large Language Models (LLMs) have demonstrated remarkable capabilities in various tasks, yet still produce errors in domain-specific tasks. To further improve their performance, we propose KSOD (Knowledge Supplement for LLMs On Demand), a novel framework that empowers LLMs to improve their capabilities with knowledge-based supervised fine-tuning (SFT). KSOD analyzes the causes of errors from the perspective of knowledge deficiency by identifying potential missing knowledge in LLM that may lead to the errors. Subsequently, KSOD tunes a knowledge module on knowledge dataset and verifies whether the LLM lacks the identified knowledge based on it. If the knowledge is verified, KSOD supplements the LLM with the identified knowledge using the knowledge module. Tuning LLMs on specific knowledge instead of specific task decouples task and knowledge and our experiments on two domain-specific benchmarks and four general benchmarks empirically demonstrate that KSOD enhances the performance of LLMs on tasks requiring the supplemented knowledge while preserving their performance on other tasks. Our findings shed light on the potential of improving the capabilities of LLMs with knowledge-based SFT.

[Arxiv](https://arxiv.org/abs/2503.07550)