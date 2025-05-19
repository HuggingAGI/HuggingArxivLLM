# 物理信息驱动的卷积长短时记忆（LSTM）统计模型用于流体热力学模拟

发布时间：2025年05月16日

`其他` `大气动力学` `气候科学`

> A Physics-Informed Convolutional Long Short Term Memory Statistical Model for Fluid Thermodynamics Simulations

# 摘要

> 流体热力学在大气动力学、气候科学、工业应用和能源系统中发挥着基础性作用。然而，对这类系统的直接数值模拟（DNS）计算成本极高。为解决这一难题，我们提出了一种针对瑞利-本nard对流（RBC）的新型物理信息增强的时空代理模型。RBC作为典型对流流体运动的代表性案例，我们的方法结合了卷积神经网络进行空间特征提取，以及一种受大型语言模型启发的创新递归架构，包含上下文构建器和序列生成器以捕捉时间动态。通过引入对控制偏微分方程的惩罚，确保了模型的物理可解释性。鉴于湍流对流对初始条件的高度敏感性，我们采用符合性预测框架来量化不确定性。该模型不仅能够复现RBC动力学的关键特征，还大幅降低了计算成本，为长期模拟提供了一种高效替代DNS的解决方案。

> Fluid thermodynamics underpins atmospheric dynamics, climate science, industrial applications, and energy systems. However, direct numerical simulations (DNS) of such systems are computationally prohibitive. To address this, we present a novel physics-informed spatio-temporal surrogate model for Rayleigh-Bénard convection (RBC), a canonical example of convective fluid flow. Our approach combines convolutional neural networks for spatial feature extraction with an innovative recurrent architecture inspired by large language models, comprising a context builder and a sequence generator to capture temporal dynamics. Inference is penalized with respect to the governing partial differential equations to ensure physical interpretability. Given the sensitivity of turbulent convection to initial conditions, we quantify uncertainty using a conformal prediction framework. This model replicates key features of RBC dynamics while significantly reducing computational cost, offering a scalable alternative to DNS for long-term simulations.

[Arxiv](https://arxiv.org/abs/2505.10919)