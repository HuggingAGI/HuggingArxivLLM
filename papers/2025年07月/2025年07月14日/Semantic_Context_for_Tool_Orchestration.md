# # 工具编排中的语义上下文

发布时间：2025年07月14日

`Agent` `自动化` `人工智能`

> Semantic Context for Tool Orchestration

# 摘要

> 本研究证明，语义上下文（SC）借助工具描述信息，是实现稳健工具编排的核心要素。我们的工作主要贡献如下：首先，我们基于上下文多臂老虎机模型构建了理论框架，提出了SC-LinUCB算法，并证明其在动态动作空间中具有更低的遗憾值和良好的适应性。其次，我们通过大型语言模型进行了并行实证研究，结果表明SC在静态环境（高效学习）和非平稳环境（稳健适应）下，对于实现成功的上下文学习至关重要。最后，我们提出了FiReAct管道，并在一个包含超过10,000种工具的基准测试中证明，基于SC的检索机制能够使大型语言模型有效应对大规模动作空间的编排任务。这些研究成果为构建更高效、适应性强且可扩展的编排代理提供了全面的指导。

> This paper demonstrates that Semantic Context (SC), leveraging descriptive tool information, is a foundational component for robust tool orchestration. Our contributions are threefold. First, we provide a theoretical foundation using contextual bandits, introducing SC-LinUCB and proving it achieves lower regret and adapts favourably in dynamic action spaces. Second, we provide parallel empirical validation with Large Language Models, showing that SC is critical for successful in-context learning in both static (efficient learning) and non-stationary (robust adaptation) settings. Third, we propose the FiReAct pipeline, and demonstrate on a benchmark with over 10,000 tools that SC-based retrieval enables an LLM to effectively orchestrate over a large action space. These findings provide a comprehensive guide to building more sample-efficient, adaptive, and scalable orchestration agents.

[Arxiv](https://arxiv.org/abs/2507.10820)