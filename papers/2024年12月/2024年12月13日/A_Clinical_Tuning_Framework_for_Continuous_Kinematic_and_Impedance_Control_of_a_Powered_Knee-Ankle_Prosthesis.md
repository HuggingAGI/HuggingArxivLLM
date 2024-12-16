# 一个针对动力膝-踝假肢连续运动学及阻抗控制的临床调优框架

发布时间：2024年12月13日

`其他`

> A Clinical Tuning Framework for Continuous Kinematic and Impedance Control of a Powered Knee-Ankle Prosthesis

# 摘要

> 目标：配置假肢是适配流程中的关键环节，然而在临床环境中，多模式动力膝踝假肢的个性化实现往往极为复杂。本文不仅开发了针对可变倾斜行走和坐立转换的混合运动学-阻抗控制器个性化的技术手段，还推出了一个直观的临床调谐接口（CTI），方便假肢技师直接修改控制器的行为。
  方法：借助已有的预测运动步态个性的方法以及新的动力学个性并行策略，我们仅运用平地行走的调谐特性来实现关节运动学和阻抗的连续相/任务模型的个性化。为运用此方法，我们研发了一个 CTI，能将常见的临床调谐参数转化为模型调整。随后，我们开展了一个涉及膝上截肢者的案例研究，在模拟的临床环节中，假肢技师对假肢进行了迭代调谐，涵盖行走和坐立转换。
  结果：假肢技师在不到 20 分钟内就完成了多活动假肢控制器的全部调谐。每次调谐迭代（即观察、参数调整和模型再处理），行走平均耗时 2 分钟，坐立平均耗时 1 分钟。调谐后的行为变化在假肢的指令扭矩中得到了恰当体现，无论是在调谐任务中，还是在未调谐任务（倾斜）中。
  结论：CTI 借助健全人的趋势，高效地实现了各类行走任务和坐立转换的个性化。案例研究验证了 CTI 调谐方法，并展现了动力膝踝假肢在临床上可行所必需的效率。

> Objective: Configuring a prosthetic leg is an integral part of the fitting process, but the personalization of a multi-modal powered knee-ankle prosthesis is often too complex to realize in a clinical environment. This paper develops both the technical means to individualize a hybrid kinematic-impedance controller for variable-incline walking and sit-stand transitions, and an intuitive Clinical Tuning Interface (CTI) that allows prosthetists to directly modify the controller behavior.
  Methods: Utilizing an established method for predicting kinematic gait individuality alongside a new parallel approach for kinetic individuality, we applied tuned characteristics exclusively from level-ground walking to personalize continuous-phase/task models of joint kinematics and impedance. To take advantage of this method, we developed a CTI that translates common clinical tuning parameters into model adjustments. We then conducted a case study involving an above-knee amputee participant where a prosthetist iteratively tuned the prosthesis in a simulated clinical session involving walking and sit-stand transitions.
  Results: The prosthetist fully tuned the multi-activity prosthesis controller in under 20 min. Each iteration of tuning (i.e., observation, parameter adjustment, and model reprocessing) took 2 min on average for walking and 1 min on average for sit-stand. The tuned behavior changes were appropriately manifested in the commanded prosthesis torques, both at the tuned tasks and across untuned tasks (inclines).
  Conclusion: The CTI leveraged able-bodied trends to efficiently personalize a wide array of walking tasks and sit-stand transitions. A case-study validated the CTI tuning method and demonstrated the efficiency necessary for powered knee-ankle prostheses to become clinically viable.

[Arxiv](https://arxiv.org/abs/2412.10154)