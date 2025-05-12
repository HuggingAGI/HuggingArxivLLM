# CityNavAgent：结合分层语义规划与全局记忆的空视导航系统

发布时间：2025年05月08日

`LLM应用` `无人机` `人工智能`

> CityNavAgent: Aerial Vision-and-Language Navigation with Hierarchical Semantic Planning and Global Memory

# 摘要

> 无人机视觉语言导航（VLN）要求无人机解读自然语言指令并导航复杂的 urban environments，已成为一个关键的具身AI挑战，连接了人机交互、三维空间推理和现实世界部署。尽管现有的地面VLN代理在室内和室外环境中取得了显著成果，但它们在无人机VLN中表现挣扎，原因在于缺乏预定义的导航图以及长期探索中指数级扩展的动作空间。本研究中，我们提出了一种基于大型语言模型（LLM）的智能体——	extbf{CityNavAgent}，它显著降低了城市无人机VLN的导航复杂性。具体来说，我们设计了一个分层语义规划模块（HSPM），将长期任务分解为不同语义层次的子目标。智能体通过逐步实现这些子目标，利用LLM的不同能力逐步到达目标。此外，我们开发了一个全局记忆模块，将历史轨迹存储到拓扑图中，以简化已访问目标的导航。广泛的基准实验表明，我们的方法实现了最先进的性能，并取得了显著提升。进一步的实验验证了CityNavAgent不同模块在连续城市环境中进行无人机VLN的有效性。代码可在\href{https://github.com/VinceOuti/CityNavAgent}{link}获取。

> Aerial vision-and-language navigation (VLN), requiring drones to interpret natural language instructions and navigate complex urban environments, emerges as a critical embodied AI challenge that bridges human-robot interaction, 3D spatial reasoning, and real-world deployment. Although existing ground VLN agents achieved notable results in indoor and outdoor settings, they struggle in aerial VLN due to the absence of predefined navigation graphs and the exponentially expanding action space in long-horizon exploration. In this work, we propose \textbf{CityNavAgent}, a large language model (LLM)-empowered agent that significantly reduces the navigation complexity for urban aerial VLN. Specifically, we design a hierarchical semantic planning module (HSPM) that decomposes the long-horizon task into sub-goals with different semantic levels. The agent reaches the target progressively by achieving sub-goals with different capacities of the LLM. Additionally, a global memory module storing historical trajectories into a topological graph is developed to simplify navigation for visited targets. Extensive benchmark experiments show that our method achieves state-of-the-art performance with significant improvement. Further experiments demonstrate the effectiveness of different modules of CityNavAgent for aerial VLN in continuous city environments. The code is available at \href{https://github.com/VinceOuti/CityNavAgent}{link}.

[Arxiv](https://arxiv.org/abs/2505.05622)