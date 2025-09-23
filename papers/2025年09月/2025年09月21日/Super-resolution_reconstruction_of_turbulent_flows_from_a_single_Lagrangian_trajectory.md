# 基于单个拉格朗日轨迹的湍流超分辨率重建

发布时间：2025年09月21日

`其他` `基础理论`

> Super-resolution reconstruction of turbulent flows from a single Lagrangian trajectory

# 摘要

> 我们研究了如何利用主动迁移拉格朗日粒子的轨迹数据重建湍流场，并提出了深度学习模型Track-to-Flow（T2F）。该模型以视觉Transformer为编码器捕捉单粒子轨迹的时空特征，搭配卷积神经网络解码器完成流场重建。为提升T2F的物理一致性，我们进一步引入受物理信息神经网络（PINN）启发的物理信息损失函数，得到变体模型T2F+PINN。我们首先在雷诺数为【数学公式】的层流圆柱尾迹流中对两模型开展概念验证：T2F的速度重建精度与现有方法相当，而T2F+PINN相比T2F降低了涡量重建的归一化误差。接着，将模型应用于瑞利数【数学公式】、普朗特数【数学公式】的湍流瑞利-贝纳尔对流，结果表明T2F可准确重建速度场与温度场，T2F+PINN则进一步提升了温度梯度、涡量及【数学公式】值等梯度相关物理量的重建精度，相比T2F最大提升约60%。总体而言，T2F更适用于原始流场变量重建，T2F+PINN则在梯度相关物理量重建中优势显著。我们的模型为基于单拉格朗日轨迹实现高精度流场重建提供了前景广阔的新方法。

> We studied the reconstruction of turbulent flow fields from trajectory data recorded by actively migrating Lagrangian agents. We propose a deep learning model, Track-to-Flow (T2F), which employs a Vision Transformer as an encoder to capture the spatiotemporal features of a single agent trajectory, and a convolutional neural network as the decoder to reconstruct the flow field. To enhance the physical consistency of the T2F model, we further incorporate a physics-informed loss function inspired by the framework of Physics-Informed Neural Network (PINN), yielding a variant model referred to as T2F+PINN. We first evaluate both models in a laminar cylinder wake flow at a Reynolds number of $Re = 800$ as a proof-of-concept. The results show that the T2F model achieves velocity reconstruction accuracy comparable to existing flow reconstruction methods, while the T2F+PINN model reduces the normalized error in vorticity reconstruction relative to the T2F model. We then apply the models in a turbulent Rayleigh-Bénard convection at a Rayleigh number of $Ra = 10^{8}$ and a Prandtl number of $Pr = 0.71$. The results show that the T2F model accurately reconstructs both the velocity and temperature fields, whereas the T2F+PINN model further improves the reconstruction accuracy of gradient-related physical quantities, such as temperature gradients, vorticity, and the $Q$ value, with a maximum improvement of approximately 60\% compared to the T2F model. Overall, the T2F model is better suited for reconstructing primitive flow variables, while the T2F+PINN model provides advantages in reconstructing gradient-related quantities. Our models open a promising avenue for accurate flow reconstruction from a single Lagrangian trajectory.

[Arxiv](https://arxiv.org/abs/2509.17109)