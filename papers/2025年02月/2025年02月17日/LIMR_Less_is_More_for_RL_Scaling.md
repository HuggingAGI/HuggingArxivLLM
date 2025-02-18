# LIMR：强化学习扩展，少即是多。

发布时间：2025年02月17日

`LLM应用` `人工智能`

> LIMR: Less is More for RL Scaling

# 摘要

> 本文探讨：强化学习（RL）训练数据真正有效性的决定因素是什么？尽管近期o1、Deepseek R1和Kimi1.5等进展展示了RL的潜力，但训练数据需求的不透明性阻碍了系统性研究。我们从基础模型直接入手，不使用蒸馏技术，挑战了“扩大RL训练数据规模必然提升性能”的传统假设。研究发现，仅需1,389个战略性样本即可超越完整的8,523个样本数据集。我们提出学习影响测量（LIM），这是一种基于模型学习轨迹对齐程度自动评估和优先排序训练样本的方法，可实现资源高效利用和大规模实施。我们的方法仅使用1,389个样本，即可达到甚至超越完整8,523样本数据集的性能。值得注意的是，尽管近期数据高效方法（如LIMO和s1）在32B规模模型中表现良好，但我们发现它们在7B规模模型中通过监督微调（SFT）表现显著不佳。相比之下，我们的基于RL的LIMR在AIME24上准确率提升了16.7%，并在MATH500上分别比LIMO和s1高出13.0%和22.2%。这些结果重新定义了我们对LLMs中RL扩展的理解，表明精准的样本选择，而非数据规模，可能是提升推理能力的关键。为支持研究创新，我们开源了LIMR，包括LIM实现、训练评估代码、整理数据集及训练模型，访问地址为https://github.com/GAIR-NLP/LIMR。

> In this paper, we ask: what truly determines the effectiveness of RL training data for enhancing language models' reasoning capabilities? While recent advances like o1, Deepseek R1, and Kimi1.5 demonstrate RL's potential, the lack of transparency about training data requirements has hindered systematic progress. Starting directly from base models without distillation, we challenge the assumption that scaling up RL training data inherently improves performance. we demonstrate that a strategically selected subset of just 1,389 samples can outperform the full 8,523-sample dataset. We introduce Learning Impact Measurement (LIM), an automated method to evaluate and prioritize training samples based on their alignment with model learning trajectories, enabling efficient resource utilization and scalable implementation. Our method achieves comparable or even superior performance using only 1,389 samples versus the full 8,523 samples dataset. Notably, while recent data-efficient approaches (e.g., LIMO and s1) show promise with 32B-scale models, we find it significantly underperforms at 7B-scale through supervised fine-tuning (SFT). In contrast, our RL-based LIMR achieves 16.7% higher accuracy on AIME24 and outperforms LIMO and s1 by 13.0% and 22.2% on MATH500. These results fundamentally reshape our understanding of RL scaling in LLMs, demonstrating that precise sample selection, rather than data scale, may be the key to unlocking enhanced reasoning capabilities. For reproducible research and future innovation, we are open-sourcing LIMR, including implementation of LIM, training and evaluation code, curated datasets, and trained models at https://github.com/GAIR-NLP/LIMR.

[Arxiv](https://arxiv.org/abs/2502.11886)