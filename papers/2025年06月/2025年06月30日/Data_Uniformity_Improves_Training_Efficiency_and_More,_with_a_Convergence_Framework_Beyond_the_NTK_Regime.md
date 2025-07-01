# 数据一致性提升训练效率并带来诸多优势，采用超越 NTK 范式的收敛框架

发布时间：2025年06月30日

`LLM理论` `数据科学` `机器学习`

> Data Uniformity Improves Training Efficiency and More, with a Convergence Framework Beyond the NTK Regime

# 摘要

> 数据选择在数据驱动决策中至关重要，尤其在大型语言模型（LLMs）中，且与具体任务密切相关。数据质量与多样性等属性已被广泛研究，被认为能显著提升模型性能。然而，是否存在其他通用的定量数据选择原则，能够在知识有限的复杂任务中持续提升性能，仍是一个待解之谜。本文研究表明，选择分布更均匀的数据不仅能提高训练效率，还能显著增强模型性能。具体而言，我们发现更均匀（更少偏见）的数据分布会导致数据点间最小成对距离 $h_{\min}$ 更大，并证明较小的 $h_{\min}$ 会减缓梯度下降（GD）的训练动力学。此外，我们从理论上证明神经网络的近似误差会随着 $h_{\min}$ 的增加而减少。我们的分析引入了一个超越神经切向核（NTK）范式的 GD 收敛框架，适用于包括 transformer 在内的广泛架构类别，且无需 Lipschitz 光滑性要求。该框架进一步为深度神经架构中残差连接和函数组合的使用提供了理论支持。最后，我们在不同设置下进行了全面的监督微调实验，涵盖不同的优化策略、模型规模和训练数据集。实验结果一致表明，通过最大化成对距离选择数据可以显著加速训练，并在各种数据集的 LLM 中实现相当或更好的性能。代码和数据集可在以下链接获取：https://github.com/SafeRL-Lab/data-uniformity。


> Data selection plays a crucial role in data-driven decision-making, including in large language models (LLMs), and is typically task-dependent. Properties such as data quality and diversity have been extensively studied and are known to enhance model performance. However, it remains unclear whether there exist other quantitative and general principles of data selection that can consistently improve performance, especially for complex tasks with limited prior knowledge. In this paper, we demonstrate that selecting more uniformly distributed data can improve training efficiency while enhancing performance. Specifically, we establish that more uniform (less biased) distribution leads to a larger minimum pairwise distance between data points, denoted by $h_{\min}$, and prove that a smaller $h_{\min}$ can slow down the training dynamics of gradient descent (GD). Moreover, we theoretically show that the approximation error of neural networks decreases as $h_{\min}$ increases. Our analysis introduces a convergence framework for GD beyond the Neural Tangent Kernel (NTK) regime, applicable to a broad class of architectures, including transformers, without requiring Lipschitz smoothness. This framework further provides theoretical justification for the use of residual connections and function compositions in deep neural architectures. In the end, we conduct comprehensive experiments for supervised fine-tuning across various settings, including different optimization strategies, model sizes, and training datasets. The results consistently demonstrate that selecting data by maximizing pairwise distance significantly accelerates training and achieves comparable or better performance in LLMs across diverse datasets. Code and Datasets are available at the link: https://github.com/SafeRL-Lab/data-uniformity.

[Arxiv](https://arxiv.org/abs/2506.24120)