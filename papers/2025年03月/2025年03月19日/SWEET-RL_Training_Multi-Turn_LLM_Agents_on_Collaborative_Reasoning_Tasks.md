# SWEET-RL：针对协作推理任务训练多轮LLM智能体

发布时间：2025年03月19日

`LLM应用` `软件开发` `协作内容创作`

> SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks

# 摘要

> 在现实任务中，大型语言模型（LLM）代理需要进行多轮交互，但现有的多轮强化学习算法在优化LLM代理时，难以有效分配多轮信用，同时利用LLM的泛化能力，开发此类算法仍是一个难题。为研究这一问题，我们引入了一个新的基准测试ColBench，在此基准中，LLM代理与人类合作者进行多轮交互，共同解决后端编程和前端设计中的现实任务。基于此，我们提出了一种新型的强化学习算法SWEET-RL（基于训练时间信息的逐步评估强化学习），该算法通过精心设计的优化目标，训练一个能够访问额外训练时间信息的批评模型。该批评模型为改进策略模型提供分步奖励。实验结果表明，与现有的其他先进多轮强化学习算法相比，SWEET-RL在ColBench上的成功率和胜率实现了6%的绝对提升，使Llama-3.1-8B能够达到或超越GPT4-o在现实协作内容创作中的性能。

> Large language model (LLM) agents need to perform multi-turn interactions in real-world tasks. However, existing multi-turn RL algorithms for optimizing LLM agents fail to perform effective credit assignment over multiple turns while leveraging the generalization capabilities of LLMs and it remains unclear how to develop such algorithms. To study this, we first introduce a new benchmark, ColBench, where an LLM agent interacts with a human collaborator over multiple turns to solve realistic tasks in backend programming and frontend design. Building on this benchmark, we propose a novel RL algorithm, SWEET-RL (RL with Step-WisE Evaluation from Training-time information), that uses a carefully designed optimization objective to train a critic model with access to additional training-time information. The critic provides step-level rewards for improving the policy model. Our experiments demonstrate that SWEET-RL achieves a 6% absolute improvement in success and win rates on ColBench compared to other state-of-the-art multi-turn RL algorithms, enabling Llama-3.1-8B to match or exceed the performance of GPT4-o in realistic collaborative content creation.

[Arxiv](https://arxiv.org/abs/2503.15478)