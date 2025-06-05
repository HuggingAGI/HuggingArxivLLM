# 先生成提示，再进行蒸馏：基于LLM驱动的教师-学生框架的数据标注方法

发布时间：2025年06月04日

`LLM应用` `数据标注` `数据处理`

> Prompt Candidates, then Distill: A Teacher-Student Framework for LLM-driven Data Annotation

# 摘要

> 最近，大型语言模型（LLMs）在数据标注领域展现了巨大潜力，显著降低了下游应用的劳动力成本。然而，现有方法大多采用激进策略，通过提示LLM为每个未标记样本确定单一黄金标签。由于LLMs的内在不确定性，它们在处理困难样本时往往生成错误标签，严重影响下游应用数据质量。受人类行为中规避模糊性的启发，我们提出了一种全新候选标注范式，鼓励大型语言模型在面对不确定性时输出所有可能标签。为了确保下游任务获得唯一标签，我们开发了教师-学生框架CanDist，利用小语言模型（SLM）对候选标注进行蒸馏。我们进一步提供了一个严格证明，证明从教师LLM蒸馏候选注释比直接使用单个注释提供了更优理论保证。六个文本分类任务的广泛实验验证了我们方法的有效性。源代码可在https://github.com/MingxuanXia/CanDist获取。

> Recently, Large Language Models (LLMs) have demonstrated significant potential for data annotation, markedly reducing the labor costs associated with downstream applications. However, existing methods mostly adopt an aggressive strategy by prompting LLM to determine a single gold label for each unlabeled sample. Due to the inherent uncertainty within LLMs, they often produce incorrect labels for difficult samples, severely compromising the data quality for downstream applications. Motivated by ambiguity aversion in human behaviors, we propose a novel candidate annotation paradigm wherein large language models are encouraged to output all possible labels when incurring uncertainty. To ensure unique labels are provided for downstream tasks, we develop a teacher-student framework CanDist that distills candidate annotations with a Small Language Model (SLM). We further provide a rigorous justification demonstrating that distilling candidate annotations from the teacher LLM offers superior theoretical guarantees compared to directly using single annotations. Extensive experiments across six text classification tasks validate the effectiveness of our proposed method. The source code is available at https://github.com/MingxuanXia/CanDist.

[Arxiv](https://arxiv.org/abs/2506.03857)