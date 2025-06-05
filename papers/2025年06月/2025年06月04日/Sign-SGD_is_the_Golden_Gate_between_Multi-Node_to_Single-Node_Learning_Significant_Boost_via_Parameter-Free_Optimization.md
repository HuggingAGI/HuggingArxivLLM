# Sign-SGD架起了多节点与单节点学习之间的金色桥梁，无参数优化带来显著性能提升

发布时间：2025年06月04日

`LLM理论` `机器学习`

> Sign-SGD is the Golden Gate between Multi-Node to Single-Node Learning: Significant Boost via Parameter-Free Optimization

# 摘要

> 大型语言模型近期在多个领域取得了突破性进展。然而，即使是拥有丰富计算资源的机构，训练这些模型仍是一项极其耗资源的任务。为应对这一挑战，Sign-SGD方法逐渐受到关注。该方法既可作为单节点训练中的内存高效方案，也可作为分布式学习中的梯度压缩技术。然而，从理论角度自动确定有效步长仍是一个难题，因为这取决于实际学习场景中难以获取的数据集参数。为解决这一问题，我们设计了多种单节点确定性Sign-SGD变体，并将其扩展至随机单节点和多节点学习场景，以及结合动量的方法。我们在实际机器学习问题上进行了大量实验，充分验证了我们的方法在实际应用中的有效性。

> Quite recently, large language models have made a significant breakthrough across various disciplines. However, training them is an extremely resource-intensive task, even for major players with vast computing resources. One of the methods gaining popularity in light of these challenges is Sign-SGD. This method can be applied both as a memory-efficient approach in single-node training and as a gradient compression technique in the distributed learning. Nevertheless, it is impossible to automatically determine the effective stepsize from the theoretical standpoint. Indeed, it depends on the parameters of the dataset to which we do not have access in the real-world learning paradigm. To address this issue, we design several variants of single-node deterministic Sign-SGD. We extend our approaches to practical scenarios: stochastic single-node and multi-node learning, methods with incorporated momentum. We conduct extensive experiments on real machine learning problems that emphasize the practical applicability of our ideas.

[Arxiv](https://arxiv.org/abs/2506.03725)