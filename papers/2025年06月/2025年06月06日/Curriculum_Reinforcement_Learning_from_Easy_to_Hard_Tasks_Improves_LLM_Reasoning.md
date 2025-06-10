# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月06日

`LLM应用

LLM应用` `人工智能` `机器学习`

> Curriculum Reinforcement Learning from Easy to Hard Tasks Improves LLM Reasoning

# 摘要

> 我们致力于通过强化学习（RL）提升语言模型的推理能力。近期，像DeepSeek-R1这样的RL后训练模型在数学和编程任务中已展现出强大的推理能力。然而，先前研究表明，单独使用强化学习来提升推理能力在本质上困难的任务上效果有限。为此，我们从课程学习中汲取灵感，提出将任务从简单到困难（E2H）进行安排，使LLM能够逐步构建推理技能。我们的方法被称为E2H推理器。

实证研究表明，虽然简单任务在初始阶段至关重要，但通过适当安排逐步淡出这些任务对于防止过拟合至关重要。理论上，我们在近似策略迭代框架内为E2H推理器建立了收敛保证。我们推导了有限样本复杂度的界限，并证明当任务得到适当分解和条件化时，通过课程阶段的学习所需的总样本量少于直接学习。

跨多个领域的实验表明，E2H推理器显著提升了小规模LLM（1.5B到3B）的推理能力。这些模型在仅使用基础RL训练时表现挣扎，而通过E2H推理器的训练则显著提升了推理能力，这凸显了我们方法的有效性。

> We aim to improve the reasoning capabilities of language models via reinforcement learning (RL). Recent RL post-trained models like DeepSeek-R1 have demonstrated reasoning abilities on mathematical and coding tasks. However, prior studies suggest that using RL alone to improve reasoning on inherently difficult tasks is less effective. Here, we draw inspiration from curriculum learning and propose to schedule tasks from easy to hard (E2H), allowing LLMs to build reasoning skills gradually. Our method is termed E2H Reasoner. Empirically, we observe that, although easy tasks are important initially, fading them out through appropriate scheduling is essential in preventing overfitting. Theoretically, we establish convergence guarantees for E2H Reasoner within an approximate policy iteration framework. We derive finite-sample complexity bounds and show that when tasks are appropriately decomposed and conditioned, learning through curriculum stages requires fewer total samples than direct learning. Experiments across multiple domains show that E2H Reasoner significantly improves the reasoning ability of small LLMs (1.5B to 3B), which otherwise struggle when trained with vanilla RL alone, highlighting the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2506.06632)