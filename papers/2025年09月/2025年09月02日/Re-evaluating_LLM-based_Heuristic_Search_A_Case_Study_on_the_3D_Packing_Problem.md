# 重新评估基于LLM的启发式搜索：三维装箱问题的案例研究

发布时间：2025年09月02日

`LLM应用` `交通运输`

> Re-evaluating LLM-based Heuristic Search: A Case Study on the 3D Packing Problem

# 摘要

> 启发式设计向来是人类的智慧结晶。尽管大型语言模型（LLMs）能够生成搜索启发式代码，但其应用大多局限于在人类构建的框架内调整简单函数，至于它们能否实现更广泛的创新，仍是一个未解之谜。为了探究这一问题，我们让LLM独立构建一个完整的约束3D装箱问题求解器。然而直接生成代码很快就暴露出不够稳健的问题，为此我们引入了两种辅助机制：约束脚手架——即预编写的约束检查代码——和迭代自修正——通过额外的优化迭代来修复漏洞并生成可行的初始群体。值得注意的是，即便在贪婪算法的庞大搜索空间中，LLM也几乎将所有精力都集中在优化评分函数上。这意味着，先前研究对评分函数的侧重或许并非源于某种系统性策略，而是LLM自身能力的天然局限。最终生成的启发式算法性能与人类设计的贪婪算法不相上下；若将其评分函数整合到人类构建的元启发式算法中，其表现甚至能与主流求解器比肩，不过在约束条件增强时，效果会打折扣。我们的研究揭示了当前LLMs实现自动化启发式设计的两大障碍：一是需通过工程手段弥补其在复杂推理任务中的脆弱性，二是预训练偏差的影响——这种偏差可能过早限制对创新方案的探索。

> The art of heuristic design has traditionally been a human pursuit. While Large Language Models (LLMs) can generate code for search heuristics, their application has largely been confined to adjusting simple functions within human-crafted frameworks, leaving their capacity for broader innovation an open question. To investigate this, we tasked an LLM with building a complete solver for the constrained 3D Packing Problem. Direct code generation quickly proved fragile, prompting us to introduce two supports: constraint scaffolding--prewritten constraint-checking code--and iterative self-correction--additional refinement cycles to repair bugs and produce a viable initial population. Notably, even within a vast search space in a greedy process, the LLM concentrated its efforts almost exclusively on refining the scoring function. This suggests that the emphasis on scoring functions in prior work may reflect not a principled strategy, but rather a natural limitation of LLM capabilities. The resulting heuristic was comparable to a human-designed greedy algorithm, and when its scoring function was integrated into a human-crafted metaheuristic, its performance rivaled established solvers, though its effectiveness waned as constraints tightened. Our findings highlight two major barriers to automated heuristic design with current LLMs: the engineering required to mitigate their fragility in complex reasoning tasks, and the influence of pretrained biases, which can prematurely narrow the search for novel solutions.

[Arxiv](https://arxiv.org/abs/2509.02297)