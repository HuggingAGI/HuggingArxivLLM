# DS@GT 在 CheckThat! 2025 中：探索社交媒体话语中科学声明来源的检索与重排序流水线。

发布时间：2025年07月09日

`LLM应用` `社交媒体` `科学信息验证`

> DS@GT at CheckThat! 2025: Exploring Retrieval and Reranking Pipelines for Scientific Claim Source Retrieval on Social Media Discourse

# 摘要

> 社交媒体用户常发表科学声明却未注明来源，这促使我们有必要验证这些声明。本文介绍DS@GT团队在CLEF 2025 CheckThat! Lab Task 4b中的工作，该任务旨在根据推文中的隐含引用找到相关科学论文。我们探索了6种数据增强技术、7种检索与重排序管道，并微调了双编码器。在MRR@5指标上，我们达到了0.58，在30支队伍中排名第16，比BM25基线提升了0.15。代码已开源：https://github.com/dsgt-arc/checkthat-2025-swd/tree/main/subtask-4b。

> Social media users often make scientific claims without citing where these claims come from, generating a need to verify these claims. This paper details work done by the DS@GT team for CLEF 2025 CheckThat! Lab Task 4b Scientific Claim Source Retrieval which seeks to find relevant scientific papers based on implicit references in tweets. Our team explored 6 different data augmentation techniques, 7 different retrieval and reranking pipelines, and finetuned a bi-encoder. Achieving an MRR@5 of 0.58, our team ranked 16th out of 30 teams for the CLEF 2025 CheckThat! Lab Task 4b, and improvement of 0.15 over the BM25 baseline of 0.43. Our code is available on Github at https://github.com/dsgt-arc/checkthat-2025-swd/tree/main/subtask-4b.

[Arxiv](https://arxiv.org/abs/2507.06563)