# ProgRM：通过进度奖励机制打造更优秀的GUI代理

发布时间：2025年05月23日

`Agent` `软件测试和自动化`

> ProgRM: Build Better GUI Agents with Progress Rewards

# 摘要

> 基于LLM的GUI代理正深刻改变我们的日常生活。然而，现有代理面临高质量训练数据匮乏的挑战，主要源于轨迹收集和奖励标注的难度。现有研究尝试利用LLMs收集轨迹用于模仿学习，或提供在线强化学习的奖励信号。然而，现有的成果奖励模型（ORM）存在两大问题：无法提供精细反馈，且可能过度惩罚最终失败轨迹中的有价值步骤。为解决这些问题，我们提出了进度奖励模型（ProgRM），通过在在线训练中为每一步预测任务完成进度，提供密集且信息丰富的中间奖励。针对进度奖励标签标注的难题，我们设计了一种高效的基于最长公共子序列（LCS）的自标注算法，用于识别轨迹中的关键步骤并分配进度标签。通过广泛的实验和分析，ProgRM表现出显著优势。实验结果表明，使用ProgRM训练的代理优于现有专有LLMs和ORM训练的代理，充分证明了ProgRM的有效性。实验代码将在接受后公开发布。

> LLM-based (Large Language Model) GUI (Graphical User Interface) agents can potentially reshape our daily lives significantly. However, current LLM-based GUI agents suffer from the scarcity of high-quality training data owing to the difficulties of trajectory collection and reward annotation. Existing works have been exploring LLMs to collect trajectories for imitation learning or to offer reward signals for online RL training. However, the Outcome Reward Model (ORM) used in existing works cannot provide finegrained feedback and can over-penalize the valuable steps in finally failed trajectories. To this end, we propose Progress Reward Model (ProgRM) to provide dense informative intermediate rewards by predicting a task completion progress for each step in online training. To handle the challenge of progress reward label annotation, we further design an efficient LCS-based (Longest Common Subsequence) self-annotation algorithm to discover the key steps in trajectories and assign progress labels accordingly. ProgRM is evaluated with extensive experiments and analyses. Actors trained with ProgRM outperform leading proprietary LLMs and ORM-trained actors, illustrating the effectiveness of ProgRM. The codes for experiments will be made publicly available upon acceptance.

[Arxiv](https://arxiv.org/abs/2505.18121)