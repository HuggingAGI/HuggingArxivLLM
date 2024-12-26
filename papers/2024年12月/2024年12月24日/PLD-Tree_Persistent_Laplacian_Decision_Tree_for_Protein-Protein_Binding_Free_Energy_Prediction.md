# PLD-Tree：用于预测蛋白质 - 蛋白质结合自由能的持久拉普拉斯决策树

发布时间：2024年12月24日

`其他` `生物医学` `分子研究`

> PLD-Tree: Persistent Laplacian Decision Tree for Protein-Protein Binding Free Energy Prediction

# 摘要

> 近期，基于拓扑建模的进步加快了物理建模和分子研究的步伐，其中涵盖了蛋白质 - 配体结合亲和力的应用。在本研究中，我们推出了持久拉普拉斯决策树（PLD-Tree），这是一种专门用于应对预测蛋白质 - 蛋白质相互作用（PPI）亲和力这一艰巨任务的新方法。PLD-Tree 聚焦于结合界面的蛋白质链，并运用持久拉普拉斯来获取反映关键蛋白质间相互作用的拓扑不变量。这些源自持久同源性的拓扑描述符，通过融入来自大型语言模型的进化规模建模（ESM）得以进一步强化，从而整合基于序列的信息。我们在两个基准数据集——PDBbind V2020 和 SKEMPI v2 上对 PLD-Tree 进行了验证，在复杂的留一蛋白交叉验证下，相关系数（$R_p$）达到 0.83。尤为值得一提的是，在这些数据集上，我们的方法超越了所有已报道的先进方法。这些成果突显了将机器学习技术与基于拓扑的描述符相融合用于分子对接和虚拟筛选的强大力量，为预测蛋白质 - 蛋白质结合亲和力提供了一个稳固且精准的框架。

> Recent advances in topology-based modeling have accelerated progress in physical modeling and molecular studies, including applications to protein-ligand binding affinity. In this work, we introduce the Persistent Laplacian Decision Tree (PLD-Tree), a novel method designed to address the challenging task of predicting protein-protein interaction (PPI) affinities. PLD-Tree focuses on protein chains at binding interfaces and employs the persistent Laplacian to capture topological invariants reflecting critical inter-protein interactions. These topological descriptors, derived from persistent homology, are further enhanced by incorporating evolutionary scale modeling (ESM) from a large language model to integrate sequence-based information. We validate PLD-Tree on two benchmark datasets-PDBbind V2020 and SKEMPI v2 demonstrating a correlation coefficient ($R_p$) of 0.83 under the sophisticated leave-out-protein-out cross-validation. Notably, our approach outperforms all reported state-of-the-art methods on these datasets. These results underscore the power of integrating machine learning techniques with topology-based descriptors for molecular docking and virtual screening, providing a robust and accurate framework for predicting protein-protein binding affinities.

[Arxiv](https://arxiv.org/abs/2412.18541)