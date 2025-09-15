# DiffAero：面向高效四旋翼策略学习的GPU加速可微分仿真框架

发布时间：2025年09月12日

`强化学习` `交通运输`

> DiffAero: A GPU-Accelerated Differentiable Simulation Framework for Efficient Quadrotor Policy Learning

# 摘要

> 本文推出DiffAero——一款轻量级、GPU加速的完全可微仿真框架，专为高效学习四旋翼控制策略而设计。该框架支持环境级与智能体级并行计算，集成多种动力学模型、可定制传感器组（含IMU、深度相机及LiDAR），并将多样化飞行任务融入统一的GPU原生训练接口。通过在GPU上对物理与渲染过程全并行处理，DiffAero彻底消除CPU-GPU数据传输瓶颈，仿真吞吐量实现数量级飞跃。相较于现有模拟器，DiffAero不仅提供高性能仿真能力，更成为探索可微与混合学习算法的研究平台。大量基准测试与真实飞行实验证实，DiffAero结合混合学习算法，能在消费级硬件上仅用数小时便学习到鲁棒的飞行策略。代码已开源至https://github.com/flyingbitac/diffaero。

> This letter introduces DiffAero, a lightweight, GPU-accelerated, and fully differentiable simulation framework designed for efficient quadrotor control policy learning. DiffAero supports both environment-level and agent-level parallelism and integrates multiple dynamics models, customizable sensor stacks (IMU, depth camera, and LiDAR), and diverse flight tasks within a unified, GPU-native training interface. By fully parallelizing both physics and rendering on the GPU, DiffAero eliminates CPU-GPU data transfer bottlenecks and delivers orders-of-magnitude improvements in simulation throughput. In contrast to existing simulators, DiffAero not only provides high-performance simulation but also serves as a research platform for exploring differentiable and hybrid learning algorithms. Extensive benchmarks and real-world flight experiments demonstrate that DiffAero and hybrid learning algorithms combined can learn robust flight policies in hours on consumer-grade hardware. The code is available at https://github.com/flyingbitac/diffaero.

[Arxiv](https://arxiv.org/abs/2509.10247)