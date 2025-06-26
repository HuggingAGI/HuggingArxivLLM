# RoboTwin 2.0: 一个用于鲁棒双臂机器人操作的可扩展数据生成器和基准测试，具备强领域随机化能力

发布时间：2025年06月22日

`Agent

理由：这篇论文主要探讨了使用仿真框架和多模态大型语言模型来提升机器人操作能力，属于机器人智能体的应用领域。` `机器人` `人工智能`

> RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation

# 摘要

> 基于仿真的数据合成已成为提升现实世界机器人操作能力的重要范式。然而，现有合成数据集在实现鲁棒双臂操作方面仍存在两大挑战：(1) 缺乏高效且可扩展的新任务数据生成方法；(2) 过于简化的仿真环境无法真实还原现实世界的复杂性。为此，我们推出RoboTwin 2.0，一个可扩展的仿真框架，支持大规模多样化且逼真数据的自动生成，并提供统一的双臂操作评估协议。首先，我们构建了包含147个类别、731个实例的大型物体库RoboTwin-OD，每个实例均标注了语义和操作相关标签。在此基础上，我们开发了一条专家数据合成流水线，结合多模态大型语言模型（MLLMs）与模拟闭环优化，可自动生成任务级执行代码。为提升仿真到现实的迁移效果，RoboTwin 2.0引入了沿五个维度的结构化领域随机化：杂乱程度、光照、背景、桌面高度及语言指令，从而增强数据多样性和策略鲁棒性。我们已在涵盖五种机器人形态的50个双臂任务中实现了该框架的落地，并预先收集了超过10万条领域随机化的专家轨迹。实验结果表明，代码生成成功率提升了10.9%，且在新型现实场景中的泛化能力显著增强。基于我们的数据集微调的VLA模型在未见过的现实场景任务中实现了367%的相对提升（42.0% vs. 9.0%），而仅基于合成数据训练的零样本模型则实现了228%的相对增益，充分展现了无需现实监督的强大泛化能力。我们开源了数据生成器、基准测试、数据集及代码，以支持鲁棒双臂操作的可扩展性研究。

> Simulation-based data synthesis has emerged as a powerful paradigm for enhancing real-world robotic manipulation. However, existing synthetic datasets remain insufficient for robust bimanual manipulation due to two challenges: (1) the lack of an efficient, scalable data generation method for novel tasks, and (2) oversimplified simulation environments that fail to capture real-world complexity. We present RoboTwin 2.0, a scalable simulation framework that enables automated, large-scale generation of diverse and realistic data, along with unified evaluation protocols for dual-arm manipulation. We first construct RoboTwin-OD, a large-scale object library comprising 731 instances across 147 categories, each annotated with semantic and manipulation-relevant labels. Building on this foundation, we develop an expert data synthesis pipeline that combines multimodal large language models (MLLMs) with simulation-in-the-loop refinement to generate task-level execution code automatically. To improve sim-to-real transfer, RoboTwin 2.0 incorporates structured domain randomization along five axes: clutter, lighting, background, tabletop height and language instructions, thereby enhancing data diversity and policy robustness. We instantiate this framework across 50 dual-arm tasks spanning five robot embodiments, and pre-collect over 100,000 domain-randomized expert trajectories. Empirical results show a 10.9% gain in code generation success and improved generalization to novel real-world scenarios. A VLA model fine-tuned on our dataset achieves a 367% relative improvement (42.0% vs. 9.0%) on unseen scene real-world tasks, while zero-shot models trained solely on our synthetic data achieve a 228% relative gain, highlighting strong generalization without real-world supervision. We release the data generator, benchmark, dataset, and code to support scalable research in robust bimanual manipulation.

[Arxiv](https://arxiv.org/abs/2506.18088)