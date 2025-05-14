# DeepMath-Creative：评估大型语言模型数学创造力的基准测试

发布时间：2025年05月13日

`LLM应用`

> DeepMath-Creative: A Benchmark for Evaluating Mathematical Creativity of Large Language Models

# 摘要

> 为了提升大型语言模型（LLMs）的数学能力，DeepMath团队发起了一个开源项目，旨在开发开放的数学LLM并系统评估其数学创造力。本文是该计划的初步成果。
尽管近期数学LLMs的发展主要集中在推理能力的提升上，但模型的创造力却鲜少受到关注，且评估数据集仍然匮乏。为此，我们提出了一个数学创造力的评估标准，并推出了DeepMath-Creative——一个涵盖代数、几何、分析等领域的新型高质量基准，包含各类构造性问题。
我们利用该数据集对主流LLMs的创造性问题解决能力进行了系统性评估。实验结果表明，即使在较为宽松的评分标准下，表现最佳的模型O3 Mini也仅能达到70%的准确率，且主要在基础的大学水平构造性任务上。面对更复杂的题目，模型的表现急剧下降，甚至无法为开放性问题提供实质性的解题策略。这些发现表明，尽管当前的LLMs在熟悉且难度较低的问题上展现出一定的构造能力，但这种表现很可能源于对记忆模式的重组，而非真正的创造性洞察或新颖的综合能力。

> To advance the mathematical proficiency of large language models (LLMs), the DeepMath team has launched an open-source initiative aimed at developing an open mathematical LLM and systematically evaluating its mathematical creativity. This paper represents the initial contribution of this initiative. While recent developments in mathematical LLMs have predominantly emphasized reasoning skills, as evidenced by benchmarks on elementary to undergraduate-level mathematical tasks, the creative capabilities of these models have received comparatively little attention, and evaluation datasets remain scarce. To address this gap, we propose an evaluation criteria for mathematical creativity and introduce DeepMath-Creative, a novel, high-quality benchmark comprising constructive problems across algebra, geometry, analysis, and other domains. We conduct a systematic evaluation of mainstream LLMs' creative problem-solving abilities using this dataset. Experimental results show that even under lenient scoring criteria -- emphasizing core solution components and disregarding minor inaccuracies, such as small logical gaps, incomplete justifications, or redundant explanations -- the best-performing model, O3 Mini, achieves merely 70% accuracy, primarily on basic undergraduate-level constructive tasks. Performance declines sharply on more complex problems, with models failing to provide substantive strategies for open problems. These findings suggest that, although current LLMs display a degree of constructive proficiency on familiar and lower-difficulty problems, such performance is likely attributable to the recombination of memorized patterns rather than authentic creative insight or novel synthesis.

[Arxiv](https://arxiv.org/abs/2505.08744)