# 社会事件检测中的显式和隐式数据增强

发布时间：2025年09月04日

`LLM应用` `媒体与娱乐`

> Explicit and Implicit Data Augmentation for Social Event Detection

# 摘要

> 社交事件检测需从社交媒体中识别并分类重要事件，这类任务依赖标注数据，但标注过程成本高昂且耗力。为解决这一问题，我们提出社交事件检测增强框架（SED-Aug）——一个即插即用的双重增强框架，它融合显式文本增强与隐式特征空间增强，以提升数据多样性和模型鲁棒性。显式增强借助大型语言模型，通过五种多样化生成策略丰富文本信息；隐式增强则设计了五种新颖的扰动技术，在结构融合嵌入的特征空间中进行操作。这些扰动旨在保留嵌入的语义及关系属性，同时增强其多样性。实验显示，在平均F1分数上，SED-Aug在Twitter2012数据集上较最佳基线模型提升约17.67%，在Twitter2018数据集上提升约15.57%。代码已开源至GitHub：https://github.com/congboma/SED-Aug。

> Social event detection involves identifying and categorizing important events from social media, which relies on labeled data, but annotation is costly and labor-intensive. To address this problem, we propose Augmentation framework for Social Event Detection (SED-Aug), a plug-and-play dual augmentation framework, which combines explicit text-based and implicit feature-space augmentation to enhance data diversity and model robustness. The explicit augmentation utilizes large language models to enhance textual information through five diverse generation strategies. For implicit augmentation, we design five novel perturbation techniques that operate in the feature space on structural fused embeddings. These perturbations are crafted to keep the semantic and relational properties of the embeddings and make them more diverse. Specifically, SED-Aug outperforms the best baseline model by approximately 17.67% on the Twitter2012 dataset and by about 15.57% on the Twitter2018 dataset in terms of the average F1 score. The code is available at GitHub: https://github.com/congboma/SED-Aug.

[Arxiv](https://arxiv.org/abs/2509.04202)