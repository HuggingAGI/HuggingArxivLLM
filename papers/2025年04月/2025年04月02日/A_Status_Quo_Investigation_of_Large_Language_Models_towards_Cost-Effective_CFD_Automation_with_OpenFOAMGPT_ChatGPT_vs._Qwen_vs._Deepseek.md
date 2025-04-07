# 大型语言模型在成本效益CFD自动化中的现状研究：基于OpenFOAMGPT的ChatGPT、Qwen与Deepseek对比分析

发布时间：2025年04月02日

`LLM应用` `工程学` `计算流体动力学`

> A Status Quo Investigation of Large Language Models towards Cost-Effective CFD Automation with OpenFOAMGPT: ChatGPT vs. Qwen vs. Deepseek

# 摘要

> 我们评估了整合多个大型语言模型的 OpenFOAMGPT 的性能。部分当前模型能高效处理不同CFD任务，如调整边界条件、湍流模型和求解器配置，尽管它们的代币成本和稳定性有所差异。本地部署的小型模型如 QwQ-32B 在生成复杂流程的有效求解器文件时显得力不从心。零样本提示在模拟具有复杂设置时普遍失败，即使是大型模型也不例外。边界条件和求解器关键词相关的挑战凸显了对专家监督的需求，表明要实现CFD模拟的全面自动化仍需进一步开发。

> We evaluated the performance of OpenFOAMGPT incorporating multiple large-language models. Some of the present models efficiently manage different CFD tasks such as adjusting boundary conditions, turbulence models, and solver configurations, although their token cost and stability vary. Locally deployed smaller models like QwQ-32B struggled with generating valid solver files for complex processes. Zero-shot prompting commonly failed in simulations with intricate settings, even for large models. Challenges with boundary conditions and solver keywords stress the requirement for expert supervision, indicating that further development is needed to fully automate specialized CFD simulations.

[Arxiv](https://arxiv.org/abs/2504.02888)