# MEJO：基于任务间与任务内联合优化的多模态大型语言模型赋能手术三元组识别

发布时间：2025年09月16日

`LLM应用` `医疗健康`

> MEJO: MLLM-Engaged Surgical Triplet Recognition via Inter- and Intra-Task Joint Optimization

# 摘要

> 手术三元组识别需识别器械、动词、目标及其组合，是一项受长尾数据分布困扰的复杂手术场景理解难题。得益于跨任务协同促进的主流多任务学习范式在三元组识别中已展现出良好性能，但仍面临两个关键挑战：1）任务通用与特定表示纠缠引发的任务间优化冲突；2）类别不平衡训练数据导致的任务内优化冲突。为解决这些难题，我们提出MLLM参与的联合优化（MEJO）框架，旨在为手术三元组识别实现任务间与任务内的协同优化。针对任务间优化，我们提出共享-特定-解耦（S²D）学习方案，将表示分解为任务共享与特定组件。为增强任务共享表示，我们构建了多模态大型语言模型（MLLM）驱动的概率提示池，借助专家级语义线索动态增强视觉特征。此外，通过涵盖时空维度的专属任务提示对全面的任务特定线索建模，有效缓解了任务间模糊性。针对任务内优化冲突，我们开发了协调梯度学习（CGL）策略，通过剖析并重新平衡头部与尾部类别的正负梯度，实现更协调的学习过程。在CholecT45和CholecT50数据集上的大量实验表明，我们提出的框架具有优越性，验证了其在处理优化冲突方面的有效性。

> Surgical triplet recognition, which involves identifying instrument, verb, target, and their combinations, is a complex surgical scene understanding challenge plagued by long-tailed data distribution. The mainstream multi-task learning paradigm benefiting from cross-task collaborative promotion has shown promising performance in identifying triples, but two key challenges remain: 1) inter-task optimization conflicts caused by entangling task-generic and task-specific representations; 2) intra-task optimization conflicts due to class-imbalanced training data. To overcome these difficulties, we propose the MLLM-Engaged Joint Optimization (MEJO) framework that empowers both inter- and intra-task optimization for surgical triplet recognition. For inter-task optimization, we introduce the Shared-Specific-Disentangled (S$^2$D) learning scheme that decomposes representations into task-shared and task-specific components. To enhance task-shared representations, we construct a Multimodal Large Language Model (MLLM) powered probabilistic prompt pool to dynamically augment visual features with expert-level semantic cues. Additionally, comprehensive task-specific cues are modeled via distinct task prompts covering the temporal-spatial dimensions, effectively mitigating inter-task ambiguities. To tackle intra-task optimization conflicts, we develop a Coordinated Gradient Learning (CGL) strategy, which dissects and rebalances the positive-negative gradients originating from head and tail classes for more coordinated learning behaviors. Extensive experiments on the CholecT45 and CholecT50 datasets demonstrate the superiority of our proposed framework, validating its effectiveness in handling optimization conflicts.

[Arxiv](https://arxiv.org/abs/2509.12893)