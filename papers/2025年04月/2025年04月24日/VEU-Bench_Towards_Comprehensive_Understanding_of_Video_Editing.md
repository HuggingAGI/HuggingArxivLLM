# VEU-Bench：致力于全面理解视频编辑的能力

发布时间：2025年04月24日

`LLM应用` `计算机视觉`

> VEU-Bench: Towards Comprehensive Understanding of Video Editing

# 摘要

> 互联网上广泛传播的视频大多都经过后期处理。尽管近期视频大型语言模型（Vid-LLMs）在通用视频理解任务中取得了显著进展，但它们在视频编辑理解（VEU）任务中的能力尚未得到充分探索。为填补这一研究空白，本研究提出了VEU-Bench，这是一个全面的视频编辑理解基准，涵盖了从镜头大小等帧内特征到剪辑类型和转场等帧间属性的多维度视频编辑组件分类。与以往专注于编辑元素分类的视频编辑理解基准不同，VEU-Bench涵盖了从识别、推理到判断三个阶段的19个细粒度任务。为了提升VEU的标注效率，我们构建了一个集成基于本体论知识库的标注流水线。通过与11个当前最先进的Vid-LLMs的广泛实验对比，我们发现现有Vid-LLMs在VEU任务中面临着严峻挑战，部分模型的表现甚至低于随机选择。为解决这一问题，我们开发了Oscars，这是一个基于精心筛选的VEU-Bench数据集进行微调的VEU专家模型。它在VEU-Bench上的准确率比现有开源Vid-LLMs高出28.3%以上，并且在性能上与GPT-4等商业模型相当。我们还证明，整合VEU数据显著提升了Vid-LLMs在通用视频理解基准上的表现，在9个推理任务中平均提升了8.3%的性能。

> Widely shared videos on the internet are often edited. Recently, although Video Large Language Models (Vid-LLMs) have made great progress in general video understanding tasks, their capabilities in video editing understanding (VEU) tasks remain unexplored. To address this gap, in this paper, we introduce VEU-Bench (Video Editing Understanding Benchmark), a comprehensive benchmark that categorizes video editing components across various dimensions, from intra-frame features like shot size to inter-shot attributes such as cut types and transitions. Unlike previous video editing understanding benchmarks that focus mainly on editing element classification, VEU-Bench encompasses 19 fine-grained tasks across three stages: recognition, reasoning, and judging. To enhance the annotation of VEU automatically, we built an annotation pipeline integrated with an ontology-based knowledge base. Through extensive experiments with 11 state-of-the-art Vid-LLMs, our findings reveal that current Vid-LLMs face significant challenges in VEU tasks, with some performing worse than random choice. To alleviate this issue, we develop Oscars, a VEU expert model fine-tuned on the curated VEU-Bench dataset. It outperforms existing open-source Vid-LLMs on VEU-Bench by over 28.3% in accuracy and achieves performance comparable to commercial models like GPT-4o. We also demonstrate that incorporating VEU data significantly enhances the performance of Vid-LLMs on general video understanding benchmarks, with an average improvement of 8.3% across nine reasoning tasks.

[Arxiv](https://arxiv.org/abs/2504.17828)