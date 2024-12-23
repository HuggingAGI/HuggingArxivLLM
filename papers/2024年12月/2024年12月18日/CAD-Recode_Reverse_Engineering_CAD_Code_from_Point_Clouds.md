# CAD-Recode：由点云实现 CAD 代码的逆向工程

发布时间：2024年12月18日

`LLM应用` `计算机辅助设计` `逆向工程`

> CAD-Recode: Reverse Engineering CAD Code from Point Clouds

# 摘要

> 计算机辅助设计（CAD）模型通常是通过依次绘制参数化草图并应用 CAD 操作来构建 3D 模型的。3D CAD 逆向工程的难题在于从点云等 3D 表示中重构草图和 CAD 操作序列。在本文中，我们从三个层面做出新贡献来应对此挑战：CAD 序列表示、网络设计和数据集。具体而言，我们把 CAD 草图-拉伸序列表示为 Python 代码。所提出的 CAD-Recode 能将点云转化为 Python 代码，执行该代码即可重建 CAD 模型。借助预先训练的大型语言模型（LLMs）对 Python 代码的了解，我们用相对较小的 LLM 作为 CAD-Recode 的解码器，并与轻量级点云投影仪相结合。CAD-Recode 仅在提议的包含一百万个不同 CAD 序列的合成数据集上训练。CAD-Recode 在三个数据集上的表现远超现有方法，且所需输入点更少。尤为突出的是，在 DeepCAD 和 Fusion360 数据集上，其平均倒角距离比前沿方法低 10 倍。此外，我们证明我们的 CAD Python 代码输出能被现成的 LLMs 解读，从而能从点云进行 CAD 编辑和 CAD 特定的问答。

> Computer-Aided Design (CAD) models are typically constructed by sequentially drawing parametric sketches and applying CAD operations to obtain a 3D model. The problem of 3D CAD reverse engineering consists of reconstructing the sketch and CAD operation sequences from 3D representations such as point clouds. In this paper, we address this challenge through novel contributions across three levels: CAD sequence representation, network design, and dataset. In particular, we represent CAD sketch-extrude sequences as Python code. The proposed CAD-Recode translates a point cloud into Python code that, when executed, reconstructs the CAD model. Taking advantage of the exposure of pre-trained Large Language Models (LLMs) to Python code, we leverage a relatively small LLM as a decoder for CAD-Recode and combine it with a lightweight point cloud projector. CAD-Recode is trained solely on a proposed synthetic dataset of one million diverse CAD sequences. CAD-Recode significantly outperforms existing methods across three datasets while requiring fewer input points. Notably, it achieves 10 times lower mean Chamfer distance than state-of-the-art methods on DeepCAD and Fusion360 datasets. Furthermore, we show that our CAD Python code output is interpretable by off-the-shelf LLMs, enabling CAD editing and CAD-specific question answering from point clouds.

[Arxiv](https://arxiv.org/abs/2412.14042)