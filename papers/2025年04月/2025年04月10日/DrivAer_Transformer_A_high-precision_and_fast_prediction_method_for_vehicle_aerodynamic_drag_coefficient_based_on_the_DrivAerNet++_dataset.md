# 基于 DrivAerNet++ 数据集的高精度快速车辆气动阻力系数预测方法研究：DrivAer Transformer 模型

发布时间：2025年04月10日

`其他` `汽车工程` `车辆设计`

> DrivAer Transformer: A high-precision and fast prediction method for vehicle aerodynamic drag coefficient based on the DrivAerNet++ dataset

# 摘要

> 目前，基于深度学习的方法在气动性能评估方面表现优异，大幅缩短了传统计算流体动力学（CFD）模拟的时间和成本。然而，面对复杂三维（3D）车辆模型时，大型数据集和训练资源的缺乏，加上不同车辆模型几何形状的多样性和复杂性，限制了现有网络的预测准确性和通用性，难以满足当前生产需求。鉴于Transformer模型在自然语言处理领域的成功及其在图像处理领域的潜力，本研究提出了一种名为DrivAer Transformer (DAT)的创新点云学习框架。DAT采用包含工业标准3D车辆形状高保真CFD数据的DrivAerNet++数据集，可直接从3D网格中精确估计空气阻力，突破了传统方法如2D图像渲染或符号距离场（SDF）的局限。DAT实现了快速精准的阻力预测，推动了气动评估流程的革新，为将数据驱动方法引入汽车设计奠定了基础。该框架有望加速车辆设计流程，显著提升开发效率。

> At the current stage, deep learning-based methods have demonstrated excellent capabilities in evaluating aerodynamic performance, significantly reducing the time and cost required for traditional computational fluid dynamics (CFD) simulations. However, when faced with the task of processing extremely complex three-dimensional (3D) vehicle models, the lack of large-scale datasets and training resources, coupled with the inherent diversity and complexity of the geometry of different vehicle models, means that the prediction accuracy and versatility of these networks are still not up to the level required for current production. In view of the remarkable success of Transformer models in the field of natural language processing and their strong potential in the field of image processing, this study innovatively proposes a point cloud learning framework called DrivAer Transformer (DAT). The DAT structure uses the DrivAerNet++ dataset, which contains high-fidelity CFD data of industrial-standard 3D vehicle shapes. enabling accurate estimation of air drag directly from 3D meshes, thus avoiding the limitations of traditional methods such as 2D image rendering or signed distance fields (SDF). DAT enables fast and accurate drag prediction, driving the evolution of the aerodynamic evaluation process and laying the critical foundation for introducing a data-driven approach to automotive design. The framework is expected to accelerate the vehicle design process and improve development efficiency.

[Arxiv](https://arxiv.org/abs/2504.08217)