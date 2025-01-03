# 大型语言模型预训练中的遗忘现象探索

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在预训练过程中的灾难性遗忘问题，并提出了新的指标和方法来检测和缓解这一问题。这属于对LLM内部机制和理论的研究，因此归类为“LLM理论”。` `机器学习`

> Exploring Forgetting in Large Language Model Pre-Training

# 摘要

> 灾难性遗忘一直是LLMs构建全能模型的一大挑战。尽管任务级遗忘在微调中已有研究，但预训练中的遗忘却鲜有关注。我们系统研究了预训练中遗忘的存在与测量，质疑了困惑度（PPL）等传统指标，并引入新指标以更好地检测实体记忆保留。基于对遗忘指标的重新评估，我们探索了低成本、简单的方法来缓解预训练中的遗忘。此外，通过分析学习曲线，我们深入了解了遗忘的动态。对预训练遗忘的广泛评估与分析，将为未来LLMs研究提供有力支持。

> Catastrophic forgetting remains a formidable obstacle to building an omniscient model in large language models (LLMs). Despite the pioneering research on task-level forgetting in LLM fine-tuning, there is scant focus on forgetting during pre-training. We systematically explored the existence and measurement of forgetting in pre-training, questioning traditional metrics such as perplexity (PPL) and introducing new metrics to better detect entity memory retention. Based on our revised assessment of forgetting metrics, we explored low-cost, straightforward methods to mitigate forgetting during the pre-training phase. Further, we carefully analyzed the learning curves, offering insights into the dynamics of forgetting. Extensive evaluations and analyses on forgetting of pre-training could facilitate future research on LLMs.

[Arxiv](https://arxiv.org/abs/2410.17018)