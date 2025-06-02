# 别只依赖 MLLM：开放世界智能体的稳健高效规划

发布时间：2025年05月29日

`Agent` `自主代理` `规划系统`

> Don't Just Follow MLLM Plans: Robust and Efficient Planning for Open-world Agents

# 摘要

> 开发能够在不可预测且交互式的环境中掌握复杂多步骤任务的自主代理是一项重大挑战。尽管大型语言模型（LLMs）在规划方面展现出潜力，但现有方法往往依赖有问题的内部知识或做出不切实际的环境假设。近期研究虽探索了学习规划知识，但受限于对外部知识的依赖或不切实际的设置，仍存在局限性。实际上，先前研究大多忽视了开发能够从零开始、直接在现实环境中获取规划知识的代理。实现这一能力虽然必要，却面临巨大挑战，尤其是在LLMs不准确知识的高风险下实现鲁棒性。此外，效率对于实用性至关重要，因为学习可能需要高昂的探索成本。为此，我们引入了面向开放世界代理的稳健高效规划框架（REPOA），旨在解决这些问题。REPOA包含三个关键组件：自适应依赖学习和细粒度故障感知操作记忆，以增强对知识不准确性的鲁棒性；以及基于难度的探索，以提升学习效率。我们在两个 established open-world testbeds 中进行的评估展示了 REPOA 在稳健和高效规划方面的优势，凸显了其成功获取先前方法无法企及的具有挑战性的后期游戏物品的能力。

> Developing autonomous agents capable of mastering complex, multi-step tasks in unpredictable, interactive environments presents a significant challenge. While Large Language Models (LLMs) offer promise for planning, existing approaches often rely on problematic internal knowledge or make unrealistic environmental assumptions. Although recent work explores learning planning knowledge, they still retain limitations due to partial reliance on external knowledge or impractical setups. Indeed, prior research has largely overlooked developing agents capable of acquiring planning knowledge from scratch, directly in realistic settings. While realizing this capability is necessary, it presents significant challenges, primarily achieving robustness given the substantial risk of incorporating LLMs' inaccurate knowledge. Moreover, efficiency is crucial for practicality as learning can demand prohibitive exploration. In response, we introduce Robust and Efficient Planning for Open-world Agents (REPOA), a novel framework designed to tackle these issues. REPOA features three key components: adaptive dependency learning and fine-grained failure-aware operation memory to enhance robustness to knowledge inaccuracies, and difficulty-based exploration to improve learning efficiency. Our evaluation in two established open-world testbeds demonstrates REPOA's robust and efficient planning, showcasing its capability to successfully obtain challenging late-game items that were beyond the reach of prior approaches.

[Arxiv](https://arxiv.org/abs/2505.24157)