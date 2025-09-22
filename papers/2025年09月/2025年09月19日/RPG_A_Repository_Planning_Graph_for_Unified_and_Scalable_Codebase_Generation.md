# RPG：一种面向统一与可扩展代码库生成的仓库规划图

发布时间：2025年09月19日

`LLM应用` `基础理论`

> RPG: A Repository Planning Graph for Unified and Scalable Codebase Generation

# 摘要

> 大型语言模型在函数级和文件级代码生成方面表现出色，但从头生成完整仓库仍是一项根本性挑战。这一过程需在提案级与实现级阶段进行连贯可靠的规划，而自然语言因其模糊性和冗长性，难以准确呈现复杂软件结构。为此，我们引入仓库规划图（RPG）——一种持久化表示，通过在单个图中编码能力、文件结构、数据流和函数，统一提案级与实现级规划。RPG用明确蓝图取代模糊的自然语言，支持长程规划和可扩展的仓库生成。基于RPG，我们开发了ZeroRepo——一个从头生成仓库的图驱动框架。它分为三个阶段：通过提案级规划和实现级细化构建图，随后进行图引导的代码生成及测试验证。为评估该方案，我们构建了RepoCraft基准测试集，包含6个真实项目与1052个任务。在RepoCraft上，ZeroRepo生成的仓库平均近36K LOC，约为最强基线（Claude Code）的3.9【数学公式】倍、其他基线的64【数学公式】倍；功能覆盖率达81.5%，通过率为69.7%，分别比Claude Code高出27.3和35.8个百分点。进一步分析显示，RPG可建模复杂依赖关系，通过近线性扩展实现日益复杂的规划，并增强LLM对仓库的理解，进而加速智能体定位。

> Large language models excel at function- and file-level code generation, yet generating complete repositories from scratch remains a fundamental challenge. This process demands coherent and reliable planning across proposal- and implementation-level stages, while natural language, due to its ambiguity and verbosity, is ill-suited for faithfully representing complex software structures. To address this, we introduce the Repository Planning Graph (RPG), a persistent representation that unifies proposal- and implementation-level planning by encoding capabilities, file structures, data flows, and functions in one graph. RPG replaces ambiguous natural language with an explicit blueprint, enabling long-horizon planning and scalable repository generation. Building on RPG, we develop ZeroRepo, a graph-driven framework for repository generation from scratch. It operates in three stages: proposal-level planning and implementation-level refinement to construct the graph, followed by graph-guided code generation with test validation. To evaluate this setting, we construct RepoCraft, a benchmark of six real-world projects with 1,052 tasks. On RepoCraft, ZeroRepo produces repositories averaging nearly 36K LOC, roughly 3.9$\times$ the strongest baseline (Claude Code) and about 64$\times$ other baselines. It attains 81.5% functional coverage and a 69.7% pass rate, exceeding Claude Code by 27.3 and 35.8 percentage points, respectively. Further analysis shows that RPG models complex dependencies, enables progressively more sophisticated planning through near-linear scaling, and enhances LLM understanding of repositories, thereby accelerating agent localization.

[Arxiv](https://arxiv.org/abs/2509.16198)