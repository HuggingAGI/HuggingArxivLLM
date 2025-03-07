# DIMSUM：数学推理中的论述作为监督模块

发布时间：2025年03月06日

`LLM应用` `人工智能`

> DIMSUM: Discourse in Mathematical Reasoning as a Supervision Module

# 摘要

> 我们研究了GSM8k数据集上的推理，该数据集包含呈现小学数学问题的简短文本。研究发现，与Mirzadeh等（2024）一致，当前LLM在该数据集上的进展可能并非源于更强的推理能力，而是得益于更广泛的预训练数据分布的暴露。为此，我们引入了一种新的信息来源——语篇结构，以帮助数据量较少或训练较差的模型更好地推理。实验结果表明，语篇结构能够将如Llama2 13b等模型的性能提升高达160%。值得注意的是，即使对于那些很可能已经记住整个数据集的模型，向模型添加语篇结构信息仍然能够改进预测，并极大地提升大模型在分布外示例上的性能表现。

> We look at reasoning on GSM8k, a dataset of short texts presenting primary school, math problems. We find, with Mirzadeh et al. (2024), that current LLM progress on the data set may not be explained by better reasoning but by exposure to a broader pretraining data distribution. We then introduce a novel information source for helping models with less data or inferior training reason better: discourse structure. We show that discourse structure improves performance for models like Llama2 13b by up to 160%. Even for models that have most likely memorized the data set, adding discourse structural information to the model still improves predictions and dramatically improves large model performance on out of distribution examples.

[Arxiv](https://arxiv.org/abs/2503.04685)