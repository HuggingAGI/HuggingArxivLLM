# Free-MAD：无共识多智能体辩论

发布时间：2025年09月13日

`Agent` `基础理论`

> Free-MAD: Consensus-Free Multi-Agent Debate

# 摘要

> 多智能体辩论（MAD）是提升大型语言模型（LLMs）推理能力的新兴方法。现有MAD方法通过智能体间的多轮交互达成共识，最终输出由最后一轮的多数投票决定。但这种基于共识的设计存在明显局限：一是多轮通信会增加token开销，限制可扩展性；二是由于LLM固有的从众性，最初给出正确答案的智能体可能在辩论中被错误观点带偏，导致错误传播；三是多数投票在决策时引入随机性和不公平性，还可能降低推理性能。
  为解决这些问题，我们提出	extsc{Free-MAD}——一种无需智能体达成共识的新型MAD框架。它引入了一种新颖的基于分数的决策机制，评估整个辩论轨迹而非仅依赖最后一轮。该机制追踪每个智能体的推理演变过程，从而实现更准确、公平的结果。此外，	extsc{Free-MAD}还通过引入反从众机制重构了辩论阶段，该机制能帮助智能体减轻多数方的过度影响。在八个基准数据集上的实验表明，	extsc{Free-MAD}不仅显著提升了推理性能，还只需单轮辩论，从而降低了token成本。我们还发现，与现有MAD方法相比，	extsc{Free-MAD}在真实攻击场景中表现出更强的鲁棒性。

> Multi-agent debate (MAD) is an emerging approach to improving the reasoning capabilities of large language models (LLMs). Existing MAD methods rely on multiple rounds of interaction among agents to reach consensus, and the final output is selected by majority voting in the last round. However, this consensus-based design faces several limitations. First, multiple rounds of communication increases token overhead and limits scalability. Second, due to the inherent conformity of LLMs, agents that initially produce correct responses may be influenced by incorrect ones during the debate process, causing error propagation. Third, majority voting introduces randomness and unfairness in the decision-making phase, and can degrade the reasoning performance.
  To address these issues, we propose \textsc{Free-MAD}, a novel MAD framework that eliminates the need for consensus among agents. \textsc{Free-MAD} introduces a novel score-based decision mechanism that evaluates the entire debate trajectory rather than relying on the last round only. This mechanism tracks how each agent's reasoning evolves, enabling more accurate and fair outcomes. In addition, \textsc{Free-MAD} reconstructs the debate phase by introducing anti-conformity, a mechanism that enables agents to mitigate excessive influence from the majority. Experiments on eight benchmark datasets demonstrate that \textsc{Free-MAD} significantly improves reasoning performance while requiring only a single-round debate and thus reducing token costs. We also show that compared to existing MAD approaches, \textsc{Free-MAD} exhibits improved robustness in real-world attack scenarios.

[Arxiv](https://arxiv.org/abs/2509.11035)