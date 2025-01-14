# TimeLogic: 视频问答的时间逻辑基准

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了时间逻辑理解在视频问答（VideoQA）任务中的应用，并提出了一个自动生成问答对的框架（TLQA）来评估模型的时间逻辑推理能力。虽然论文中提到了视觉语言模型，但其核心关注点是如何利用这些模型来处理和理解视频中的时间逻辑关系，并将其应用于具体的任务（VideoQA）。因此，这篇论文属于LLM应用类别。` `视频分析` `问答系统`

> TimeLogic: A Temporal Logic Benchmark for Video QA

# 摘要

> # 时间逻辑理解
时间逻辑理解是人类认知的核心，尤其在捕捉视频中复杂事件序列及其时间关系时至关重要。这种能力在视频问答（VideoQA）任务中尤为重要，其目标是通过处理随时间变化的视觉和文本数据来提供连贯的答案。然而，由于时间逻辑标注的复杂性，当前的VideoQA基准测试很少关注这一关键技能的评估。尽管视觉语言模型取得了显著进展，但由于缺乏需要复杂时间推理的问答对，评估其时间逻辑推理能力仍然具有挑战性。为此，我们提出了TimeLogic QA（TLQA）框架，自动生成专门用于评估时间逻辑理解的问答对。TLQA利用现有视频数据集的时间标注和逻辑理论中的时间操作符，构建测试事件序列及其时间关系理解的问题。该框架具有通用性和可扩展性，能够利用带有时间动作分割标注或时间场景图标注的视频数据集，自动生成时间逻辑问题。我们基于STAR、Breakfast、AGQA和CrossTask四个数据集，生成了小型（TLQA-S）和大型（TLQA-L）两个VideoQA数据集变体，每个类别分别包含2k和10k个问答对，每个数据集总共生成32k和160k对。我们使用TLQA对领先的VideoQA模型进行了全面评估，测试其在16个不同时间复杂性类别上的时间逻辑推理能力。

> Temporal logical understanding, a core facet of human cognition, plays a pivotal role in capturing complex sequential events and their temporal relationships within videos. This capability is particularly crucial in tasks like Video Question Answering (VideoQA), where the goal is to process visual data over time together with textual data to provide coherent answers. However, current VideoQA benchmarks devote little focus to evaluating this critical skill due to the challenge of annotating temporal logic. Despite the advancement of vision-language models, assessing their temporal logical reasoning powers remains a challenge, primarily due to the lack QA pairs that demand formal, complex temporal reasoning. To bridge this gap, we introduce the TimeLogic QA (TLQA) framework to automatically generate the QA pairs, specifically designed to evaluate the temporal logical understanding. To this end, TLQA leverages temporal annotations from existing video datasets together with temporal operators derived from logic theory to construct questions that test understanding of event sequences and their temporal relationships. TLQA framework is generic and scalable, capable of leveraging both, existing video action datasets with temporal action segmentation annotations, or video datasets with temporal scene graph annotations, to automatically generate temporal logical questions. We leverage 4 datasets, STAR, Breakfast, AGQA, and CrossTask, and generate two VideoQA dataset variants - small (TLQA-S) and large (TLQA-L) - containing 2k and 10k QA pairs for each category, resulting in 32k and 160k total pairs per dataset. We undertake a comprehensive evaluation of leading-edge VideoQA models, employing the TLQA to benchmark their temporal logical understanding capabilities. We assess the VideoQA model's temporal reasoning performance on 16 categories of temporal logic with varying temporal complexity.

[Arxiv](https://arxiv.org/abs/2501.07214)