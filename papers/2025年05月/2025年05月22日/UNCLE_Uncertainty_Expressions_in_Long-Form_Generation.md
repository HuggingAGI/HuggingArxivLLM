# 长文本生成中的不确定性表达：UNCLE

发布时间：2025年05月22日

`LLM应用` `问答系统`

> UNCLE: Uncertainty Expressions in Long-Form Generation

# 摘要

> 大型语言模型（LLMs）在长文本生成中容易出现幻觉现象。一个有前景的解决方向是让LLMs在知识不足时显式表达不确定性。然而，现有研究尚未对LLMs在长文本生成中有效表达不确定性的能力进行直接且公平的评估。为填补这一空白，我们推出了UNCLE基准，专注于评估长文本和短文本问答（QA）中的不确定性表达。UNCLE覆盖了五个领域，包含4000个长文本QA实例和20000多个短文本QA对，是首个通过配对问题和黄金标准答案连接短长文本QA的数据集。除了基准，我们还开发了一套新指标来评估模型选择性表达不确定性的能力。通过UNCLE，我们发现当前模型在长文本生成中未能恰当传达不确定性。我们进一步探索了基于提示和基于训练的改进方法，其中基于训练的方法表现出更大的提升潜力。此外，短长文本不确定性表达之间对齐差距的分析，为未来基于UNCLE的研究提供了重要方向。


> Large Language Models (LLMs) are prone to hallucination, particularly in long-form generations. A promising direction to mitigate hallucination is to teach LLMs to express uncertainty explicitly when they lack sufficient knowledge. However, existing work lacks direct and fair evaluation of LLMs' ability to express uncertainty effectively in long-form generation. To address this gap, we first introduce UNCLE, a benchmark designed to evaluate uncertainty expression in both long- and short-form question answering (QA). UNCLE spans five domains and comprises 4k long-form QA instances and over 20k short-form QA pairs. Our dataset is the first to directly bridge short- and long-form QA with paired questions and gold-standard answers. Along with the benchmark, we propose a suite of new metrics to assess the models' capabilities to selectively express uncertainty. Using UNCLE, we then demonstrate that current models fail to convey uncertainty appropriately in long-form generation. We further explore both prompt-based and training-based methods to improve models' performance, with the training-based methods yielding greater gains. Further analysis of alignment gaps between short- and long-form uncertainty expression highlights promising directions for future research using UNCLE.

[Arxiv](https://arxiv.org/abs/2505.16922)