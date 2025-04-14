# 原子材料建模的图神经网络扩展定律

发布时间：2025年04月10日

`其他` `材料科学` `药物发现`

> Scaling Laws of Graph Neural Networks for Atomistic Materials Modeling

# 摘要

> 原子材料建模是连接药物发现与材料科学的关键技术，准确预测材料性质能够推动科学发现的重大突破。图神经网络（GNNs）凭借其捕捉复杂关系结构的能力，成为建模原子材料数据的前沿工具。尽管机器学习性能通常随模型和数据集规模扩大而提升，但用于原子材料建模的GNNs相较于大型语言模型（LLMs）仍显袖珍。LLMs通过利用数十亿参数和海量数据集，在各自领域取得了卓越性能。为突破这一限制，我们开发了一个具有数十亿参数的基础模型，并基于海量数据集进行训练，探索了GNNs在原子材料建模中的扩展极限。我们的方法整合了来自LLM库的技术，以高效管理大规模数据和模型，从而实现大规模GNN模型的有效训练和部署。这项研究针对扩展GNNs的三个核心问题：GNN模型架构的扩展潜力、数据集规模对模型精度的影响，以及LLM启发技术对GNN架构的适用性。具体而言，本研究的成果包括（1）揭示了GNNs的扩展规律，明确了模型规模、数据集体积与精度之间的关系；（2）开发了一个针对原子材料建模优化的基础GNN模型；（3）构建了一个增强的GNN代码库，集成了先进的LLM训练技术。我们的发现为基于数十亿参数和海量数据集的大规模GNN奠定了基础，为未来在原子材料建模领域的突破开辟了可扩展的路径。

> Atomistic materials modeling is a critical task with wide-ranging applications, from drug discovery to materials science, where accurate predictions of the target material property can lead to significant advancements in scientific discovery. Graph Neural Networks (GNNs) represent the state-of-the-art approach for modeling atomistic material data thanks to their capacity to capture complex relational structures. While machine learning performance has historically improved with larger models and datasets, GNNs for atomistic materials modeling remain relatively small compared to large language models (LLMs), which leverage billions of parameters and terabyte-scale datasets to achieve remarkable performance in their respective domains. To address this gap, we explore the scaling limits of GNNs for atomistic materials modeling by developing a foundational model with billions of parameters, trained on extensive datasets in terabyte-scale. Our approach incorporates techniques from LLM libraries to efficiently manage large-scale data and models, enabling both effective training and deployment of these large-scale GNN models. This work addresses three fundamental questions in scaling GNNs: the potential for scaling GNN model architectures, the effect of dataset size on model accuracy, and the applicability of LLM-inspired techniques to GNN architectures. Specifically, the outcomes of this study include (1) insights into the scaling laws for GNNs, highlighting the relationship between model size, dataset volume, and accuracy, (2) a foundational GNN model optimized for atomistic materials modeling, and (3) a GNN codebase enhanced with advanced LLM-based training techniques. Our findings lay the groundwork for large-scale GNNs with billions of parameters and terabyte-scale datasets, establishing a scalable pathway for future advancements in atomistic materials modeling.

[Arxiv](https://arxiv.org/abs/2504.08112)