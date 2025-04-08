# RLDBF：强化学习助力提升大型语言模型，融入数据库反馈机制

发布时间：2025年03月28日

`LLM应用` `结构化科学数据`

> RLDBF: Enhancing LLMs Via Reinforcement Learning With DataBase FeedBack

# 摘要

> 当前大型语言模型 (LLMs) 虽然在无结构文本上展现出了强大的语言能力，但对蕴含数百年科学积累的结构化科学数据（如化学分子属性）的应用仍显不足。这些结构化数据对科学领域的人工智能发展至关重要，但现有研究仅将其作为辅助工具。本研究以化学分子科学为实验平台，首次系统性地探索了如何将结构化科学数据融入 LLMs。我们分析了在持续预训练、监督微调和强化学习等不同训练阶段中引入分子属性数据对 LLM 的影响。为解决大型模型对数值数据不敏感的固有局限，我们提出了一种创新方法——“基于数据库反馈的强化学习”（RLDBF）。实验结果表明，该方法显著提升了模型在全新数据和其他化学任务上的表现，证实了其在提升 LLMs 处理结构化科学数据能力方面的潜力。

> While current large language models (LLMs) demonstrate remarkable linguistic capabilities through training on massive unstructured text corpora, they remain inadequate in leveraging structured scientific data (e.g., chemical molecular properties in databases) that encapsulate centuries of accumulated scientific expertise. These structured datasets hold strategic significance for advancing AI for Science yet current approaches merely treat them as auxiliary supplements to unstructured text. This study pioneers a systematic investigation into enhancing LLMs with structured scientific data, using chemical molecular science as a testbed. We investigate the impact of incorporating molecular property data on LLM across distinct training phases, including continual pre-training, supervised fine-tuning, and reinforcement learning. Notably, to address the inherent limitation of numerical insensitivity in large models, we propose an innovative methodology termed "Reinforcement Learning with Database Feedback" (RLDBF). Experimental evaluations demonstrate the efficacy of the proposed approach, with the model exhibiting remarkable generalization capabilities on previously unseen data and other chemical tasks. The results substantiate the potential of our method in advancing the field of structured scientific data processing within LLMs.

[Arxiv](https://arxiv.org/abs/2504.03713)