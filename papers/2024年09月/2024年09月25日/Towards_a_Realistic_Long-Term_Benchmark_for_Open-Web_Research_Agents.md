# 构建开放网络研究智能体的现实长期基准

发布时间：2024年09月25日

`Agent

理由：这篇论文主要讨论了LLM代理在特定任务（如金融和咨询领域的开放网络研究任务）上的表现，并评估了不同代理架构的性能。论文的核心关注点是LLM代理的设计、评估和性能，因此应归类为Agent。`

> Towards a Realistic Long-Term Benchmark for Open-Web Research Agents

# 摘要

> 我们展示了一个即将发布的基准测试的初步结果，用于评估LLM代理在经济价值的白领任务上的表现。我们评估了代理在金融和咨询领域中常见的现实世界“混乱”开放网络研究任务上的表现。通过这一工作，我们为LLM代理评估套件奠定了基础，其中良好的表现直接对应于巨大的经济和社会影响。我们构建并测试了几种代理架构，包括o1-preview、GPT-4o、Claude-3.5 Sonnet、Llama 3.1 (405b)和GPT-4o-mini。平均而言，由Claude-3.5 Sonnet和o1-preview驱动的LLM代理显著优于使用GPT-4o的代理，而基于Llama 3.1 (405b)和GPT-4o-mini的代理明显落后。在所有LLM中，具有将子任务委托给子代理能力的ReAct架构表现最佳。除了定量评估外，我们还通过检查代理的跟踪记录并反思其观察结果，对LLM代理的表现进行了定性评估。我们的评估代表了首次对代理在真实开放网络上进行具有挑战性、经济价值的分析师风格研究能力的深入评估。

> We present initial results of a forthcoming benchmark for evaluating LLM agents on white-collar tasks of economic value. We evaluate agents on real-world "messy" open-web research tasks of the type that are routine in finance and consulting. In doing so, we lay the groundwork for an LLM agent evaluation suite where good performance directly corresponds to a large economic and societal impact. We built and tested several agent architectures with o1-preview, GPT-4o, Claude-3.5 Sonnet, Llama 3.1 (405b), and GPT-4o-mini. On average, LLM agents powered by Claude-3.5 Sonnet and o1-preview substantially outperformed agents using GPT-4o, with agents based on Llama 3.1 (405b) and GPT-4o-mini lagging noticeably behind. Across LLMs, a ReAct architecture with the ability to delegate subtasks to subagents performed best. In addition to quantitative evaluations, we qualitatively assessed the performance of the LLM agents by inspecting their traces and reflecting on their observations. Our evaluation represents the first in-depth assessment of agents' abilities to conduct challenging, economically valuable analyst-style research on the real open web.

[Arxiv](https://arxiv.org/abs/2409.14913)