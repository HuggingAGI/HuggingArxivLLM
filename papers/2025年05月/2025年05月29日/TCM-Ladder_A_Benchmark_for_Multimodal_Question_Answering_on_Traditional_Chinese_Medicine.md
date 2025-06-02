# TCM阶梯：传统中医领域的多模态问答评测基准

发布时间：2025年05月29日

`LLM应用

理由：这篇论文专注于将大语言模型（LLMs）应用于中医领域，构建了一个多模态的问答数据集TCM-Ladder，并提出了评估方法Ladder-Score。其核心在于模型在具体领域的应用和评估，属于LLM应用类别。` `数据集`

> TCM-Ladder: A Benchmark for Multimodal Question Answering on Traditional Chinese Medicine

# 摘要

> 中医作为有效的替代医学，近年来受到越来越多的关注。近年来，针对中医的大语言模型（LLMs）快速发展，凸显了建立一个客观全面的评估框架来评估其在实际任务中性能的必要性。然而，现有的评估数据集范围有限，且主要基于文本，缺乏统一标准化的多模态问答（QA）基准。为了解决这一问题，我们提出了TCM-Ladder，这是首个专门针对评估中医大语言模型的多模态QA数据集。该数据集涵盖了中医的多个核心学科，包括基础理论、诊断、方剂、内科、外科、药理学和儿科。除了文本内容外，TCM-Ladder还包含了图像和视频等多种模态。该数据集通过自动化和人工筛选相结合的方式构建，总共有52000多个问题，包括单选、多选、填空、诊断对话和视觉理解等多种任务类型。我们在TCM-Ladder上训练了一个推理模型，并与9个主流通用领域和5个领先的中医领域大语言模型进行了对比实验，以评估它们在数据集上的性能。此外，我们提出了Ladder-Score，这是一种专门用于中医问答的评估方法，能够有效评估答案在术语使用和语义表达方面的质量。据我们所知，这是首个在统一多模态基准上对主流通用领域和中医领域大语言模型进行评估的工作。数据集和排行榜可在https://tcmladder.com或https://54.211.107.106上公开获取，并将持续更新。

> Traditional Chinese Medicine (TCM), as an effective alternative medicine, has been receiving increasing attention. In recent years, the rapid development of large language models (LLMs) tailored for TCM has underscored the need for an objective and comprehensive evaluation framework to assess their performance on real-world tasks. However, existing evaluation datasets are limited in scope and primarily text-based, lacking a unified and standardized multimodal question-answering (QA) benchmark. To address this issue, we introduce TCM-Ladder, the first multimodal QA dataset specifically designed for evaluating large TCM language models. The dataset spans multiple core disciplines of TCM, including fundamental theory, diagnostics, herbal formulas, internal medicine, surgery, pharmacognosy, and pediatrics. In addition to textual content, TCM-Ladder incorporates various modalities such as images and videos. The datasets were constructed using a combination of automated and manual filtering processes and comprise 52,000+ questions in total. These questions include single-choice, multiple-choice, fill-in-the-blank, diagnostic dialogue, and visual comprehension tasks. We trained a reasoning model on TCM-Ladder and conducted comparative experiments against 9 state-of-the-art general domain and 5 leading TCM-specific LLMs to evaluate their performance on the datasets. Moreover, we propose Ladder-Score, an evaluation method specifically designed for TCM question answering that effectively assesses answer quality regarding terminology usage and semantic expression. To our knowledge, this is the first work to evaluate mainstream general domain and TCM-specific LLMs on a unified multimodal benchmark. The datasets and leaderboard are publicly available at https://tcmladder.com or https://54.211.107.106 and will be continuously updated.

[Arxiv](https://arxiv.org/abs/2505.24063)