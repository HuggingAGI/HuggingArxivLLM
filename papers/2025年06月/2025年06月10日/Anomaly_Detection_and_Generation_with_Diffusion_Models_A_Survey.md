# 利用扩散模型进行异常检测与生成的综述

发布时间：2025年06月10日

`其他` `异常检测` `网络安全`

> Anomaly Detection and Generation with Diffusion Models: A Survey

# 摘要

> 异常检测（AD）在网络安全、金融、医疗和工业制造等领域中发挥着关键作用，通过识别现实世界数据中的异常模式实现。近年来，扩散模型（DMs）因其强大的学习和生成能力，为无监督异常检测提供了新思路。本综述全面探讨了基于扩散模型的异常检测与生成（ADGDM），从理论到实践，覆盖多种数据类型。与传统综述不同，我们揭示了异常检测与生成之间的协同关系：生成技术解决数据稀缺问题，检测方法提升生成质量，二者相辅相成。通过分类法分析现有方法，并探讨未来挑战与方向，包括高效架构和基础模型的结合。本综述旨在为研究者和从业者提供利用扩散模型开发创新异常检测方案的指导。

> Anomaly detection (AD) plays a pivotal role across diverse domains, including cybersecurity, finance, healthcare, and industrial manufacturing, by identifying unexpected patterns that deviate from established norms in real-world data. Recent advancements in deep learning, specifically diffusion models (DMs), have sparked significant interest due to their ability to learn complex data distributions and generate high-fidelity samples, offering a robust framework for unsupervised AD. In this survey, we comprehensively review anomaly detection and generation with diffusion models (ADGDM), presenting a tutorial-style analysis of the theoretical foundations and practical implementations and spanning images, videos, time series, tabular, and multimodal data. Crucially, unlike existing surveys that often treat anomaly detection and generation as separate problems, we highlight their inherent synergistic relationship. We reveal how DMs enable a reinforcing cycle where generation techniques directly address the fundamental challenge of anomaly data scarcity, while detection methods provide critical feedback to improve generation fidelity and relevance, advancing both capabilities beyond their individual potential. A detailed taxonomy categorizes ADGDM methods based on anomaly scoring mechanisms, conditioning strategies, and architectural designs, analyzing their strengths and limitations. We final discuss key challenges including scalability and computational efficiency, and outline promising future directions such as efficient architectures, conditioning strategies, and integration with foundation models (e.g., visual-language models and large language models). By synthesizing recent advances and outlining open research questions, this survey aims to guide researchers and practitioners in leveraging DMs for innovative AD solutions across diverse applications.

[Arxiv](https://arxiv.org/abs/2506.09368)