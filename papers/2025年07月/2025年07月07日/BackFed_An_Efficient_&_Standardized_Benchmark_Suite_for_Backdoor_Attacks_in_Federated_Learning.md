# BackFed：联邦学习后门攻击的高效标准化基准套件

发布时间：2025年07月07日

`其他` `联邦学习` `网络安全`

> BackFed: An Efficient & Standardized Benchmark Suite for Backdoor Attacks in Federated Learning

# 摘要

> 联邦学习（FL）系统面临后门攻击威胁，攻击者通过在中毒数据上训练本地模型并提交中毒更新破坏全局模型。尽管已有诸多攻击与防御方法提出，但实验设置差异、实现错误及不切实际的假设限制了对其实战有效性的公平比较和有效结论。为此，我们推出BackFed——一个全面基准测试套件，旨在标准化、简化并可靠评估FL中的后门攻击与防御，特别关注实际约束。我们的基准测试通过多进程实现显著加速实验，并采用模块化设计，借助清晰定义的API无缝集成新方法。借助标准化评估流程，我们设想BackFed为研究人员提供一个即插即用环境，以全面可靠评估新攻击与防御。利用BackFed，我们在计算机视觉和自然语言处理任务中，针对多样化的模型架构和实验设置，开展具有代表性的后门攻击与防御大规模研究。我们的实验对现有攻击与防御性能进行批判性评估，揭示实际条件下未知的局限性和失效模式。这些实证见解为新方法开发和提升FL系统安全性提供了宝贵指导。我们的框架已开源，地址为https://github.com/thinh-dao/BackFed。


> Federated Learning (FL) systems are vulnerable to backdoor attacks, where adversaries train their local models on poisoned data and submit poisoned model updates to compromise the global model. Despite numerous proposed attacks and defenses, divergent experimental settings, implementation errors, and unrealistic assumptions hinder fair comparisons and valid conclusions about their effectiveness in real-world scenarios. To address this, we introduce BackFed - a comprehensive benchmark suite designed to standardize, streamline, and reliably evaluate backdoor attacks and defenses in FL, with a focus on practical constraints. Our benchmark offers key advantages through its multi-processing implementation that significantly accelerates experimentation and the modular design that enables seamless integration of new methods via well-defined APIs. With a standardized evaluation pipeline, we envision BackFed as a plug-and-play environment for researchers to comprehensively and reliably evaluate new attacks and defenses. Using BackFed, we conduct large-scale studies of representative backdoor attacks and defenses across both Computer Vision and Natural Language Processing tasks with diverse model architectures and experimental settings. Our experiments critically assess the performance of proposed attacks and defenses, revealing unknown limitations and modes of failures under practical conditions. These empirical insights provide valuable guidance for the development of new methods and for enhancing the security of FL systems. Our framework is openly available at https://github.com/thinh-dao/BackFed.

[Arxiv](https://arxiv.org/abs/2507.04903)