# # LLM-Flock：基于大型语言模型和影响力共识的去中心化多机器人编队

发布时间：2025年05月10日

`LLM应用` `机器人技术` `机器人编队`

> LLM-Flock: Decentralized Multi-Robot Flocking via Large Language Models and Influence-Based Consensus

# 摘要

> 大型语言模型（LLMs）近年来发展迅速，在问题理解和推理方面表现出强大的能力。受到这些进展的启发，研究人员开始探索将LLMs作为去中心化决策者用于多机器人编队控制。然而，先前的研究表明，直接将LLMs应用于此类任务通常会导致不稳定和不一致的行为，机器人可能会因幻觉推理、逻辑不一致和有限的协调意识而崩溃到它们的位置中心或完全分散。为了解决这些问题，我们提出了一种创新性框架，将LLMs与基于影响的计划共识协议相结合。在此框架中，每个机器人独立地使用自己的LLM生成向期望编队的局部计划。随后，机器人通过一种去中心化的共识协议对它们的计划进行迭代优化，该协议考虑了它们对邻近机器人施加的影响。这一过程以完全去中心化的方式推动系统向一致且稳定的集群编队发展。我们通过全面模拟评估了我们的方法，涉及最新闭源LLMs（如o3-mini、Claude 3.5）和开源模型（如Llama3.1-405b、Qwen-Max、DeepSeek-R1）。结果显示，与之前的基于LLM的方法相比，我们在稳定性、收敛性和适应性方面取得了显著提升。我们进一步在Crazyflie无人机的物理团队上验证了我们的框架，证明了其在现实世界多机器人系统中的实际可行性和有效性。

> Large Language Models (LLMs) have advanced rapidly in recent years, demonstrating strong capabilities in problem comprehension and reasoning. Inspired by these developments, researchers have begun exploring the use of LLMs as decentralized decision-makers for multi-robot formation control. However, prior studies reveal that directly applying LLMs to such tasks often leads to unstable and inconsistent behaviors, where robots may collapse to the centroid of their positions or diverge entirely due to hallucinated reasoning, logical inconsistencies, and limited coordination awareness. To overcome these limitations, we propose a novel framework that integrates LLMs with an influence-based plan consensus protocol. In this framework, each robot independently generates a local plan toward the desired formation using its own LLM. The robots then iteratively refine their plans through a decentralized consensus protocol that accounts for their influence on neighboring robots. This process drives the system toward a coherent and stable flocking formation in a fully decentralized manner. We evaluate our approach through comprehensive simulations involving both state-of-the-art closed-source LLMs (e.g., o3-mini, Claude 3.5) and open-source models (e.g., Llama3.1-405b, Qwen-Max, DeepSeek-R1). The results show notable improvements in stability, convergence, and adaptability over previous LLM-based methods. We further validate our framework on a physical team of Crazyflie drones, demonstrating its practical viability and effectiveness in real-world multi-robot systems.

[Arxiv](https://arxiv.org/abs/2505.06513)