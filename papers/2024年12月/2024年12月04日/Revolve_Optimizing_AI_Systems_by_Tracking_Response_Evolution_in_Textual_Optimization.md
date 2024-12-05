# Revolve：借由跟踪文本优化中的响应演变来优化 AI 系统

发布时间：2024年12月04日

`LLM应用` `人工智能`

> Revolve: Optimizing AI Systems by Tracking Response Evolution in Textual Optimization

# 摘要

> 近期，大型语言模型（LLMs）的进步显著提升了基于 LLM 系统通过自然语言处理和工具交互执行复杂任务的能力。然而，针对特定任务优化此类基于 LLM 的系统颇具挑战，往往需要诸如提示工程和超参数调优等人工干预。现有的自动优化方法，像基于文本反馈的技术（如 TextGrad），通常聚焦于即时反馈，类似于传统数值梯度下降中的即时导数。但仅依赖这种反馈可能存在局限，当针对此反馈做出的调整过小或不规则波动时，可能会减缓甚至停滞优化进程。为应对这些挑战，需要更具适应性的方法，尤其在系统响应缓慢或不可预测演变的情况下。本文介绍了 REVOLVE 这一优化方法，它追踪 LLM 系统迭代过程中“响应的演变情况”。通过关注响应随时间的变化，REVOLVE 在每一步都进行深思熟虑、逐步的调整，从而实现更稳定、有效的优化。实验结果显示，REVOLVE 优于竞争基线，在提示优化方面提升了 7.8％，在解决方案细化方面收获了 20.72％的增益，在代码优化方面提高了 29.17％。此外，REVOLVE 收敛所需的迭代次数更少，大幅节省了计算量。这些优势彰显了其适应性和效率，使 REVOLVE 成为优化基于 LLM 系统和推动下一代人工智能技术发展的得力工具。代码获取地址：https://github.com/Peiyance/REVOLVE 。

> Recent advancements in large language models (LLMs) have significantly enhanced the ability of LLM-based systems to perform complex tasks through natural language processing and tool interaction. However, optimizing these LLM-based systems for specific tasks remains challenging, often requiring manual interventions like prompt engineering and hyperparameter tuning. Existing automatic optimization methods, such as textual feedback-based techniques (e.g., TextGrad), tend to focus on immediate feedback, analogous to using immediate derivatives in traditional numerical gradient descent. However, relying solely on such feedback can be limited when the adjustments made in response to this feedback are either too small or fluctuate irregularly, potentially slowing down or even stalling the optimization process. To overcome these challenges, more adaptive methods are needed, especially in situations where the system's response is evolving slowly or unpredictably. In this paper, we introduce REVOLVE, an optimization method that tracks how "R"esponses "EVOLVE" across iterations in LLM systems. By focusing on the evolution of responses over time, REVOLVE enables more stable and effective optimization by making thoughtful, progressive adjustments at each step. Experimental results demonstrate that REVOLVE outperforms competitive baselines, achieving a 7.8% improvement in prompt optimization, a 20.72% gain in solution refinement, and a 29.17% increase in code optimization. Additionally, REVOLVE converges in fewer iterations, resulting in significant computational savings. These advantages highlight its adaptability and efficiency, positioning REVOLVE as a valuable tool for optimizing LLM-based systems and accelerating the development of next-generation AI technologies. Code is available at: https://github.com/Peiyance/REVOLVE.

[Arxiv](https://arxiv.org/abs/2412.03092)