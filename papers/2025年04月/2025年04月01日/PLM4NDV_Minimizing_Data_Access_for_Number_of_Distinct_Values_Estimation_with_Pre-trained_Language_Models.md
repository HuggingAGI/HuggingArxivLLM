# PLM4NDV：利用预训练语言模型，旨在减少数据访问以实现唯一值数量的估计

发布时间：2025年04月01日

`LLM应用` `数据库` `数据管理`

> PLM4NDV: Minimizing Data Access for Number of Distinct Values Estimation with Pre-trained Language Models

# 摘要

> 多集合或列的不同值数量（NDV）估计是数据管理中的基础任务，尤其在数据库领域具有重要意义。尽管研究者们为此付出了数十年的努力，现有的方法仍存在明显不足：它们要么依赖大量均匀随机采样的样本，要么需要访问整列数据才能完成估计，这不仅导致高昂的数据访问成本，还在数据受限场景下容易产生低效估计。为解决这一问题，我们提出利用模式（schema）中的语义信息。模式中蕴含丰富的语义信息，能够有效提升NDV估计的准确性。为此，我们开发了PLM4NDV，这是一种结合预训练语言模型（PLMs）的创新方法，旨在通过提取语义模式信息来优化NDV估计。具体而言，PLM4NDV能够深入解析目标列及其所在表的语义信息，从而全面掌握列的含义。借助这些语义信息，PLM4NDV不仅显著降低了数据访问成本，还实现了精准的NDV估计，甚至在无需任何数据访问的情况下仍能保持高效运行。我们在大规模真实数据集上的实验证明了PLM4NDV相较于传统方法的显著优势。如需获取我们的代码，请访问https://github.com/bytedance/plm4ndv。

> Number of Distinct Values (NDV) estimation of a multiset/column is a basis for many data management tasks, especially within databases. Despite decades of research, most existing methods require either a significant amount of samples through uniform random sampling or access to the entire column to produce estimates, leading to substantial data access costs and potentially ineffective estimations in scenarios with limited data access. In this paper, we propose leveraging semantic information, i.e., schema, to address these challenges. The schema contains rich semantic information that can benefit the NDV estimation. To this end, we propose PLM4NDV, a learned method incorporating Pre-trained Language Models (PLMs) to extract semantic schema information for NDV estimation. Specifically, PLM4NDV leverages the semantics of the target column and the corresponding table to gain a comprehensive understanding of the column's meaning. By using the semantics, PLM4NDV reduces data access costs, provides accurate NDV estimation, and can even operate effectively without any data access. Extensive experiments on a large-scale real-world dataset demonstrate the superiority of PLM4NDV over baseline methods. Our code is available at https://github.com/bytedance/plm4ndv.

[Arxiv](https://arxiv.org/abs/2504.00608)