# 矩阵驱动型即时审查系统：针对PC端环境，自信地检测并重建LLM抄袭行为

发布时间：2025年08月08日

`LLM理论` `知识产权`

> Matrix-Driven Instant Review: Confident Detection and Reconstruction of LLM Plagiarism on PC

# 摘要

> 近年来，大型语言模型（LLMs）的知识产权问题日益引发关注。通过直接复制权重、升级、剪枝或持续预训练等方式剽窃其他LLMs，并在未正确标注原始许可证的情况下声称所有权，是一种严重的学术不端行为，可能导致原始开发者的重大财务和声誉损失。然而，现有的LLM抄袭检测方法在关键领域存在不足。它们无法准确重建权重对应关系，缺乏计算统计显著性指标（如【数学公式】p值）的能力，并可能错误地将基于相似数据训练的模型标记为相关。为了解决这些问题，我们提出了一种基于矩阵分析和大偏差理论的新型方法——矩阵驱动即时审查（MDIR）。MDIR能够准确重建权重关系，提供严格的p值估计，并专注于权重相似性，而无需进行完整的模型推断。实验结果表明，即使经过广泛的转换（如随机置换和使用万亿级标记的持续预训练），MDIR仍能可靠地检测抄袭行为。此外，所有检测均可在单台PC上一小时内完成，使MDIR既高效又易于使用。

> In recent years, concerns about intellectual property (IP) in large language models (LLMs) have grown significantly. Plagiarizing other LLMs (through direct weight copying, upcycling, pruning, or continual pretraining) and claiming authorship without properly attributing to the original license, is a serious misconduct that can lead to significant financial and reputational harm to the original developers. However, existing methods for detecting LLM plagiarism fall short in key areas. They fail to accurately reconstruct weight correspondences, lack the ability to compute statistical significance measures such as $p$-values, and may mistakenly flag models trained on similar data as being related. To address these limitations, we propose Matrix-Driven Instant Review (MDIR), a novel method that leverages matrix analysis and Large Deviation Theory. MDIR achieves accurate reconstruction of weight relationships, provides rigorous $p$-value estimation, and focuses exclusively on weight similarity without requiring full model inference. Experimental results demonstrate that MDIR reliably detects plagiarism even after extensive transformations, such as random permutations and continual pretraining with trillions of tokens. Moreover, all detections can be performed on a single PC within an hour, making MDIR both efficient and accessible.

[Arxiv](https://arxiv.org/abs/2508.06309)