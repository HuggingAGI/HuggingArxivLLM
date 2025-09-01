# 生物医学研究中数据驱动的数字孪生发现

发布时间：2025年08月29日

`其他` `医疗健康`

> Data-driven Discovery of Digital Twins in Biomedical Research

# 摘要

> 近期技术进步让高通量生物数据集的获取更为便捷，从而为生物医学系统或患者数字孪生体的可靠设计提供了可能。这类计算工具刻画了驱动扰动或药物反应的关键反应网络，能够助力药物研发与个性化治疗。然而，其开发仍依赖建模人员耗时费力的数据整合工作，因此自动化方法的需求迫在眉睫。物理学中数据驱动的系统发现之所以成功，得益于干净的数据集和明确的支配定律，这激发了将类似技术应用于生物学的兴趣，而生物学却面临着独特挑战。在此，我们综述了从生物时间序列中自动推断数字孪生体的相关方法，这些方法主要包括符号回归与稀疏回归。我们从八个生物学与方法学挑战角度对算法进行了评估，这些挑战涵盖噪声/不完整数据、多条件、先验知识整合、潜变量、高维度、未观测变量导数、候选库设计及不确定性量化。综合这些标准，稀疏回归通常比符号回归表现更优，尤其在采用贝叶斯框架时。我们还着重指出深度学习与大型语言模型的新兴作用——它们实现了创新的先验知识整合方式，不过此类方法的可靠性与一致性仍亟待提升。尽管尚无单一方法能应对所有挑战，但我们认为，数字孪生体学习的突破将源于融合了以下要素的混合模块化框架：基于化学反应网络的机制基础、贝叶斯不确定性量化，以及深度学习的生成与知识整合能力。为支持其发展，我们进一步提出了一个基准框架，以跨所有挑战评估各类方法。

> Recent technological advances have expanded the availability of high-throughput biological datasets, enabling the reliable design of digital twins of biomedical systems or patients. Such computational tools represent key reaction networks driving perturbation or drug response and can guide drug discovery and personalized therapeutics. Yet, their development still relies on laborious data integration by the human modeler, so that automated approaches are critically needed. The success of data-driven system discovery in Physics, rooted in clean datasets and well-defined governing laws, has fueled interest in applying similar techniques in Biology, which presents unique challenges. Here, we reviewed methodologies for automatically inferring digital twins from biological time series, which mostly involve symbolic or sparse regression. We evaluate algorithms according to eight biological and methodological challenges, associated to noisy/incomplete data, multiple conditions, prior knowledge integration, latent variables, high dimensionality, unobserved variable derivatives, candidate library design, and uncertainty quantification. Upon these criteria, sparse regression generally outperformed symbolic regression, particularly when using Bayesian frameworks. We further highlight the emerging role of deep learning and large language models, which enable innovative prior knowledge integration, though the reliability and consistency of such approaches must be improved. While no single method addresses all challenges, we argue that progress in learning digital twins will come from hybrid and modular frameworks combining chemical reaction network-based mechanistic grounding, Bayesian uncertainty quantification, and the generative and knowledge integration capacities of deep learning. To support their development, we further propose a benchmarking framework to evaluate methods across all challenges.

[Arxiv](https://arxiv.org/abs/2508.21484)