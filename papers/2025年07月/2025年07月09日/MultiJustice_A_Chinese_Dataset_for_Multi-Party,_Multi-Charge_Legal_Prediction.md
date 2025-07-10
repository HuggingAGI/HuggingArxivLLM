# MultiJustice: 一个用于多方多罪名法律预测的中文数据集

发布时间：2025年07月09日

`LLM应用` `模型评估`

> MultiJustice: A Chinese Dataset for Multi-Party, Multi-Charge Legal Prediction

# 摘要

> 法律判决预测为从业者和研究人员提供了一种有力工具，但一个关键问题尚未充分探索：在法律判决预测（LJP）中，是否应分别处理多个被告和罪名？为解决这一问题，我们推出了多主体多罪名预测（MPMCP）数据集，并通过评估四个实际场景中的主流法律模型表现来寻找答案：单一被告单一罪名（S1）、单一被告多罪名（S2）、多个被告单一罪名（S3），以及多个被告多罪名（S4）。我们在罪名预测和刑期预测两个任务上对数据集进行了全面评估。实验结果显示，S4（多个被告多罪名）是最大的挑战，其次是 S2、S3 和 S1。不同模型的表现差异显著。例如，与 S1 相比，InternLM2 在 S4 中的 F1 值下降了约 4.5%，LogD 值上升了约 2.8%；而 Lawformer 的 F1 值下降了 19.7%，LogD 值上升了 19.0%。我们的数据集和代码已开源，欢迎访问 https://github.com/lololo-xiao/MultiJustice-MPMCP 查看。

> Legal judgment prediction offers a compelling method to aid legal practitioners and researchers. However, the research question remains relatively under-explored: Should multiple defendants and charges be treated separately in LJP? To address this, we introduce a new dataset namely multi-person multi-charge prediction (MPMCP), and seek the answer by evaluating the performance of several prevailing legal large language models (LLMs) on four practical legal judgment scenarios: (S1) single defendant with a single charge, (S2) single defendant with multiple charges, (S3) multiple defendants with a single charge, and (S4) multiple defendants with multiple charges. We evaluate the dataset across two LJP tasks, i.e., charge prediction and penalty term prediction. We have conducted extensive experiments and found that the scenario involving multiple defendants and multiple charges (S4) poses the greatest challenges, followed by S2, S3, and S1. The impact varies significantly depending on the model. For example, in S4 compared to S1, InternLM2 achieves approximately 4.5% lower F1-score and 2.8% higher LogD, while Lawformer demonstrates around 19.7% lower F1-score and 19.0% higher LogD. Our dataset and code are available at https://github.com/lololo-xiao/MultiJustice-MPMCP.

[Arxiv](https://arxiv.org/abs/2507.06909)