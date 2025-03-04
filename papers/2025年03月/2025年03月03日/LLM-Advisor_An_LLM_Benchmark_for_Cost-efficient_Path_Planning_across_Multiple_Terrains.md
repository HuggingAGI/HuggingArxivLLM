# LLM-Advisor：跨多地形的高效路径规划基准测试

发布时间：2025年03月03日

`LLM应用` `机器人导航` `复杂地形`

> LLM-Advisor: An LLM Benchmark for Cost-efficient Path Planning across Multiple Terrains

# 摘要

> 多地形低成本路径规划是机器人导航中的重要任务，要求从起点到目标点找到一条既能避开障碍物又能最小化旅行成本的路径。这一任务在现实世界中尤为重要，因为机器人需要在难以充电或加油的户外复杂地形中导航。然而，这一领域的研究却非常有限。

本文中，我们开发了一种基于提示的方法——LLM-Advisor，利用大型语言模型（LLMs）作为有效的路径规划顾问。LLM-Advisor能够选择性地提供建议，证明了它能够识别出何时不需要修改。当提供建议时，A*算法中70.59%的路径、RRT*算法中69.47%的路径以及LLM-A*算法中78.70%的路径在成本效率上得到了提升。

由于LLM-Advisor的建议可能偶尔缺乏常识，我们提出了两种幻觉缓解策略。此外，我们实验证明，即使在地形描述清晰的情况下，GPT-4在零样本路径规划任务中表现也很差，这表明其空间意识较低。我们还通过实验表明，将LLM用作顾问比直接将其集成到路径规划循环中更有效。由于LLMs可能会生成幻觉，将LLMs用于基于搜索的方法（如A*）的循环中可能会导致更多路径失败，这表明我们提出的LLM-Advisor是一个更好的选择。

> Multi-terrain cost-efficient path planning is a crucial task in robot navigation, requiring the identification of a path from the start to the goal that not only avoids obstacles but also minimizes travel costs. This is especially crucial for real-world applications where robots need to navigate diverse terrains in outdoor environments, where recharging or refueling is difficult. However, there is very limited research on this topic. In this paper, we develop a prompt-based approach, LLM-Advisor, which leverages large language models (LLMs) as effective advisors for path planning. The LLM-Advisor selectively provides suggestions, demonstrating its ability to recognize when no modifications are necessary. When suggestions are made, 70.59% of the paths suggested for the A* algorithm, 69.47% for the RRT* algorithm, and 78.70% for the LLM-A* algorithm achieve greater cost efficiency. Since LLM-Advisor may occasionally lack common sense in their suggestions, we propose two hallucination-mitigation strategies. Furthermore, we experimentally verified that GPT-4o performs poorly in zero-shot path planning, even when terrain descriptions are clearly provided, demonstrating its low spatial awareness. We also experimentally demonstrate that using an LLM as an advisor is more effective than directly integrating it into the path-planning loop. Since LLMs may generate hallucinations, using LLMs in the loop of a search-based method (such as A*) may lead to a higher number of failed paths, demonstrating that our proposed LLM-Advisor is a better choice.

[Arxiv](https://arxiv.org/abs/2503.01236)