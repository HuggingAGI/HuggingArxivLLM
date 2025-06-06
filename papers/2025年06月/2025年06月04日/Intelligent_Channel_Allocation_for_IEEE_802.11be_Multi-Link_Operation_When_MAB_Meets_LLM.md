# # 智能信道分配在 IEEE 802.11be 多链路操作中的应用：当多臂老虎机算法遇见大型语言模型

发布时间：2025年06月04日

`其他` `网络优化`

> Intelligent Channel Allocation for IEEE 802.11be Multi-Link Operation: When MAB Meets LLM

# 摘要

> WiFi网络在全球范围内实现了无缝通信和数据交换的巨大成功。IEEE 802.11be标准（即WiFi 7）引入了多链路操作（MLO），这一开创性功能使设备能够跨不同频段和信道建立多个同时连接。尽管MLO在提升网络吞吐量和降低延迟方面潜力巨大，但在密集网络环境中，它带来了信道分配的重大挑战。当前研究主要集中在静态WiFi 7网络配置的性能分析和吞吐量优化上。本文则聚焦于具有MLO功能的密集WiFi 7网络中的动态信道分配问题。我们将其建模为一个组合优化问题，并引入了新颖的网络性能分析机制。鉴于缺乏先验网络信息，我们采用多臂老虎机（MAB）框架进行在线学习，以优化信道分配。我们提出的最佳臂识别增强的蒙特卡洛树搜索（BAI-MCTS）算法，包含严格的理论分析，提供了样本复杂度和错误概率的上限。为了进一步降低样本复杂度并提升泛化能力，我们提出了LLM-BAI-MCTS，这是一种通过将大型语言模型（LLM）与BAI-MCTS相结合的智能算法。数值结果表明，BAI-MCTS算法在达到98%最优值时，其收敛速度比现有最先进算法快约50.44%。特别地，在密集网络中，LLM-BAI-MCTS算法的收敛速度提高了63.32%以上。

> WiFi networks have achieved remarkable success in enabling seamless communication and data exchange worldwide. The IEEE 802.11be standard, known as WiFi 7, introduces Multi-Link Operation (MLO), a groundbreaking feature that enables devices to establish multiple simultaneous connections across different bands and channels. While MLO promises substantial improvements in network throughput and latency reduction, it presents significant challenges in channel allocation, particularly in dense network environments. Current research has predominantly focused on performance analysis and throughput optimization within static WiFi 7 network configurations. In contrast, this paper addresses the dynamic channel allocation problem in dense WiFi 7 networks with MLO capabilities. We formulate this challenge as a combinatorial optimization problem, leveraging a novel network performance analysis mechanism. Given the inherent lack of prior network information, we model the problem within a Multi-Armed Bandit (MAB) framework to enable online learning of optimal channel allocations. Our proposed Best-Arm Identification-enabled Monte Carlo Tree Search (BAI-MCTS) algorithm includes rigorous theoretical analysis, providing upper bounds for both sample complexity and error probability. To further reduce sample complexity and enhance generalizability across diverse network scenarios, we put forth LLM-BAI-MCTS, an intelligent algorithm for the dynamic channel allocation problem by integrating the Large Language Model (LLM) into the BAI-MCTS algorithm. Numerical results demonstrate that the BAI-MCTS algorithm achieves a convergence rate approximately $50.44\%$ faster than the state-of-the-art algorithms when reaching $98\%$ of the optimal value. Notably, the convergence rate of the LLM-BAI-MCTS algorithm increases by over $63.32\%$ in dense networks.

[Arxiv](https://arxiv.org/abs/2506.04594)