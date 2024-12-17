# CG-Bench：长视频理解的线索引导式问答基准

发布时间：2024年12月16日

`LLM应用` `多模态语言模型`

> CG-Bench: Clue-grounded Question Answering Benchmark for Long Video Understanding

# 摘要

> 大多数现有的多模态大型语言模型（MLLMs）的视频理解基准都只聚焦于短视频。长视频理解的基准数量有限，且往往仅依赖多项选择题（MCQs）。然而，鉴于基于 MCQ 评估的固有局限以及 MLLMs 日益增强的推理能力，模型能够仅通过将短视频理解与排除法相结合来给出答案，而非真正理解视频内容。为填补这一空缺，我们推出了 CG-Bench，这是专为长视频中的线索问答设计的新型基准。CG-Bench 着重强调模型检索问题相关线索的能力，提升了评估的可信度。它涵盖 1219 个经人工策划的视频，通过细致的分类系统，分为 14 个主要类别、171 个次要类别和 638 个三级类别，成为长视频分析领域最大的基准。该基准包含三种主要问题类型（感知、推理和幻觉）中的 12129 个问答对。为弥补纯基于 MCQ 评估的不足，我们设计了两种新颖的基于线索的评估方法：线索接地的白盒评估和黑盒评估，以判定模型是否基于对视频的正确理解生成答案。我们在 CG-Bench 上对多个闭源和开源的 MLLMs 进行了评估。结果显示，与短视频相比，当前模型在理解长视频方面表现欠佳，开源模型和商业模型之间存在显著差距。我们期望 CG-Bench 能够推动更可靠、更强大的 MLLMs 在长视频理解方面的发展。所有注释和视频数据均在 https://cg-bench.github.io/leaderboard/ 发布。

> Most existing video understanding benchmarks for multimodal large language models (MLLMs) focus only on short videos. The limited number of benchmarks for long video understanding often rely solely on multiple-choice questions (MCQs). However, because of the inherent limitation of MCQ-based evaluation and the increasing reasoning ability of MLLMs, models can give the current answer purely by combining short video understanding with elimination, without genuinely understanding the video content. To address this gap, we introduce CG-Bench, a novel benchmark designed for clue-grounded question answering in long videos. CG-Bench emphasizes the model's ability to retrieve relevant clues for questions, enhancing evaluation credibility. It features 1,219 manually curated videos categorized by a granular system with 14 primary categories, 171 secondary categories, and 638 tertiary categories, making it the largest benchmark for long video analysis. The benchmark includes 12,129 QA pairs in three major question types: perception, reasoning, and hallucination. Compensating the drawbacks of pure MCQ-based evaluation, we design two novel clue-based evaluation methods: clue-grounded white box and black box evaluations, to assess whether the model generates answers based on the correct understanding of the video. We evaluate multiple closed-source and open-source MLLMs on CG-Bench. Results indicate that current models significantly underperform in understanding long videos compared to short ones, and a significant gap exists between open-source and commercial models. We hope CG-Bench can advance the development of more trustworthy and capable MLLMs for long video understanding. All annotations and video data are released at https://cg-bench.github.io/leaderboard/.

[Arxiv](https://arxiv.org/abs/2412.12075)