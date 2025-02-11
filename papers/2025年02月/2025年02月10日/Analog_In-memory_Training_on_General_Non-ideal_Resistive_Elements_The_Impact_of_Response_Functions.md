# 模拟存内训练在一般非理想电阻元件中的应用及其响应函数的影响

发布时间：2025年02月10日

`其他

理由：这篇论文主要讨论了模拟内存计算（AIMC）在大型视觉或语言模型训练中的应用，特别是AIMC硬件中的权重表示和更新机制。它深入研究了响应函数对训练动态的影响，并提出了一种新的残差学习算法来解决训练中的问题。虽然涉及大型模型的训练，但其重点在于硬件和算法优化，而不是大型语言模型的应用或理论本身，因此归类为其他。` `计算硬件` `机器学习`

> Analog In-memory Training on General Non-ideal Resistive Elements: The Impact of Response Functions

# 摘要

> 面对大型视觉或语言模型训练与部署成本的急剧攀升，模拟内存计算（AIMC）作为一种高效节能的解决方案应运而生。然而，关于AIMC的训练动态研究仍然十分有限。在AIMC硬件中，权重通过电阻元件的电导值表示，并通过连续的电脉冲进行更新。电阻元件对电脉冲的响应直接影响训练动态。本文首先为AIMC硬件上的基于梯度训练构建理论基础，并深入研究响应函数的影响。研究表明，噪声更新和非对称响应函数会对模拟SGD造成负面影响，具体表现为在目标函数上引入隐式惩罚项。为解决这一问题，我们提出了一种名为Tiki-Taka的残差学习算法，通过双层优化主阵列和残差阵列，精确收敛到一个临界点。这一结论通过仿真验证，证实了我们的理论分析。


> As the economic and environmental costs of training and deploying large vision or language models increase dramatically, analog in-memory computing (AIMC) emerges as a promising energy-efficient solution. However, the training perspective, especially its training dynamic, is underexplored. In AIMC hardware, the trainable weights are represented by the conductance of resistive elements and updated using consecutive electrical pulses. Among all the physical properties of resistive elements, the response to the pulses directly affects the training dynamics. This paper first provides a theoretical foundation for gradient-based training on AIMC hardware and studies the impact of response functions. We demonstrate that noisy update and asymmetric response functions negatively impact Analog SGD by imposing an implicit penalty term on the objective. To overcome the issue, Tiki-Taka, a residual learning algorithm, converges exactly to a critical point by optimizing a main array and a residual array bilevelly. The conclusion is supported by simulations validating our theoretical insights.

[Arxiv](https://arxiv.org/abs/2502.06309)