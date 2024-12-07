# 多模态 LLM 借助费希尔信息展开引导探索与主动映射

发布时间：2024年12月04日

`Agent` `具身智能` `3D 数据集`

> Multimodal LLM Guided Exploration and Active Mapping using Fisher Information

# 摘要

> 我们呈现了一个主动映射系统，它能借助 3D 高斯喷溅（3DGS）表示来规划长期的探索目标和短期行动。现有的方法，要么未充分利用多模态大型语言模型（LLM）的最新成果，要么未考虑定位不确定性这一关键挑战，而这在具身智能体中至关重要。我们提议采用多模态 LLM 进行长期规划，并结合我们基于信息的算法来做详细的运动规划。凭借 3DGS 表示所带来的高质量视图合成，我们的方法从语义角度将多模态 LLM 用作零样本规划器，以达成长期探索目标。同时，我们还引入了一种能感知不确定性的路径提议与选择算法，该算法平衡了在环境中最大化信息增益和最小化定位误差成本这两个目标。在 Gibson 和 Habitat-Matterport 3D 数据集上开展的实验表明，所提方法取得了最先进的成果。

> We present an active mapping system that could plan for long-horizon exploration goals and short-term actions with a 3D Gaussian Splatting (3DGS) representation. Existing methods either did not take advantage of recent developments in multimodal Large Language Models (LLM) or did not consider challenges in localization uncertainty, which is critical in embodied agents. We propose employing multimodal LLMs for long-horizon planning in conjunction with detailed motion planning using our information-based algorithm. By leveraging high-quality view synthesis from our 3DGS representation, our method employs a multimodal LLM as a zero-shot planner for long-horizon exploration goals from the semantic perspective. We also introduce an uncertainty-aware path proposal and selection algorithm that balances the dual objectives of maximizing the information gain for the environment while minimizing the cost of localization errors. Experiments conducted on the Gibson and Habitat-Matterport 3D datasets demonstrate state-of-the-art results of the proposed method.

[Arxiv](https://arxiv.org/abs/2410.17422)