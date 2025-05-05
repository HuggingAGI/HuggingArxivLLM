# UrbanPlanBench：全面的城市规划基准测试，用于评估大型语言模型

发布时间：2025年04月23日

`LLM应用` `城市规划` `城市设计`

> UrbanPlanBench: A Comprehensive Urban Planning Benchmark for Evaluating Large Language Models

# 摘要

> # 摘要
大型语言模型（LLMs）的出现有望彻底改变多个传统上依赖人类专业知识的领域。城市规划作为一门从根本上塑造我们日常环境的专业学科，正是这样一个高度依赖多方面专业知识和人类专家经验的领域。然而，LLMs在城市规划领域能够提供多大程度的帮助，目前仍是一个未充分探索的领域。

在本文中，我们引入了一个全面的基准测试——UrbanPlanBench，专门用于评估LLMs在城市规划中的有效性。该基准测试涵盖基本原则、专业知识以及管理和法规，与对人类规划师的要求紧密契合。通过广泛评估，我们揭示了LLMs在获取规划知识方面的显著不平衡，即使是表现最佳的模型也未能达到专业标准。例如，我们发现70%的LLMs模型在理解规划法规方面的表现逊于其他方面。

除了基准测试，我们还推出了有史以来规模最大的监督微调（SFT）数据集UrbanPlanText，该数据集包含超过30,000个指令对，源自城市规划考试和教科书。我们的研究结果表明，经过微调的模型在记忆测试和理解城市规划知识方面表现出色，但在需要领域特定术语和推理的任务中仍存在显著提升空间。

通过在https://github.com/tsinghua-fib-lab/PlanBench公开我们的基准测试、数据集及相关评估和微调工具集，我们旨在推动LLMs在实际城市规划中的应用，促进人类专业知识与机器智能的协同合作。


> The advent of Large Language Models (LLMs) holds promise for revolutionizing various fields traditionally dominated by human expertise. Urban planning, a professional discipline that fundamentally shapes our daily surroundings, is one such field heavily relying on multifaceted domain knowledge and experience of human experts. The extent to which LLMs can assist human practitioners in urban planning remains largely unexplored. In this paper, we introduce a comprehensive benchmark, UrbanPlanBench, tailored to evaluate the efficacy of LLMs in urban planning, which encompasses fundamental principles, professional knowledge, and management and regulations, aligning closely with the qualifications expected of human planners. Through extensive evaluation, we reveal a significant imbalance in the acquisition of planning knowledge among LLMs, with even the most proficient models falling short of meeting professional standards. For instance, we observe that 70% of LLMs achieve subpar performance in understanding planning regulations compared to other aspects. Besides the benchmark, we present the largest-ever supervised fine-tuning (SFT) dataset, UrbanPlanText, comprising over 30,000 instruction pairs sourced from urban planning exams and textbooks. Our findings demonstrate that fine-tuned models exhibit enhanced performance in memorization tests and comprehension of urban planning knowledge, while there exists significant room for improvement, particularly in tasks requiring domain-specific terminology and reasoning. By making our benchmark, dataset, and associated evaluation and fine-tuning toolsets publicly available at https://github.com/tsinghua-fib-lab/PlanBench, we aim to catalyze the integration of LLMs into practical urban planning, fostering a symbiotic collaboration between human expertise and machine intelligence.

[Arxiv](https://arxiv.org/abs/2504.21027)