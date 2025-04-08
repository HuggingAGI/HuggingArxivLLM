# OrderChain：一种通用提示范式，助力提升多语言大模型的序数理解能力

发布时间：2025年04月07日

`LLM应用` `数据科学`

> OrderChain: A General Prompting Paradigm to Improve Ordinal Understanding Ability of MLLM

# 摘要

> 尽管多模态大型语言模型（MLLMs）取得了显著进展，但在实现优秀的序数回归（OR；又称序数分类）性能方面仍面临挑战。为解决这一问题，本文提出了OrderChain——一种新颖且通用的提示范式，通过特异性与共性建模提升MLLMs的序数理解能力。具体而言，我们的OrderChain包含一组任务感知提示，用于促进对多样OR任务的特异性建模，以及一种新的范围优化链式思维（RO-CoT），它通过将OR任务均匀分解为多个小范围优化子任务，学习一种对OR任务的共性思维方式。此外，我们还提出了一种类别递归划分（CRD）方法，用于生成指令候选类别提示，以支持RO-CoT的自动优化。在多种OR数据集上的全面实验表明，采用我们OrderChain的大型语言和视觉助手（LLaVA）模型显著提升了基线LLaVA的表现，例如在Adience数据集上的年龄估计准确率从47.5%提升至93.2%，在糖尿病视网膜病变数据集上的准确率从30.0%提升至85.7%。值得注意的是，采用OrderChain的LLaVA在Adience数据集上不仅在准确率上比现有最优方法高出27%，在MAE指标上也领先0.24。据我们所知，我们的OrderChain是首个专门针对OR任务增强MLLMs的研究，其有效性已在多种OR数据集上得到验证。

> Despite the remarkable progress of multimodal large language models (MLLMs), they continue to face challenges in achieving competitive performance on ordinal regression (OR; a.k.a. ordinal classification). To address this issue, this paper presents OrderChain, a novel and general prompting paradigm that improves the ordinal understanding ability of MLLMs by specificity and commonality modeling. Specifically, our OrderChain consists of a set of task-aware prompts to facilitate the specificity modeling of diverse OR tasks and a new range optimization Chain-of-Thought (RO-CoT), which learns a commonality way of thinking about OR tasks by uniformly decomposing them into multiple small-range optimization subtasks. Further, we propose a category recursive division (CRD) method to generate instruction candidate category prompts to support RO-CoT automatic optimization. Comprehensive experiments show that a Large Language and Vision Assistant (LLaVA) model with our OrderChain improves baseline LLaVA significantly on diverse OR datasets, e.g., from 47.5% to 93.2% accuracy on the Adience dataset for age estimation, and from 30.0% to 85.7% accuracy on the Diabetic Retinopathy dataset. Notably, LLaVA with our OrderChain also remarkably outperforms state-of-the-art methods by 27% on accuracy and 0.24 on MAE on the Adience dataset. To our best knowledge, our OrderChain is the first work that augments MLLMs for OR tasks, and the effectiveness is witnessed across a spectrum of OR datasets.

[Arxiv](https://arxiv.org/abs/2504.04801)