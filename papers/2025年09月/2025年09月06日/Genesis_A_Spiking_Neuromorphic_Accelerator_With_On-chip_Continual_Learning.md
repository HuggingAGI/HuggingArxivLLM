# Genesis：具备片上持续学习功能的脉冲神经形态加速器

发布时间：2025年09月06日

`其他` `工业与制造`

> Genesis: A Spiking Neuromorphic Accelerator With On-chip Continual Learning

# 摘要

> 持续学习是人工智能体在现实环境中交互的关键能力，指模型在其生命周期中获取并迁移知识的能力。生物大脑在有限的能量和资源预算下运行，却天生具备这些能力。然而在人工系统中实现持续学习能力，会大幅增加内存和计算需求，在资源受限的平台上部署时问题尤为突出。为此，本研究提出了脉冲持续学习加速器Genesis，旨在填补这一空白。该架构支持神经启发机制（如活动依赖的元可塑性），可有效减轻灾难性遗忘；同时整合低精度持续学习参数，并采用自定义数据移动策略以适应稀疏分布的脉冲信号。此外，其创新的内存映射技术将元可塑性参数与突触权重置于同一地址位置，大幅提升了内存访问速度。实验结果表明，在任务无关的split-MNIST基准测试中，Genesis的平均分类准确率达到74.6%；在65nm工艺节点下，其功耗仅为17.08mW。

> Continual learning, the ability to acquire and transfer knowledge through a models lifetime, is critical for artificial agents that interact in real-world environments. Biological brains inherently demonstrate these capabilities while operating within limited energy and resource budgets. Achieving continual learning capability in artificial systems considerably increases memory and computational demands, and even more so when deploying on platforms with limited resources. In this work, Genesis, a spiking continual learning accelerator, is proposed to address this gap. The architecture supports neurally inspired mechanisms, such as activity-dependent metaplasticity, to alleviate catastrophic forgetting. It integrates low-precision continual learning parametersand employs a custom data movement strategy to accommodate the sparsely distributed spikes. Furthermore, the architecture features a memory mapping technique that places metaplasticity parameters and synaptic weights in a single address location for faster memory access. Results show that the mean classification accuracy for Genesis is 74.6% on a task-agnostic split-MNIST benchmark with power consumption of 17.08mW in a 65nm technology node.

[Arxiv](https://arxiv.org/abs/2509.05858)