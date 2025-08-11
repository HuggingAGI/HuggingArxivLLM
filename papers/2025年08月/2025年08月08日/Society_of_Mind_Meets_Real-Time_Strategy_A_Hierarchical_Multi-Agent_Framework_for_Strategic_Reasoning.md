# #心灵社会与实时战略的交汇：一种面向战略推理的层次化多智能体框架

发布时间：2025年08月08日

`LLM应用` `人工智能`

> Society of Mind Meets Real-Time Strategy: A Hierarchical Multi-Agent Framework for Strategic Reasoning

# 摘要

> 大型语言模型（LLMs）在行动序列预测方面表现优异，但在实时战略游戏等复杂任务中仍面临挑战。以《星际争霸II》（SC2）为例，智能体需在部分可观察的环境中应对资源限制和动态战场局势，这对现有LLM方法构成考验。为此，我们提出了HIMA（分层模仿多智能体）框架，该框架采用“战略规划器”（SP）元控制器协调多个专门模仿学习智能体。每个智能体通过专家演示学习独特策略（如空中支援或防御机动），并生成连贯的多步行动序列。战略规划器将这些提案整合为一个环境自适应的计划，确保局部决策与长期战略一致。我们还推出了TEXTSCII-ALL，一个涵盖SC2所有种族对抗组合的测试平台。实验结果表明，HIMA在战略清晰度、适应性和计算效率方面超越现有最优方法，展现了结合专门模仿模块与元级别编排开发更强大通用AI的潜力。

> Large Language Models (LLMs) have recently demonstrated impressive action sequence prediction capabilities but often struggle with dynamic, long-horizon tasks such as real-time strategic games. In a game such as StarCraftII (SC2), agents need to manage resource constraints and adapt to evolving battlefield situations in a partially observable environment. This often overwhelms exisiting LLM-based approaches. To address these challenges, we propose a hierarchical multi-agent framework that employs specialized imitation learning agents under a meta-controller called Strategic Planner (SP). By expert demonstrations, each specialized agent learns a distinctive strategy, such as aerial support or defensive maneuvers, and produces coherent, structured multistep action sequences. The SP then orchestrates these proposals into a single, environmentally adaptive plan that ensures local decisions aligning with long-term strategies. We call this HIMA (Hierarchical Imitation Multi-Agent). We also present TEXTSCII-ALL, a comprehensive SC2 testbed that encompasses all race match combinations in SC2. Our empirical results show that HIMA outperforms state of the arts in strategic clarity, adaptability, and computational efficiency, underscoring the potential of combining specialized imitation modules with meta-level orchestration to develop more robust, general-purpose AI agents.

[Arxiv](https://arxiv.org/abs/2508.06042)