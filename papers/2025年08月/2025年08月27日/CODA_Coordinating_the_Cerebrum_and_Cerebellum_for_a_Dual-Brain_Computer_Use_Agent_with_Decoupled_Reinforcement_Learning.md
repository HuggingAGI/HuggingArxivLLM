# CODA：协调大脑与小脑，构建结合解耦强化学习的双脑计算机使用智能体

发布时间：2025年08月27日

`Agent` `基础理论`

> CODA: Coordinating the Cerebrum and Cerebellum for a Dual-Brain Computer Use Agent with Decoupled Reinforcement Learning

# 摘要

> 图形用户界面（GUI）的自主智能体在科学计算等专业领域面临严峻挑战，这些领域对长程规划与精准执行均有极高要求。现有方法陷入两难困境：通用智能体擅长规划却执行拉垮，专业智能体则恰恰相反。近年的组合框架虽尝试通过规划器与执行器的结合弥合这一鸿沟，但多为静态且不可训练，无法从经验中学习适应——在科学领域高质量数据稀缺的背景下，这成为严重局限。为此，我们提出了CODA——一种全新的可训练组合框架，它整合通用规划器（大脑）与专业执行器（小脑），并通过专属的两阶段训练流程实现优化。第一阶段（专业化阶段）采用解耦GRPO方法，为每个科学应用单独训练专家规划器，通过少量任务轨迹进行引导学习；第二阶段（泛化阶段）则汇集所有专业专家的成功轨迹，构建综合数据集，用于最终规划器的监督微调。这让CODA兼具稳健的执行能力与跨域泛化能力。在ScienceBoard基准测试的四个高难度应用中评估后发现，CODA性能远超基线模型，成为开源模型中的最新技术标杆。

> Autonomous agents for Graphical User Interfaces (GUIs) face significant challenges in specialized domains such as scientific computing, where both long-horizon planning and precise execution are required. Existing approaches suffer from a trade-off: generalist agents excel at planning but perform poorly in execution, while specialized agents demonstrate the opposite weakness. Recent compositional frameworks attempt to bridge this gap by combining a planner and an actor, but they are typically static and non-trainable, which prevents adaptation from experience. This is a critical limitation given the scarcity of high-quality data in scientific domains. To address these limitations, we introduce CODA, a novel and trainable compositional framework that integrates a generalist planner (Cerebrum) with a specialist executor (Cerebellum), trained via a dedicated two-stage pipeline. In the first stage, Specialization, we apply a decoupled GRPO approach to train an expert planner for each scientific application individually, bootstrapping from a small set of task trajectories. In the second stage, Generalization, we aggregate all successful trajectories from the specialized experts to build a consolidated dataset, which is then used for supervised fine-tuning of the final planner. This equips CODA with both robust execution and cross-domain generalization. Evaluated on four challenging applications from the ScienceBoard benchmark, CODA significantly outperforms baselines and establishes a new state of the art among open-source models.

[Arxiv](https://arxiv.org/abs/2508.20096)