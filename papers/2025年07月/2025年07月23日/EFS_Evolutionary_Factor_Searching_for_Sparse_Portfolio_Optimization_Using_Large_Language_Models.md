# EFS: 基于大型语言模型的进化因子搜索用于稀疏投资组合优化

发布时间：2025年07月23日

`LLM应用` `投资组合优化`

> EFS: Evolutionary Factor Searching for Sparse Portfolio Optimization Using Large Language Models

# 摘要

> 稀疏投资组合优化是定量金融中的基础性难题，传统方法因过度依赖历史收益统计和静态目标而难以适应动态市场环境。为解决这一挑战，我们提出了一种创新性框架——进化因子搜索 (EFS)，该框架通过大型语言模型 (LLMs) 实现 alpha 因子的自动化生成与演化，从而优化稀疏投资组合构建。EFS 将资产选择问题转化为由 LLM 生成因子引导的 top-m 排序任务，并引入进化反馈机制，根据性能表现持续优化因子池。在五个 Fama-French 基准数据集和 US50、HSI45、CSI300 三个真实市场数据集上的实验表明，EFS 在较大资产池和高波动性条件下显著优于传统统计和优化方法。通过全面的消融研究，我们验证了提示组合设计、因子多样性和 LLM 后端选择的重要性。研究结果表明，语言引导进化是一种在结构约束下强大且可解释的投资组合优化范式，具有广阔的应用前景。

> Sparse portfolio optimization is a fundamental yet challenging problem in quantitative finance, since traditional approaches heavily relying on historical return statistics and static objectives can hardly adapt to dynamic market regimes. To address this issue, we propose Evolutionary Factor Search (EFS), a novel framework that leverages large language models (LLMs) to automate the generation and evolution of alpha factors for sparse portfolio construction. By reformulating the asset selection problem as a top-m ranking task guided by LLM-generated factors, EFS incorporates an evolutionary feedback loop to iteratively refine the factor pool based on performance. Extensive experiments on five Fama-French benchmark datasets and three real-market datasets (US50, HSI45 and CSI300) demonstrate that EFS significantly outperforms both statistical-based and optimization-based baselines, especially in larger asset universes and volatile conditions. Comprehensive ablation studies validate the importance of prompt composition, factor diversity, and LLM backend choice. Our results highlight the promise of language-guided evolution as a robust and interpretable paradigm for portfolio optimization under structural constraints.

[Arxiv](https://arxiv.org/abs/2507.17211)