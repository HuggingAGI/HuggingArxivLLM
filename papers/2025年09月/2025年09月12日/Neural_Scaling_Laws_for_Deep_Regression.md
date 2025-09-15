# # 深度回归的神经缩放定律

发布时间：2025年09月12日

`其他` `基础理论`

> Neural Scaling Laws for Deep Regression

# 摘要

> 神经缩放定律——即泛化误差与深度学习模型特征之间的幂律关系——是资源有限时开发可靠模型的关键工具。尽管大型语言模型的成功凸显了这些定律的重要性，但它们在深度回归模型中的应用却鲜少被研究。在此，我们以扭曲范德华磁体的参数估计模型为研究对象，实证探究了深度回归中的神经缩放定律。我们发现，在广泛的取值范围内，损失与训练数据集大小及模型容量均呈现幂律关系，且这一现象在多种架构中一致存在——包括全连接网络、残差网络和视觉Transformer。此外，这些关系的缩放指数介于1到2之间，具体数值取决于回归参数和模型细节。这种一致的缩放行为及其较大的缩放指数表明，增加数据量可显著提升深度回归模型的性能。

> Neural scaling laws--power-law relationships between generalization errors and characteristics of deep learning models--are vital tools for developing reliable models while managing limited resources. Although the success of large language models highlights the importance of these laws, their application to deep regression models remains largely unexplored. Here, we empirically investigate neural scaling laws in deep regression using a parameter estimation model for twisted van der Waals magnets. We observe power-law relationships between the loss and both training dataset size and model capacity across a wide range of values, employing various architectures--including fully connected networks, residual networks, and vision transformers. Furthermore, the scaling exponents governing these relationships range from 1 to 2, with specific values depending on the regressed parameters and model details. The consistent scaling behaviors and their large scaling exponents suggest that the performance of deep regression models can improve substantially with increasing data size.

[Arxiv](https://arxiv.org/abs/2509.10000)