# 组合生成的通信框架

发布时间：2025年01月31日

`Agent

理由：这篇论文主要讨论了组合性和组合泛化在机器学习中的应用，特别是通过通信游戏环境中的独立代理（发送者和接收者）来实现组合编码的生成。论文的核心内容涉及代理之间的交互和学习过程，这与Agent分类相关，因为代理（Agent）通常指的是能够自主行动、学习和交互的实体。论文中的发送者和接收者可以被视为代理，它们通过通信游戏进行学习和编码生成，这与Agent分类的主题高度契合。` `机器学习` `认知科学`

> A Comunication Framework for Compositional Generation

# 摘要

> # 组合性与组合泛化
组合性和组合泛化——理解已知概念新组合的能力——是人类语言的核心特征，也是人类认知的关键。在机器学习中，这一特性已在通信游戏环境中得到研究，其中独立的代理（发送者和接收者）从一组状态收敛到一个共享的编码策略，将状态映射到离散消息空间，接收者仅通过发送者的消息就能重建发送者观察到的状态。在生成任务中使用通信游戏仍未被充分探索，最近的组合生成方法主要依赖监督指导（通过类标签或文本）。在这项工作中，我们首次填补了这一空白，提出了一个基于自监督生成通信游戏的框架，用于从预训练的编码器-解码器模型中创建组合编码。在一个涉及发送者和接收者的迭代学习（IL）协议中，我们交替施加压缩和多样性的压力，使协议收敛到一个高效且明确的编码。近似消息熵正则化被用来支持组合编码。我们的框架基于对编码中效率、明确性和非整体性概念的严格定义和平衡的证明。我们在组合图像数据集Shapes3D上测试了该方法，展示了在重建和组合性指标上的稳健性能，超越了其他测试的离散消息框架。

> Compositionality and compositional generalization--the ability to understand novel combinations of known concepts--are central characteristics of human language and are hypothesized to be essential for human cognition. In machine learning, the emergence of this property has been studied in a communication game setting, where independent agents (a sender and a receiver) converge to a shared encoding policy from a set of states to a space of discrete messages, where the receiver can correctly reconstruct the states observed by the sender using only the sender's messages. The use of communication games in generation tasks is still largely unexplored, with recent methods for compositional generation focusing mainly on the use of supervised guidance (either through class labels or text). In this work, we take the first steps to fill this gap, and we present a self-supervised generative communication game-based framework for creating compositional encodings in learned representations from pre-trained encoder-decoder models. In an Iterated Learning (IL) protocol involving a sender and a receiver, we apply alternating pressures for compression and diversity of encoded discrete messages, so that the protocol converges to an efficient but unambiguous encoding. Approximate message entropy regularization is used to favor compositional encodings. Our framework is based on rigorous justifications and proofs of defining and balancing the concepts of Eficiency, Unambiguity and Non-Holisticity in encoding. We test our method on the compositional image dataset Shapes3D, demonstrating robust performance in both reconstruction and compositionality metrics, surpassing other tested discrete message frameworks.

[Arxiv](https://arxiv.org/abs/2501.19182)