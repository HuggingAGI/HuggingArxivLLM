# # 图像识别自动化框架

发布时间：2025年06月23日

`LLM应用

理由：这篇论文主要探讨了如何利用生成式AI和大型语言模型来生成和增强数据集，从而训练出高性能的深度学习模型。它详细描述了基于生成式AI的自动化图像识别框架，并展示了其在数据生成和模型训练中的应用。因此，这篇论文属于LLM应用类别。` `图像识别` `计算机视觉`

> Automated Image Recognition Framework

# 摘要

> 深度学习模型的效果在很大程度上依赖于数据，但为特定任务收集和标注数据，特别是在处理新颖或敏感主题且缺乏相关数据集的情况下，往往面临巨大的时间和资源挑战。为了解决这一问题，我们提出了一种基于生成式AI的自动化图像识别（AIR）框架。该框架让终端用户能够轻松生成高质量的预标注数据集，无需手动标注。它还能够基于生成的数据集自动训练出性能强劲的深度学习模型。我们的框架包含两个核心数据合成模块：AIR-Gen和AIR-Aug。其中，AIR-Gen能够根据用户需求生成定制化的数据集。为了提升图像质量，我们开发了一种新型自动化提示工程模块，充分挖掘大型语言模型的潜力。同时，我们引入了一种分布调整算法，通过消除重复项和异常值，显著提升了生成数据集的鲁棒性和可靠性。另一方面，AIR-Aug能够增强现有数据集，从而提升深度分类模型的性能。当用户在特定任务上数据有限时，这一功能尤其有用。通过全面的实验，我们验证了生成数据在训练深度学习模型中的有效性，并展示了该系统为广泛的对象提供图像识别模型的巨大潜力。此外，我们还开展了一项用户研究，取得了4.4/5.0的出色得分，充分体现了AI社区对AIR的高度认可。

> While the efficacy of deep learning models heavily relies on data, gathering and annotating data for specific tasks, particularly when addressing novel or sensitive subjects lacking relevant datasets, poses significant time and resource challenges. In response to this, we propose a novel Automated Image Recognition (AIR) framework that harnesses the power of generative AI. AIR empowers end-users to synthesize high-quality, pre-annotated datasets, eliminating the necessity for manual labeling. It also automatically trains deep learning models on the generated datasets with robust image recognition performance. Our framework includes two main data synthesis processes, AIR-Gen and AIR-Aug. The AIR-Gen enables end-users to seamlessly generate datasets tailored to their specifications. To improve image quality, we introduce a novel automated prompt engineering module that leverages the capabilities of large language models. We also introduce a distribution adjustment algorithm to eliminate duplicates and outliers, enhancing the robustness and reliability of generated datasets. On the other hand, the AIR-Aug enhances a given dataset, thereby improving the performance of deep classifier models. AIR-Aug is particularly beneficial when users have limited data for specific tasks. Through comprehensive experiments, we demonstrated the efficacy of our generated data in training deep learning models and showcased the system's potential to provide image recognition models for a wide range of objects. We also conducted a user study that achieved an impressive score of 4.4 out of 5.0, underscoring the AI community's positive perception of AIR.

[Arxiv](https://arxiv.org/abs/2506.19261)