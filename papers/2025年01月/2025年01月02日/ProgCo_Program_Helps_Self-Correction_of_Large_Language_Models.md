# ProgCo：程序助力大型语言模型的自我修正

发布时间：2025年01月02日

`LLM应用` `语言模型` `推理任务`

> ProgCo: Program Helps Self-Correction of Large Language Models

# 摘要

> 自我校正的目标是让大型语言模型（LLMs）在无外部反馈时能自我验证和自我优化初始响应。但 LLMs 常常难以有效自我验证并给出正确反馈，进一步误导优化，致使自我校正失败，在复杂推理任务中尤其如此。本文中，我们提出了程序驱动的自我校正（ProgCo）。首先，程序驱动的验证（ProgVe）通过自行生成、自行执行的验证伪程序达成复杂的验证逻辑和广泛的验证。接着，程序驱动的完善（ProgRe）接收 ProgVe 的反馈，对响应和验证程序进行双重反思与完善，以减少复杂推理任务中不正确反馈的误导。在三个指令遵循和数学基准的实验表明，ProgCo 实现了有效的自我校正，与实际程序工具结合时还能进一步提升性能。

> Self-Correction aims to enable large language models (LLMs) to self-verify and self-refine their initial responses without external feedback. However, LLMs often fail to effectively self-verify and generate correct feedback, further misleading refinement and leading to the failure of self-correction, especially in complex reasoning tasks. In this paper, we propose Program-driven Self-Correction (ProgCo). First, program-driven verification (ProgVe) achieves complex verification logic and extensive validation through self-generated, self-executing verification pseudo-programs. Then, program-driven refinement (ProgRe) receives feedback from ProgVe, conducts dual reflection and refinement on both responses and verification programs to mitigate misleading of incorrect feedback in complex reasoning tasks. Experiments on three instruction-following and mathematical benchmarks indicate that ProgCo achieves effective self-correction, and can be further enhance performance when combined with real program tools.

[Arxiv](https://arxiv.org/abs/2501.01264)