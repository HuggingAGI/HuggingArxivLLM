# DuetUI：人机协同生成面向任务界面的双向上下文循环机制

发布时间：2025年09月16日

`LLM应用` `基础理论`

> DuetUI: A Bidirectional Context Loop for Human-Agent Co-Generation of Task-Oriented Interfaces

# 摘要

> 大型语言模型虽在重塑任务自动化，却在复杂多步骤的现实任务中仍有局限——这类任务往往需要贴合模糊的用户意图，并支持用户动态干预。我们对12名参与者开展了形成性研究，结果发现终端用户并非依赖一次性输出，而是主动寻求塑造生成式界面。为此，我们提出了人机协同生成范式，并在DuetUI系统中落地实践。这个由LLM驱动的系统通过双向上下文循环随任务推进逐步展开：智能体通过分解任务搭建界面，而用户的直接操作则会隐式引导智能体的下一步生成。在24名参与者的用户研究中，DuetUI相较基线系统显著提升了任务效率与界面可用性，实现了无缝的人机协作。我们的贡献包括：提出并验证了这一新颖范式；设计了体现该范式的DuetUI原型；以及揭示了这种双向循环如何更好地让智能体与人类意图对齐的实证见解。

> Large Language Models are reshaping task automation, yet remain limited in complex, multi-step real-world tasks that require aligning with vague user intent and enabling dynamic user override. From a formative study with 12 participants, we found that end-users actively seek to shape generative interfaces rather than relying on one-shot outputs. To address this, we introduce the human-agent co-generation paradigm, materialized in DuetUI. This LLM-empowered system unfolds alongside task progress through a bidirectional context loop--the agent scaffolds the interface by decomposing the task, while the user's direct manipulations implicitly steer the agent's next generation step. In a user study with 24 participants, DuetUI significantly improved task efficiency and interface usability compared to a baseline, fostering seamless human-agent collaboration. Our contributions include the proposal and validation of this novel paradigm, the design of the DuetUI prototype embodying it, and empirical insights into how this bidirectional loop better aligns agents with human intent.

[Arxiv](https://arxiv.org/abs/2509.13444)