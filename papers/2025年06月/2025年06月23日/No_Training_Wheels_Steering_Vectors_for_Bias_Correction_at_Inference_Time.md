# 告别训练轮：推理时偏差校正的引导向量

发布时间：2025年06月23日

`LLM应用` `人工智能` `数据分析`

> No Training Wheels: Steering Vectors for Bias Correction at Inference Time

# 摘要

> 当训练数据中不同群体的表示存在不均衡时，神经网络分类器往往会继承类别偏差并学习到无关的关联。这些模型可能在整体上表现良好，但在非典型群体上却持续表现不佳。例如，在发色分类任务中，数据集可能过度代表了金发女性，从而强化了刻板印象。尽管已经提出了多种算法和数据驱动的方法来解决此类偏差问题，但它们通常需要重新训练或消耗大量计算资源。在本研究中，我们提出了一种无需训练的低成本方法，该方法灵感来源于用于编辑大型语言模型行为的方向向量。我们通过计算多数群体与少数群体在平均激活值上的差异来定义一个“偏差向量”，然后将其从模型的残差流中减去。这使得分类偏差得到减少，同时提升了最弱势群体的分类准确率。我们探索了在类似Transformer的分类器中提取和应用这些向量的多种策略，证明了传统上用于生成模型的方向向量在分类任务中也能发挥有效作用。更广泛地说，我们展示了一种极为廉价、无需训练且在推理阶段即可应用的方法，用于减轻分类模型中的偏见问题。

> Neural network classifiers trained on datasets with uneven group representation often inherit class biases and learn spurious correlations. These models may perform well on average but consistently fail on atypical groups. For example, in hair color classification, datasets may over-represent females with blond hair, reinforcing stereotypes. Although various algorithmic and data-centric methods have been proposed to address such biases, they often require retraining or significant compute. In this work, we propose a cheap, training-free method inspired by steering vectors used to edit behaviors in large language models. We compute the difference in mean activations between majority and minority groups to define a "bias vector," which we subtract from the model's residual stream. This leads to reduced classification bias and improved worst-group accuracy. We explore multiple strategies for extracting and applying these vectors in transformer-like classifiers, showing that steering vectors, traditionally used in generative models, can also be effective in classification. More broadly, we showcase an extremely cheap, inference time, training free method to mitigate bias in classification models.

[Arxiv](https://arxiv.org/abs/2506.18598)