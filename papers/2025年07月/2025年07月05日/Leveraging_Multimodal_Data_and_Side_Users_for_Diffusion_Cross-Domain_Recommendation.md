# 善用多模态数据与辅助用户，实现跨领域扩散推荐

发布时间：2025年07月05日

`LLM应用` `推荐系统`

> Leveraging Multimodal Data and Side Users for Diffusion Cross-Domain Recommendation

# 摘要

> 跨领域推荐（CDR）旨在应对推荐系统中的冷启动问题。目前的研究主要通过辅助域向目标域迁移冷启动用户信息，但存在两大挑战：多模态数据利用率低，导致跨域对齐效果欠佳；忽视了仅在目标域交互的侧边用户，影响了目标域向量空间分布的学习。为解决这些问题，我们提出了一种基于多模态数据和侧边用户的扩散跨领域推荐模型（MuSiC）。首先，我们利用多模态大型语言模型提取项目特征，并通过提示学习揭示用户特征（无需微调）。其次，我们设计了跨域扩散模块，用于学习目标域特征向量的生成。该模块从侧边用户学习特征分布，并通过重叠用户理解跨域转换模式。最后，训练好的扩散模块为目标域冷启动用户生成特征向量，完成推荐任务。实验结果表明，MuSiC在亚马逊数据集上显著超越现有基线，达到最优性能。代码已开源：https://anonymous.4open.science/r/MuSiC-310A/。

> Cross-domain recommendation (CDR) aims to address the persistent cold-start problem in Recommender Systems. Current CDR research concentrates on transferring cold-start users' information from the auxiliary domain to the target domain. However, these systems face two main issues: the underutilization of multimodal data, which hinders effective cross-domain alignment, and the neglect of side users who interact solely within the target domain, leading to inadequate learning of the target domain's vector space distribution. To address these issues, we propose a model leveraging Multimodal data and Side users for diffusion Cross-domain recommendation (MuSiC). We first employ a multimodal large language model to extract item multimodal features and leverage a large language model to uncover user features using prompt learning without fine-tuning. Secondly, we propose the cross-domain diffusion module to learn the generation of feature vectors in the target domain. This approach involves learning feature distribution from side users and understanding the patterns in cross-domain transformation through overlapping users. Subsequently, the trained diffusion module is used to generate feature vectors for cold-start users in the target domain, enabling the completion of cross-domain recommendation tasks. Finally, our experimental evaluation of the Amazon dataset confirms that MuSiC achieves state-of-the-art performance, significantly outperforming all selected baselines. Our code is available: https://anonymous.4open.science/r/MuSiC-310A/.

[Arxiv](https://arxiv.org/abs/2507.04000)