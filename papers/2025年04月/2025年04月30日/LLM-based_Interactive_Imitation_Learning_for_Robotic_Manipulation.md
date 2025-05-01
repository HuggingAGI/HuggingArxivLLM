# # 基于LLM的交互模仿学习助力机器人操作

发布时间：2025年04月30日

`Agent

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）作为交互式教师来提升智能体的性能，特别是在机器人操作任务中。它提出了一种新的交互式模仿学习框架，并通过实验验证了其有效性。因此，这篇论文主要关注智能体的学习和控制方法，属于Agent类别。` `机器人` `人工智能`

> LLM-based Interactive Imitation Learning for Robotic Manipulation

# 摘要

> 机器学习的最新进展为应对机器人领域日益复杂的序列决策问题提供了训练自主智能体的方法。模仿学习（IL）是一种主要方法，通过人类演示让智能体学习控制机器人。然而，IL在机器人任务中常会违反独立同分布（i.i.d）假设。交互式模仿学习（IIL）通过让智能体从人类教师的交互式反馈中学习，实现了更好的性能。尽管有所改进，但两种方法都因需要人类参与而带来了高昂的成本。我们利用大型语言模型（LLMs）在推理和生成人类-like响应方面的新兴能力，提出了一种名为LLM-iTeach的新IIL框架。该框架利用LLM作为交互式教师，以提升智能体性能，同时减轻对人力资源的依赖。首先，LLM-iTeach采用分层提示策略，引导LLM生成Python代码形式的策略。然后，通过设计的基于相似性的反馈机制，LLM-iTeach在智能体训练过程中提供实时的纠正性与评价性反馈。我们通过多种机器人操作任务，将LLM-iTeach与基线方法（如模仿学习方法行为克隆（BC）和使用人类教师的先进IIL方法CEILing）进行了对比评估。实验结果表明，LLM-iTeach的成功率超越了BC，并达到了甚至优于CEILing的水平，这凸显了LLMs作为成本效益高且人类-like教师在交互式学习环境中的潜力。我们进一步通过额外任务验证了该方法的泛化能力。代码和提示词已开源：https://github.com/Tubicor/LLM-iTeach。
    

> Recent advancements in machine learning provide methods to train autonomous agents capable of handling the increasing complexity of sequential decision-making in robotics. Imitation Learning (IL) is a prominent approach, where agents learn to control robots based on human demonstrations. However, IL commonly suffers from violating the independent and identically distributed (i.i.d) assumption in robotic tasks. Interactive Imitation Learning (IIL) achieves improved performance by allowing agents to learn from interactive feedback from human teachers. Despite these improvements, both approaches come with significant costs due to the necessity of human involvement. Leveraging the emergent capabilities of Large Language Models (LLMs) in reasoning and generating human-like responses, we introduce LLM-iTeach -- a novel IIL framework that utilizes an LLM as an interactive teacher to enhance agent performance while alleviating the dependence on human resources. Firstly, LLM-iTeach uses a hierarchical prompting strategy that guides the LLM in generating a policy in Python code. Then, with a designed similarity-based feedback mechanism, LLM-iTeach provides corrective and evaluative feedback interactively during the agent's training. We evaluate LLM-iTeach against baseline methods such as Behavior Cloning (BC), an IL method, and CEILing, a state-of-the-art IIL method using a human teacher, on various robotic manipulation tasks. Our results demonstrate that LLM-iTeach surpasses BC in the success rate and achieves or even outscores that of CEILing, highlighting the potential of LLMs as cost-effective, human-like teachers in interactive learning environments. We further demonstrate the method's potential for generalization by evaluating it on additional tasks. The code and prompts are provided at: https://github.com/Tubicor/LLM-iTeach.

[Arxiv](https://arxiv.org/abs/2504.21769)