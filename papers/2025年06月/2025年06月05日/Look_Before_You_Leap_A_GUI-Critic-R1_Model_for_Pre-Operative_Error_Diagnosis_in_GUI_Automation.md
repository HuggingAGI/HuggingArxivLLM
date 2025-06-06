# 先看后行：一种用于 GUI 自动化中的操作前错误诊断模型 GUI-Critic-R1

发布时间：2025年06月05日

`LLM应用` `人工智能` `软件工程`

> Look Before You Leap: A GUI-Critic-R1 Model for Pre-Operative Error Diagnosis in GUI Automation

# 摘要

> 近年来，多模态大语言模型（MLLMs）在多模态推理任务中得到了广泛应用，特别是在图形用户界面（GUI）自动化领域。与通用的离线多模态任务不同，GUI自动化需要在在线交互式环境中逐步决策，且每一步的决策错误容忍度较低。任何失误都可能导致过程的累积性中断，甚至引发删除或支付等不可逆的结果。为解决这一问题，我们提出了一种预操作批评机制，通过推理行动的潜在结果和正确性，在实际执行前提供有效反馈。具体而言，我们采用基于建议感知梯度相对策略优化（S-GRPO）的策略，构建了 GUI-Critic-R1 模型，并引入新型建议奖励以增强反馈可靠性。此外，我们开发了一种基于推理引导的数据收集管道，创建了 GUI-Critic-Train 和 GUI-Critic-Test，填补了现有 GUI 批评数据的空白。静态实验结果表明，与现有 MLLMs 相比，GUI-Critic-R1 在批评准确性方面具有显著优势。动态评估进一步证实，该模型在 GUI 自动化基准上表现出色，成功率和操作效率均显著提升。

> In recent years, Multimodal Large Language Models (MLLMs) have been extensively utilized for multimodal reasoning tasks, including Graphical User Interface (GUI) automation. Unlike general offline multimodal tasks, GUI automation is executed in online interactive environments, necessitating step-by-step decision-making based on real-time status of the environment. This task has a lower tolerance for decision-making errors at each step, as any mistakes may cumulatively disrupt the process and potentially lead to irreversible outcomes like deletions or payments. To address these issues, we introduce a pre-operative critic mechanism that provides effective feedback prior to the actual execution, by reasoning about the potential outcome and correctness of actions. Specifically, we propose a Suggestion-aware Gradient Relative Policy Optimization (S-GRPO) strategy to construct our pre-operative critic model GUI-Critic-R1, incorporating a novel suggestion reward to enhance the reliability of the model's feedback. Furthermore, we develop a reasoning-bootstrapping based data collection pipeline to create a GUI-Critic-Train and a GUI-Critic-Test, filling existing gaps in GUI critic data. Static experiments on the GUI-Critic-Test across both mobile and web domains reveal that our GUI-Critic-R1 offers significant advantages in critic accuracy compared to current MLLMs. Dynamic evaluation on GUI automation benchmark further highlights the effectiveness and superiority of our model, as evidenced by improved success rates and operational efficiency.

[Arxiv](https://arxiv.org/abs/2506.04614)