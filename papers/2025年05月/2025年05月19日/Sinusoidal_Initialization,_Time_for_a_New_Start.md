# 正弦初始化，重新开始的时刻

发布时间：2025年05月19日

`LLM理论` `神经网络`

> Sinusoidal Initialization, Time for a New Start

# 摘要

> 初始化在深度神经网络训练中至关重要，直接影响着收敛速度、训练稳定性和模型泛化能力。常见的Glorot和He初始化方法依赖于随机性，可能导致层间连接的权重分布不均匀。本文提出了一种新颖的确定性方法——正弦初始化（Sinusoidal initialization），它通过正弦函数构建结构化的权重矩阵，旨在优化网络中权重的传播与平衡，并从第一次前向传播开始，促进神经元激活状态的均匀分布和良好条件。由于正弦初始化从一开始就以均匀高效的方式利用权重和激活，它在卷积神经网络、视觉变压器和大型语言模型等多种模型中，均实现了更快的收敛速度、更高的训练稳定性和最终更高的准确度。实验数据显示，与传统方法相比，最终验证准确率平均提升了4.8%，收敛速度提高了20.9%。通过用结构替代随机性，这种初始化方法为深度学习系统奠定了更加坚实可靠的基础。


> Initialization plays a critical role in Deep Neural Network training, directly influencing convergence, stability, and generalization. Common approaches such as Glorot and He initializations rely on randomness, which can produce uneven weight distributions across layer connections. In this paper, we introduce the Sinusoidal initialization, a novel deterministic method that employs sinusoidal functions to construct structured weight matrices expressly to improve the spread and balance of weights throughout the network while simultaneously fostering a more uniform, well-conditioned distribution of neuron activation states from the very first forward pass. Because Sinusoidal initialization begins with weights and activations that are already evenly and efficiently utilized, it delivers consistently faster convergence, greater training stability, and higher final accuracy across a wide range of models, including convolutional neural networks, vision transformers, and large language models. On average, our experiments show an increase of 4.8 % in final validation accuracy and 20.9 % in convergence speed. By replacing randomness with structure, this initialization provides a stronger and more reliable foundation for Deep Learning systems.

[Arxiv](https://arxiv.org/abs/2505.12909)