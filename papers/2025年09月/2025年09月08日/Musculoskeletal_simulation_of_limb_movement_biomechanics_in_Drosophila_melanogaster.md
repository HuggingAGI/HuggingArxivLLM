# 黑腹果蝇肢体运动生物力学的肌肉骨骼模拟

发布时间：2025年09月08日

`其他` `基础理论`

> Musculoskeletal simulation of limb movement biomechanics in Drosophila melanogaster

# 摘要

> 计算模型对于深入理解神经、生物力学和物理系统如何相互作用以协调动物行为至关重要。尽管已获得黑腹果蝇中枢神经系统、肌肉系统及外骨骼的近乎完整重建，但基于解剖学和物理学的果蝇腿部肌肉模型仍未建立——而这类模型正是连接运动神经元活动与关节运动的不可或缺的桥梁。在此，我们首次提出果蝇腿部的3D数据驱动肌肉骨骼模型，并在OpenSim和MuJoCo两种仿真环境中实现。该模型基于多个固定标本的高分辨率X射线扫描，采用Hill型肌肉表示。我们还提出了利用形态学成像数据构建肌肉模型、并优化果蝇特有未知肌肉参数的流程。随后，我们将该肌肉骨骼模型与果蝇行为时的详细3D姿态估计数据相结合，在OpenSim中实现了肌肉驱动的行为回放。通过模拟不同行走和梳理行为中的肌肉活动，我们预测出可实验验证的协调肌肉协同作用。此外，在MuJoCo中训练模仿学习策略时，我们测试了不同被动关节特性对学习速度的影响，发现阻尼和刚度可促进学习。总体而言，该模型能够在实验上易于操作的模式生物中研究运动控制，为深入理解生物力学如何参与复杂肢体运动的产生提供了见解。此外，该模型还可用于控制具身人工智能体，在仿真环境中生成自然且柔顺的运动。

> Computational models are critical to advance our understanding of how neural, biomechanical, and physical systems interact to orchestrate animal behaviors. Despite the availability of near-complete reconstructions of the Drosophila melanogaster central nervous system, musculature, and exoskeleton, anatomically and physically grounded models of fly leg muscles are still missing. These models provide an indispensable bridge between motor neuron activity and joint movements. Here, we introduce the first 3D, data-driven musculoskeletal model of Drosophila legs, implemented in both OpenSim and MuJoCo simulation environments. Our model incorporates a Hill-type muscle representation based on high-resolution X-ray scans from multiple fixed specimens. We present a pipeline for constructing muscle models using morphological imaging data and for optimizing unknown muscle parameters specific to the fly. We then combine our musculoskeletal models with detailed 3D pose estimation data from behaving flies to achieve muscle-actuated behavioral replay in OpenSim. Simulations of muscle activity across diverse walking and grooming behaviors predict coordinated muscle synergies that can be tested experimentally. Furthermore, by training imitation learning policies in MuJoCo, we test the effect of different passive joint properties on learning speed and find that damping and stiffness facilitate learning. Overall, our model enables the investigation of motor control in an experimentally tractable model organism, providing insights into how biomechanics contribute to generation of complex limb movements. Moreover, our model can be used to control embodied artificial agents to generate naturalistic and compliant locomotion in simulated environments.

[Arxiv](https://arxiv.org/abs/2509.06426)