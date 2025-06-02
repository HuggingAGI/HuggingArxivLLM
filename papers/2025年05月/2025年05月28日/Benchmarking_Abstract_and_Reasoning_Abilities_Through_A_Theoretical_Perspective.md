# # 从理论视角评估抽象与推理能力

发布时间：2025年05月28日

`LLM理论

摘要中探讨了大型语言模型的抽象推理能力，提出了新的评估指标和基准，属于对LLM理论的深入分析。` `人工智能` `认知科学`

> Benchmarking Abstract and Reasoning Abilities Through A Theoretical Perspective

# 摘要

> 本文旨在建立一个简单、有效且有理论依据的基准，以深入探查大型语言模型（LLMs）的抽象推理能力。为此，我们首先构建了一个数学框架，将抽象推理定义为：(i) 提取独立于表面表示的关键模式，以及 (ii) 将一致的规则应用于这些抽象模式的能力。基于此框架，我们引入了两个新颖的互补指标：\(\scoreGamma\) 衡量基本推理准确性，而 \(\scoreDelta\) 量化模型对特定符号而非潜在模式的依赖程度，这是区分真正抽象与单纯记忆的关键指标。我们设计了一个基准：在基于规则的任务中进行系统性符号重映射，迫使模型展示超越表层符号匹配的真实模式识别能力。通过使用这个基准对大量 LLM 进行评估（包括商业 API 模型，从 7B 到 70B 规模，以及多智能体模型），我们揭示了以下发现：1) 在非十进制算术和符号推理方面存在关键限制；2) 即使采用链式思维提示，仍然存在持续的抽象差距；3) \(\scoreDelta\) 在通过量化符号重映射下的性能退化来稳健衡量记忆依赖方面的有效性，特别是突出了对特定操作数的记忆依赖。这些发现强调了当前 LLMs 尽管在特定领域表现出色，但在稳健抽象推理方面仍存在不足，突显了未来改进的关键方向。

> In this paper, we aim to establish a simple, effective, and theoretically grounded benchmark for rigorously probing abstract reasoning in Large Language Models (LLMs). To achieve this, we first develop a mathematic framework that defines abstract reasoning as the ability to: (i) extract essential patterns independent of surface representations, and (ii) apply consistent rules to these abstract patterns. Based on this framework, we introduce two novel complementary metrics: \(\scoreGamma\) measures basic reasoning accuracy, while \(\scoreDelta\) quantifies a model's reliance on specific symbols rather than underlying patterns - a key indicator of true abstraction versus mere memorization. To implement this measurement, we design a benchmark: systematic symbol remapping in rule-based tasks, which forces models to demonstrate genuine pattern recognition beyond superficial token matching. Extensive LLM evaluations using this benchmark (commercial API models, 7B-70B, multi-agent) reveal:1) critical limitations in non-decimal arithmetic and symbolic reasoning; 2) persistent abstraction gaps despite chain-of-thought prompting; and 3) \(\scoreDelta\)'s effectiveness in robustly measuring memory dependence by quantifying performance degradation under symbol remapping, particularly highlighting operand-specific memorization. These findings underscore that current LLMs, despite domain-specific strengths, still lack robust abstract reasoning, highlighting key areas for future improvement.

[Arxiv](https://arxiv.org/abs/2505.23833)