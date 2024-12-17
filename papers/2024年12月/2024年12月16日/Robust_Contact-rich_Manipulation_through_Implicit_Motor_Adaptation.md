# 通过隐式电机适应达成稳健的接触丰富式操作

发布时间：2024年12月16日

`其他` `机器人` `控制策略`

> Robust Contact-rich Manipulation through Implicit Motor Adaptation

# 摘要

> 接触丰富的操作在人类日常活动中至关重要，可不确定的物理参数给基于模型和无模型的规划及控制带来了重大挑战。解决此挑战的一个可行办法是开发能适应多种参数的策略。领域适应和领域随机化常被用于实现这类策略，但因忽略实例特定信息，往往在新实例的泛化上有所妥协或表现保守。	extit{显式电机适应}通过在线估计系统参数，再从参数增强的基本策略中获取参数条件策略来应对这些问题。然而，它通常依赖精确的系统识别或额外的高质量策略再训练，这对物理参数各异的接触丰富任务构成了巨大挑战。在本研究中，我们提出了	extit{隐式电机适应}，它借助张量分解作为基本策略的隐式表达。给定一个大致估计的参数分布，能通过利用基本策略中张量核的可分离结构高效导出参数条件策略。该框架无需精确的系统估计和策略再训练，同时能保持最优行为和强大的泛化能力。我们提供了验证该方法的理论分析，并通过对三个接触丰富的操作原语进行数值评估予以支持。模拟和真实世界的实验均表明其能够为不同实例生成稳健的策略。

> Contact-rich manipulation plays a vital role in daily human activities, yet uncertain physical parameters pose significant challenges for both model-based and model-free planning and control. A promising approach to address this challenge is to develop policies robust to a wide range of parameters. Domain adaptation and domain randomization are commonly used to achieve such policies but often compromise generalization to new instances or perform conservatively due to neglecting instance-specific information. \textit{Explicit motor adaptation} addresses these issues by estimating system parameters online and then retrieving the parameter-conditioned policy from a parameter-augmented base policy. However, it typically relies on precise system identification or additional high-quality policy retraining, presenting substantial challenges for contact-rich tasks with diverse physical parameters. In this work, we propose \textit{implicit motor adaptation}, which leverages tensor factorization as an implicit representation of the base policy. Given a roughly estimated parameter distribution, the parameter-conditioned policy can be efficiently derived by exploiting the separable structure of tensor cores from the base policy. This framework eliminates the need for precise system estimation and policy retraining while preserving optimal behavior and strong generalization. We provide a theoretical analysis validating this method, supported by numerical evaluations on three contact-rich manipulation primitives. Both simulation and real-world experiments demonstrate its ability to generate robust policies for diverse instances.

[Arxiv](https://arxiv.org/abs/2412.11829)