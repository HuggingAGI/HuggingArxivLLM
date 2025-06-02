# GridRoute：基于 LLM 的网格环境路径规划基准测试

发布时间：2025年05月30日

`LLM应用` `人工智能` `机器人`

> GridRoute: A Benchmark for LLM-Based Route Planning with Cardinal Movement in Grid Environments

# 摘要

> 大型语言模型（LLMs）近期的突破性进展在规划与推理任务中展现出巨大潜力，为传统路径搜索算法提供了灵活的替代方案。然而，现有研究多集中于LLMs的独立推理能力，而忽视了其与传统算法的协同潜力。为填补这一空白，我们提出了一项全面评估基准GridRoute，用于评估LLMs如何有效利用传统算法的优势。同时，我们创新性地提出了名为Algorithm of Thought (AoT)的混合提示技术，将传统算法的指导引入提示设计中。我们的基准测试涵盖了参数规模从7B到72B的六种LLMs，在不同地图尺寸下评估其正确性、最优性与效率。实验结果表明，AoT在所有模型规模上均显著提升了性能，尤其在大型或复杂环境中表现尤为突出，为解决路径规划难题提供了极具前景的方法。我们的代码已开源，地址为https://github.com/LinChance/GridRoute。


> Recent advancements in Large Language Models (LLMs) have demonstrated their potential in planning and reasoning tasks, offering a flexible alternative to classical pathfinding algorithms. However, most existing studies focus on LLMs' independent reasoning capabilities and overlook the potential synergy between LLMs and traditional algorithms. To fill this gap, we propose a comprehensive evaluation benchmark GridRoute to assess how LLMs can take advantage of traditional algorithms. We also propose a novel hybrid prompting technique called Algorithm of Thought (AoT), which introduces traditional algorithms' guidance into prompting. Our benchmark evaluates six LLMs ranging from 7B to 72B parameters across various map sizes, assessing their performance in correctness, optimality, and efficiency in grid environments with varying sizes. Our results show that AoT significantly boosts performance across all model sizes, particularly in larger or more complex environments, suggesting a promising approach to addressing path planning challenges. Our code is open-sourced at https://github.com/LinChance/GridRoute.

[Arxiv](https://arxiv.org/abs/2505.24306)