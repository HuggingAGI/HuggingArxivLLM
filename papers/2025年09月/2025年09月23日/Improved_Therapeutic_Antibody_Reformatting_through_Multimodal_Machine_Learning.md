# 借助多模态机器学习优化治疗性抗体重构

发布时间：2025年09月23日

`其他` `医疗健康`

> Improved Therapeutic Antibody Reformatting through Multimodal Machine Learning

# 摘要

> 现代治疗性抗体设计常需将多个独立功能结构域组合成复合体，这些结构域可能源自不同来源或经独立改造。尽管这类复杂分子格式能扩大疾病适用范围并提升安全性，却也带来了严峻的工程挑战：单个结构域在新格式中的功能和稳定性无法保证，整个分子甚至可能无法合成。为应对这些挑战，我们开发了一个机器学习框架来预测“重格式化成功率”——即抗体从一种格式转换为另一种格式能否成功。该框架融合了抗体序列与结构信息，并采用了反映实际应用场景的评估方案。在真实世界抗体重格式化数据集的实验中，我们发现了一个意外结果：大型预训练蛋白质语言模型（PLMs）的性能竟然不及简单的、领域定制的多模态表示。这一点在最严苛的评估场景中尤为突出：我们测试模型对全新起始抗体的泛化能力。在这种极具挑战性的“新抗体、无数据”场景下，我们最优的多模态模型仍能实现高预测精度，从而可以优先筛选有潜力的候选分子，减少无效实验成本。

> Modern therapeutic antibody design often involves composing multi-part assemblages of individual functional domains, each of which may be derived from a different source or engineered independently. While these complex formats can expand disease applicability and improve safety, they present a significant engineering challenge: the function and stability of individual domains are not guaranteed in the novel format, and the entire molecule may no longer be synthesizable. To address these challenges, we develop a machine learning framework to predict "reformatting success" -- whether converting an antibody from one format to another will succeed or not. Our framework incorporates both antibody sequence and structural context, incorporating an evaluation protocol that reflects realistic deployment scenarios. In experiments on a real-world antibody reformatting dataset, we find the surprising result that large pretrained protein language models (PLMs) fail to outperform simple, domain-tailored, multimodal representations. This is particularly evident in the most difficult evaluation setting, where we test model generalization to a new starting antibody. In this challenging "new antibody, no data" scenario, our best multimodal model achieves high predictive accuracy, enabling prioritization of promising candidates and reducing wasted experimental effort.

[Arxiv](https://arxiv.org/abs/2509.19604)