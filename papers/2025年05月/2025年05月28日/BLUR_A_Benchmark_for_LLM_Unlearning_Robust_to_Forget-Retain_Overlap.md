# BLUR：一个评估LLM无学习能力的基准，专注于遗忘与保留的重叠问题

发布时间：2025年05月28日

`LLM应用` `人工智能安全` `隐私保护`

> BLUR: A Benchmark for LLM Unlearning Robust to Forget-Retain Overlap

# 摘要

> 机器遗忘技术有望提升大型语言模型（LLM）的安全性，通过事后移除敏感或有害信息。然而，在遗忘过程中，如何平衡“遗忘质量”（有效遗忘不良信息）与“保留质量”（维持其他通用任务的性能）是一个关键挑战。不幸的是，现有LLM遗忘基准测试中的遗忘与保留数据集差异巨大，导致对LLM遗忘方法有效性的评估结果严重失真。这尤其令人担忧，因为它使良性扰动（如重新学习攻击）有机可乘，一旦模型部署，这些攻击可以轻易揭示本应被遗忘的知识。为解决这一问题，我们推出了$	exttt{BLUR}$：一个更贴近真实场景的LLM遗忘基准测试。$	exttt{BLUR}$在现有基准的基础上进行了大幅扩展，新增了扩展的评估任务、结合遗忘与保留的查询，以及难度各异的重新学习数据集。尽管我们考虑的查询本质上是良性的，但在$	exttt{BLUR}$上的评估显示，现有方法的性能大幅下降，简单的基线方法甚至优于更近期的方法。这些结果凸显了鲁棒评估的重要性，并为未来研究指明了方向。我们的基准测试已公开发布，详情请访问：https://huggingface.co/datasets/forgelab/BLUR

> Machine unlearning has the potential to improve the safety of large language models (LLMs) by removing sensitive or harmful information post hoc. A key challenge in unlearning involves balancing between forget quality (effectively unlearning undesirable information) and retain quality (maintaining good performance on other, general tasks). Unfortunately, as we show, current LLM unlearning benchmarks contain highly disparate forget and retain sets -- painting a false picture of the effectiveness of LLM unlearning methods. This can be particularly problematic because it opens the door for benign perturbations, such as relearning attacks, to easily reveal supposedly unlearned knowledge once models are deployed. To address this, we present $\texttt{BLUR}$: a benchmark for LLM unlearning that provides more realistic scenarios of forget-retain overlap. $\texttt{BLUR}$ significantly expands on existing unlearning benchmarks by providing extended evaluation tasks, combined forget/retain queries, and relearning datasets of varying degrees of difficulty. Despite the benign nature of the queries considered, we find that the performance of existing methods drops significantly when evaluated on $\texttt{BLUR}$, with simple approaches performing better on average than more recent methods. These results highlight the importance of robust evaluation and suggest several important directions of future study. Our benchmark is publicly available at: https://huggingface.co/datasets/forgelab/BLUR

[Arxiv](https://arxiv.org/abs/2506.15699)