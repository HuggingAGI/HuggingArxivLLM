# 面向监督在线连续学习的 Transformer 模型研究

发布时间：2024年03月03日

`Agent`

> Transformers for Supervised Online Continual Learning

# 摘要

> Transformer如今已成为序列建模（如NLP和音频处理）领域的主导架构，甚至在图像分类等非顺序任务上也崭露头角。凭借对一组标记进行上下文关注与处理的能力，它们展现出强大的基于上下文的少量样本学习性能。然而，其在在线持续学习方面的可能性仍待深入挖掘。在这种环境下，模型需不断适应变化的数据流，以最小化累计的后续预测误差。我们将焦点置于监督式在线持续学习场景，其中目标是针对一系列示例$(x_t, y_t)$学习预测函数$x_t \rightarrow y_t$。受Transformer上下文学习能力及其与元学习联系的启示，我们提出一种新方法，充分利用这些优势来应对在线持续学习挑战。该方法特别让Transformer实时关注最新观测数据，并同步采用随机梯度下降在线训练，借鉴Transformer-XL的训练流程。同时，我们融入重播机制，在遵循序列学习规则的同时保持多轮训练的优点。我们推测，这种方法结合了上下文学习带来的快速适应性和参数学习所带来的持久性长期改进效果。实验证明，我们的方法在极具挑战性的大型真实世界图像地理定位基准CLOC上取得了显著超越先前最佳水平的成果。

> Transformers have become the dominant architecture for sequence modeling tasks such as natural language processing or audio processing, and they are now even considered for tasks that are not naturally sequential such as image classification. Their ability to attend to and to process a set of tokens as context enables them to develop in-context few-shot learning abilities. However, their potential for online continual learning remains relatively unexplored. In online continual learning, a model must adapt to a non-stationary stream of data, minimizing the cumulative nextstep prediction loss. We focus on the supervised online continual learning setting, where we learn a predictor $x_t \rightarrow y_t$ for a sequence of examples $(x_t, y_t)$. Inspired by the in-context learning capabilities of transformers and their connection to meta-learning, we propose a method that leverages these strengths for online continual learning. Our approach explicitly conditions a transformer on recent observations, while at the same time online training it with stochastic gradient descent, following the procedure introduced with Transformer-XL. We incorporate replay to maintain the benefits of multi-epoch training while adhering to the sequential protocol. We hypothesize that this combination enables fast adaptation through in-context learning and sustained longterm improvement via parametric learning. Our method demonstrates significant improvements over previous state-of-the-art results on CLOC, a challenging large-scale real-world benchmark for image geo-localization.

[Arxiv](https://arxiv.org/abs/2403.01554)