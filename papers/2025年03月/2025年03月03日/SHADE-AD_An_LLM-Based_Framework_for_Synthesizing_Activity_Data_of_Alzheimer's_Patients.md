# SHADE-AD：基于 LLM 的阿尔茨海默病患者活动数据合成框架

发布时间：2025年03月03日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLM）生成合成数据，用于阿尔茨海默病（AD）的监测和智能健康应用。研究展示了LLM在生成AD相关活动数据方面的应用，并评估了其在下游任务中的性能，属于将LLM技术应用于特定领域的问题，因此归类为LLM应用。` `健康监测`

> SHADE-AD: An LLM-Based Framework for Synthesizing Activity Data of Alzheimer's Patients

# 摘要

> 阿尔茨海默病（AD）已成为日益严峻的全球健康问题，亟需在智能健康应用中开发有效的监测解决方案。然而，现有解决方案的发展受到AD专用活动数据集稀缺性的严重限制。为应对这一挑战，我们提出了一种名为SHADE-AD的大型语言模型（LLM）框架，用于合成嵌入AD特征的人类活动数据集。通过结合公共数据集和我们从99名AD患者中收集的数据，SHADE-AD能够生成专门代表AD相关行为的人类活动视频。通过采用三阶段训练机制，它能够扩展活动范围，超越有限部署环境中收集的活动类型。我们对生成的数据集进行了全面评估，结果显示在人体活动识别（HAR）检测等下游任务中，性能显著提升，最高可达79.69%。真实数据与合成数据之间的详细运动指标对比显示了高度一致性，验证了合成数据集的真实性和实用性。这些结果凸显了SHADE-AD在推动智能健康应用方面的潜力，它为AD监测提供了一种既经济又保护隐私的解决方案。

> Alzheimer's Disease (AD) has become an increasingly critical global health concern, which necessitates effective monitoring solutions in smart health applications. However, the development of such solutions is significantly hindered by the scarcity of AD-specific activity datasets. To address this challenge, we propose SHADE-AD, a Large Language Model (LLM) framework for Synthesizing Human Activity Datasets Embedded with AD features. Leveraging both public datasets and our own collected data from 99 AD patients, SHADE-AD synthesizes human activity videos that specifically represent AD-related behaviors. By employing a three-stage training mechanism, it broadens the range of activities beyond those collected from limited deployment settings. We conducted comprehensive evaluations of the generated dataset, demonstrating significant improvements in downstream tasks such as Human Activity Recognition (HAR) detection, with enhancements of up to 79.69%. Detailed motion metrics between real and synthetic data show strong alignment, validating the realism and utility of the synthesized dataset. These results underscore SHADE-AD's potential to advance smart health applications by providing a cost-effective, privacy-preserving solution for AD monitoring.

[Arxiv](https://arxiv.org/abs/2503.01768)