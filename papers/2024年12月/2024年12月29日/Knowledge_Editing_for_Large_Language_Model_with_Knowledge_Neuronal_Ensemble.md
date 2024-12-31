# 利用知识神经元集合对大型语言模型进行知识编辑

发布时间：2024年12月29日

`LLM应用` `知识编辑` `语言模型`

> Knowledge Editing for Large Language Model with Knowledge Neuronal Ensemble

# 摘要

> 现实世界的知识持续演进，确保模型知识的及时性与准确性极为关键。这让大型语言模型中的知识编辑愈发重要。然而，现有的知识编辑方法面临数项挑战，像参数定位耦合、定位不精准以及各层间缺乏动态交互。本文中，我们提出了一种全新的知识编辑方法，名为知识神经元集成（KNE）。知识神经元集成意味着一组编码特定知识的神经元，由此缓解了参数定位耦合引发的频繁参数修改问题。KNE 方法通过为每层的每个参数计算梯度归因分数，提升了参数定位的精准度和准确度。在编辑过程中，只计算与知识神经元集成相关的梯度和损失，并相应进行误差反向传播，保证参数间的动态交互与协同更新。在三个广泛运用的知识编辑数据集上的实验结果显示，KNE 方法大幅提高了知识编辑的准确性，在可移植性和局部性指标上达到甚至超越了最佳基线方法的表现。

> As real-world knowledge is constantly evolving, ensuring the timeliness and accuracy of a model's knowledge is crucial. This has made knowledge editing in large language models increasingly important. However, existing knowledge editing methods face several challenges, including parameter localization coupling, imprecise localization, and a lack of dynamic interaction across layers. In this paper, we propose a novel knowledge editing method called Knowledge Neuronal Ensemble (KNE). A knowledge neuronal ensemble represents a group of neurons encoding specific knowledge, thus mitigating the issue of frequent parameter modification caused by coupling in parameter localization. The KNE method enhances the precision and accuracy of parameter localization by computing gradient attribution scores for each parameter at each layer. During the editing process, only the gradients and losses associated with the knowledge neuronal ensemble are computed, with error backpropagation performed accordingly, ensuring dynamic interaction and collaborative updates among parameters. Experimental results on three widely used knowledge editing datasets show that the KNE method significantly improves the accuracy of knowledge editing and achieves, or even exceeds, the performance of the best baseline methods in portability and locality metrics.

[Arxiv](https://arxiv.org/abs/2412.20637)