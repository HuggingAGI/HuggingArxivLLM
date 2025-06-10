# 预热搜索：利用大型语言模型通过预热树搜索指导几何任务和运动规划

发布时间：2025年06月08日

`LLM应用` `机器人学` `自动化`

> Prime the search: Using large language models for guiding geometric task and motion planning by warm-starting tree search

# 摘要

> 将物体重新定位到目标区域的问题，尤其是在存在可移动障碍物的情况下，可以建模为几何任务与运动规划（G-TAMP）问题，这是任务与运动规划（TAMP）的一个子类。传统方法主要依赖领域独立的启发式或从规划经验中学习，通常需要大量计算资源或数据。相比之下，人类在处理G-TAMP问题时，常利用常识来直观决定操作哪些物体。受此启发，我们提出利用大型语言模型（LLMs），这些模型从互联网规模的数据中获取了常识知识，来指导G-TAMP中的任务规划。为了使LLMs进行几何推理，我们设计了基于谓词的提示，将从运动规划算法中提取的几何信息编码。然后查询LLM生成任务计划，用于搜索可行的连续参数。由于LLMs容易出错，我们没有完全依赖其输出，而是将蒙特卡洛树搜索（MCTS）扩展到混合动作空间，并用LLM引导搜索。与之前在每个节点都调用LLM导致高昂计算成本的方法不同，我们利用LLM完成任务计划过程中探索的节点来预热MCTS。在六个不同的G-TAMP问题上，我们的方法优于之前的LLM规划器和纯搜索算法。代码可在以下链接找到：https://github.com/iMSquared/prime-the-search

> The problem of relocating a set of objects to designated areas amidst movable obstacles can be framed as a Geometric Task and Motion Planning (G-TAMP) problem, a subclass of task and motion planning (TAMP). Traditional approaches to G-TAMP have relied either on domain-independent heuristics or on learning from planning experience to guide the search, both of which typically demand significant computational resources or data. In contrast, humans often use common sense to intuitively decide which objects to manipulate in G-TAMP problems. Inspired by this, we propose leveraging Large Language Models (LLMs), which have common sense knowledge acquired from internet-scale data, to guide task planning in G-TAMP problems. To enable LLMs to perform geometric reasoning, we design a predicate-based prompt that encodes geometric information derived from a motion planning algorithm. We then query the LLM to generate a task plan, which is then used to search for a feasible set of continuous parameters. Since LLMs are prone to mistakes, instead of committing to LLM's outputs, we extend Monte Carlo Tree Search (MCTS) to a hybrid action space and use the LLM to guide the search. Unlike the previous approach that calls an LLM at every node and incurs high computational costs, we use it to warm-start the MCTS with the nodes explored in completing the LLM's task plan. On six different G-TAMP problems, we show our method outperforms previous LLM planners and pure search algorithms. Code can be found at: https://github.com/iMSquared/prime-the-search

[Arxiv](https://arxiv.org/abs/2506.07062)