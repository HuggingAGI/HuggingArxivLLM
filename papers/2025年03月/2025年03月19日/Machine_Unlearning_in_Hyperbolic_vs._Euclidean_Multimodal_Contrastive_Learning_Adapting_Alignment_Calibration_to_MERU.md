# 机器遗忘在双曲与欧氏多模态对比学习中的对比：适应MERU的对齐校准调整

发布时间：2025年03月19日

`LLM理论` `人工智能` `模型训练`

> Machine Unlearning in Hyperbolic vs. Euclidean Multimodal Contrastive Learning: Adapting Alignment Calibration to MERU

# 摘要

> 机器遗忘方法在大型预训练模型中选择性移除特定概念方面愈发重要。尽管近期研究已探索了欧几里得对比视觉-语言模型中的遗忘机制，但超球面空间中概念移除的有效性仍未得到探索。本文研究了超球面对比学习中的机器遗忘，通过将对齐校准方法适配到MERU模型中，该模型将图像和文本嵌入超球面空间以更好地捕捉语义层级结构。通过系统性实验和消融研究，我们证明了超球面几何在概念移除方面具有独特优势，能够在合理保留原有概念性能的同时实现近乎完美的遗忘，尤其在处理多概念移除时表现更为显著。我们的方法引入了超球面特有的构成要素，包括蕴含校准和范数正则化，充分挖掘了超球面空间的独特属性。与欧几里得模型的对比分析揭示了遗忘动态的根本差异，超球面遗忘能够重组语义层级，而欧几里得方法仅能切断跨模态关联。这些发现不仅推动了机器遗忘技术的发展，也为理解影响多模态模型中概念表示与移除的几何属性提供了洞见。源代码可从https://github.com/alex-pv01/HAC获取

> Machine unlearning methods have become increasingly important for selective concept removal in large pre-trained models. While recent work has explored unlearning in Euclidean contrastive vision-language models, the effectiveness of concept removal in hyperbolic spaces remains unexplored. This paper investigates machine unlearning in hyperbolic contrastive learning by adapting Alignment Calibration to MERU, a model that embeds images and text in hyperbolic space to better capture semantic hierarchies. Through systematic experiments and ablation studies, we demonstrate that hyperbolic geometry offers distinct advantages for concept removal, achieving near perfect forgetting with reasonable performance on retained concepts, particularly when scaling to multiple concept removal. Our approach introduces hyperbolic-specific components including entailment calibration and norm regularization that leverage the unique properties of hyperbolic space. Comparative analysis with Euclidean models reveals fundamental differences in unlearning dynamics, with hyperbolic unlearning reorganizing the semantic hierarchy while Euclidean approaches merely disconnect cross-modal associations. These findings not only advance machine unlearning techniques but also provide insights into the geometric properties that influence concept representation and removal in multimodal models. Source code available at https://github.com/alex-pv01/HAC

[Arxiv](https://arxiv.org/abs/2503.15166)