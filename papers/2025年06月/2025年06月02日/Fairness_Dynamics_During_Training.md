# # 公平性动态：训练过程中的演变

发布时间：2025年06月02日

`LLM理论` `社会学` `人工智能`

> Fairness Dynamics During Training

# 摘要

> 我们深入探究了大型语言模型（LLM）训练过程中公平性动态的演变，旨在通过训练干预（如提前终止）实现对偏见的诊断与缓解。研究发现，偏见的出现并不遵循常规性能指标，且可能突然发生。为此，我们提出了两个全新指标：平均排名和分部Jensen-Shannon散度，以全面评估模型预训练阶段的公平性动态。通过分析Pythia模型在WinoBias数据集上的职业性别预测任务，我们发现：(1) Pythia-6.9b对男性存在明显偏见，其在训练过程中对“男性”的预测表现优于“女性”，(2) 通过提前终止训练，Pythia-6.9b可在LAMBADA任务上牺牲1.7%的准确率，换取92.5%的公平性提升，(3) 模型规模越大，偏见越显著；Pythia-6.9b相较于Pythia-160m，对性别假设更为敏感，即使在性别未明确说明的情况下亦然。

> We investigate fairness dynamics during Large Language Model (LLM) training to enable the diagnoses of biases and mitigations through training interventions like early stopping; we find that biases can emerge suddenly and do not always follow common performance metrics. We introduce two new metrics to evaluate fairness dynamics holistically during model pre-training: Average Rank and Jensen-Shannon Divergence by Parts. These metrics provide insights into the Pythia models' progression of biases in gender prediction of occupations on the WinoBias dataset. By monitoring these dynamics, we find that (1) Pythia-6.9b is biased towards men; it becomes more performant and confident predicting "male" than "female" during training, (2) via early-stopping, Pythia-6.9b can exchange 1.7% accuracy on LAMBADA for a 92.5% increase in fairness, and (3) larger models can exhibit more bias; Pythia-6.9b makes more assumptions about gender than Pythia-160m, even when a subject's gender is not specified.

[Arxiv](https://arxiv.org/abs/2506.01709)