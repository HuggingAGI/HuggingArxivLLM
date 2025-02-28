# LLM驱动的有效知识追踪：整合双通道难度实现精准追踪

发布时间：2025年02月27日

`LLM应用` `智能辅导系统`

> LLM-driven Effective Knowledge Tracing by Integrating Dual-channel Difficulty

# 摘要

> 知识追踪（KT）是智能辅导系统的核心技术，用于模拟学生学习过程中的知识状态变化、追踪个性化知识掌握情况以及预测学习表现。然而，当前的知识追踪模型面临三大挑战：（1）在遇到新问题时，由于交互记录稀疏，模型会面临冷启动问题，难以进行精准建模；（2）传统模型仅利用历史交互记录进行学生个性化建模，无法准确追踪个体掌握水平，导致个性化建模不清晰；（3）模型的决策过程对教育者而言是不透明的，使得他们难以理解模型的判断依据。

为了解决这些挑战，我们提出了一种新型的双通道难度感知知识追踪（DDKT）框架。该框架结合大型语言模型（LLMs）和检索增强生成（RAG）进行主观难度评估，并融合难度偏见感知算法和学生掌握算法，实现精准难度测量。我们的框架带来了三项关键创新：（1）难度平衡感知序列（DBPS）——结合学生的主观感知和客观难度，通过注意力机制衡量大型语言模型评估难度、数学统计难度以及学生主观感知难度之间的差距；（2）难度掌握比率（DMR）——通过不同难度区域实现对学生掌握水平的精准建模；（3）知识状态更新机制——通过门控网络实现个性化知识获取，并更新学生知识状态。

在两个真实数据集上的实验结果表明，我们的方法在九种基线模型中表现最优，AUC指标提升了2%至10%，同时有效解决了冷启动问题并增强了模型的可解释性。

> Knowledge Tracing (KT) is a fundamental technology in intelligent tutoring systems used to simulate changes in students' knowledge state during learning, track personalized knowledge mastery, and predict performance. However, current KT models face three major challenges: (1) When encountering new questions, models face cold-start problems due to sparse interaction records, making precise modeling difficult; (2) Traditional models only use historical interaction records for student personalization modeling, unable to accurately track individual mastery levels, resulting in unclear personalized modeling; (3) The decision-making process is opaque to educators, making it challenging for them to understand model judgments. To address these challenges, we propose a novel Dual-channel Difficulty-aware Knowledge Tracing (DDKT) framework that utilizes Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) for subjective difficulty assessment, while integrating difficulty bias-aware algorithms and student mastery algorithms for precise difficulty measurement. Our framework introduces three key innovations: (1) Difficulty Balance Perception Sequence (DBPS) - students' subjective perceptions combined with objective difficulty, measuring gaps between LLM-assessed difficulty, mathematical-statistical difficulty, and students' subjective perceived difficulty through attention mechanisms; (2) Difficulty Mastery Ratio (DMR) - precise modeling of student mastery levels through different difficulty zones; (3) Knowledge State Update Mechanism - implementing personalized knowledge acquisition through gated networks and updating student knowledge state. Experimental results on two real datasets show our method consistently outperforms nine baseline models, improving AUC metrics by 2% to 10% while effectively addressing cold-start problems and enhancing model interpretability.

[Arxiv](https://arxiv.org/abs/2502.19915)