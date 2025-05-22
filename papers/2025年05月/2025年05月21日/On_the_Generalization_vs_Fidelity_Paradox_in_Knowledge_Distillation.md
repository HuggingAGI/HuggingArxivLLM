# 知识蒸馏中的泛化与保真度悖论研究

发布时间：2025年05月21日

`LLM理论` `人工智能`

> On the Generalization vs Fidelity Paradox in Knowledge Distillation

# 摘要

> 知识蒸馏（KD）是压缩大型语言模型同时保持性能的核心技术。尽管KD研究近期备受关注，但其对小型语言模型的效果及知识转移机制仍待深入探索。本研究首次针对参数规模从0.5B到7B的模型，在零样本设置下的14个复杂推理任务中开展大规模实证和统计分析。研究发现，KD可使小型模型的平均性能提升最高10%，特定任务更是达到22%的显著提升，而对大型模型仅带来约1.3%的微小收益。令人意外的是，教师模型的性能水平对学生成绩影响有限，但教师在特定任务上的专业能力则显著影响KD效果。相关性研究表明，小型LMs更能从KD中获益，而大型LMs的增益则相对有限。此外，我们发现学生性能提升与推理保真度之间存在不一致，表明尽管KD提高了准确性，但并不总能保持教师的结构化决策过程。通过消融研究，我们进一步发现教师信号和对数平滑是影响学生蒸馏后性能的关键因素。总体而言，本研究为KD提供了一项全面的实证和统计评估，揭示了其在知识转移过程中的优势与权衡。

> Knowledge distillation (KD) is a key technique for compressing large language models into smaller ones while preserving performance. Despite the recent traction of KD research, its effectiveness for smaller language models (LMs) and the mechanisms driving knowledge transfer remain underexplored. In this work, we present the first large-scale empirical and statistical analysis of KD across models ranging from 0.5B to 7B parameters on 14 complex reasoning tasks in a zero-shot setting. Our findings reveal that KD can improve the average performance of smaller models by up to $10\%$, with a peak task specific gain of $22\%$, while providing only marginal benefits ($\sim 1.3\%$) for larger models. Surprisingly, teacher performance has a minimal impact on student outcomes, while teacher task expertise impacts KD effectiveness. A correlation study indicates that smaller LMs benefit more from KD, whereas larger LMs show diminished gains. Additionally, we uncover a misalignment between improvements in student performance and reasoning fidelity, suggesting that while KD enhances accuracy, it does not always maintain the structured decision-making processes of the teacher. Our ablation study further highlights the importance of teacher signals and logit smoothing in influencing students' performance after distillation. Overall, our study offers a comprehensive empirical and statistical assessment of KD, highlighting both its benefits and trade-offs when distilling knowledge from larger to smaller LMs.

[Arxiv](https://arxiv.org/abs/2505.15442)