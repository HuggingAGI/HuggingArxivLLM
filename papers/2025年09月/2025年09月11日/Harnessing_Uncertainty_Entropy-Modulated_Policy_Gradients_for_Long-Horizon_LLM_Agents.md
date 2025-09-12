# 驾驭不确定性：面向长时程LLM智能体的熵调制策略梯度

发布时间：2025年09月11日

`强化学习` `基础理论`

> Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents

# 摘要

> 在长期任务中，基于大型语言模型（LLMs）的新一代智能体面临一大难题：稀疏的结果导向型奖励难以对中间步骤进行功劳分配。以往方法多聚焦于构建密集奖励信号以引导学习，具体包括传统强化学习技术（如逆强化学习）或借助过程奖励模型提供逐步反馈。本文指出LLMs学习动态中的核心问题：策略梯度的幅度与熵存在内在耦合，这会导致对自信正确动作的更新低效且幅度小，而对不确定动作的大幅更新则可能失稳。为此，我们提出熵调制策略梯度（EMPG）框架，该框架基于逐步不确定性和最终任务结果重新校准学习信号。EMPG会放大对自信正确动作的更新，惩罚自信错误，并减弱不确定步骤的更新以稳定探索过程。我们还引入未来清晰度奖励项，激励智能体探索更具可预测性的解决方案路径。通过在WebShop、ALFWorld和Deep Search这三个高难度智能体任务上的全面实验，结果表明EMPG性能提升显著，且大幅优于现有的强策略梯度基线。项目页面：https://empgseed-seed.github.io/

> In long-horizon tasks, recent agents based on Large Language Models (LLMs) face a significant challenge that sparse, outcome-based rewards make it difficult to assign credit to intermediate steps. Previous methods mainly focus on creating dense reward signals to guide learning, either through traditional reinforcement learning techniques like inverse reinforcement learning or by using Process Reward Models for step-by-step feedback. In this paper, we identify a fundamental problem in the learning dynamics of LLMs: the magnitude of policy gradients is inherently coupled with the entropy, which leads to inefficient small updates for confident correct actions and potentially destabilizes large updates for uncertain ones. To resolve this, we propose Entropy-Modulated Policy Gradients (EMPG), a framework that re-calibrates the learning signal based on step-wise uncertainty and the final task outcome. EMPG amplifies updates for confident correct actions, penalizes confident errors, and attenuates updates from uncertain steps to stabilize exploration. We further introduce a bonus term for future clarity that encourages agents to find more predictable solution paths. Through comprehensive experiments on three challenging agent tasks, WebShop, ALFWorld, and Deep Search, we demonstrate that EMPG achieves substantial performance gains and significantly outperforms strong policy gradient baselines. Project page is at https://empgseed-seed.github.io/

[Arxiv](https://arxiv.org/abs/2509.09265)