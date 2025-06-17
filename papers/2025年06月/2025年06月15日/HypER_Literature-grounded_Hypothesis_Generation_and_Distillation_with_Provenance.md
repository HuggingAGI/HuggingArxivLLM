# HypER：基于文献的假设生成与蒸馏，结合来源信息

发布时间：2025年06月15日

`LLM应用` `假设生成`

> HypER: Literature-grounded Hypothesis Generation and Distillation with Provenance

# 摘要

> 大型语言模型在科研创意领域展现了巨大潜力，但假设开发这一关键环节却鲜少受到关注。现有方法仅关注输出质量，忽视了创意背后的推理过程。我们提出了一种小型语言模型$	exttt{HypER}$，用于文献引导的推理和基于证据的假设生成。通过多任务学习，$	exttt{HypER}$能够有效区分科学推理链的优劣（平均绝对F1值提升22%），生成的假设不仅更具证据支持（0.327 vs. 0.305），且在可行性和影响力方面均获得了专家的高度评价（5分Likert量表中评分超过3.5分）。

> Large Language models have demonstrated promising performance in research ideation across scientific domains. Hypothesis development, the process of generating a highly specific declarative statement connecting a research idea with empirical validation, has received relatively less attention. Existing approaches trivially deploy retrieval augmentation and focus only on the quality of the final output ignoring the underlying reasoning process behind ideation. We present $\texttt{HypER}$ ($\textbf{Hyp}$othesis Generation with $\textbf{E}$xplanation and $\textbf{R}$easoning), a small language model (SLM) trained for literature-guided reasoning and evidence-based hypothesis generation. $\texttt{HypER}$ is trained in a multi-task setting to discriminate between valid and invalid scientific reasoning chains in presence of controlled distractions. We find that $\texttt{HypER}$ outperformes the base model, distinguishing valid from invalid reasoning chains (+22\% average absolute F1), generates better evidence-grounded hypotheses (0.327 vs. 0.305 base model) with high feasibility and impact as judged by human experts ($>$3.5 on 5-point Likert scale).

[Arxiv](https://arxiv.org/abs/2506.12937)