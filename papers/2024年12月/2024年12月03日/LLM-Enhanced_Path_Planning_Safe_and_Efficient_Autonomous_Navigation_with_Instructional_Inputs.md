# LLM 强化的路径规划：凭借指导性输入实现安全高效的自主导航

发布时间：2024年12月03日

`LLM应用`

> LLM-Enhanced Path Planning: Safe and Efficient Autonomous Navigation with Instructional Inputs

# 摘要

> 自然语言指令引导下的自主导航对于提升人机交互效果以及在动态环境中开展复杂操作至关重要。尽管大型语言模型（LLMs）并非专为规划而设，但它们能够通过提供引导和告知约束条件，显著提升规划效率，保障安全性。本文引入了一个将 LLMs 与 2D 占用网格地图和自然语言指令相融合的规划框架，以在资源有限的情况下提升空间推理和任务执行能力。通过分解高级指令和实时环境数据，该系统为取放任务生成了结构化的导航规划，涵盖避障、目标优先级排序和自适应行为等。该框架会动态重新计算路径以应对环境变化，并与隐性社会规范相契合，实现人机交互的无缝衔接。我们的成果展现了 LLMs 在设计情境感知系统方面的潜力，能够提升工业和动态环境中的导航效率与安全性。

> Autonomous navigation guided by natural language instructions is essential for improving human-robot interaction and enabling complex operations in dynamic environments. While large language models (LLMs) are not inherently designed for planning, they can significantly enhance planning efficiency by providing guidance and informing constraints to ensure safety. This paper introduces a planning framework that integrates LLMs with 2D occupancy grid maps and natural language commands to improve spatial reasoning and task execution in resource-limited settings. By decomposing high-level commands and real-time environmental data, the system generates structured navigation plans for pick-and-place tasks, including obstacle avoidance, goal prioritization, and adaptive behaviors. The framework dynamically recalculates paths to address environmental changes and aligns with implicit social norms for seamless human-robot interaction. Our results demonstrates the potential of LLMs to design context-aware system to enhance navigation efficiency and safety in industrial and dynamic environments.

[Arxiv](https://arxiv.org/abs/2412.02655)