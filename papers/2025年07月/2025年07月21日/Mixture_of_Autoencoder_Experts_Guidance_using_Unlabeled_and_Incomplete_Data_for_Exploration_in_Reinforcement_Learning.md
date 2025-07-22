# 基于未标记和不完整数据的自动编码器专家混合指导方法，用于强化学习中的探索

发布时间：2025年07月21日

`Agent` `人工智能` `模仿学习`

> Mixture of Autoencoder Experts Guidance using Unlabeled and Incomplete Data for Exploration in Reinforcement Learning

# 摘要

> 近年来，强化学习（RL）领域的研究趋势凸显出，智能体需要从无奖励的交互和替代监督信号中学习，而不仅仅是依赖于显式奖励最大化。开发能够高效适应真实环境的通用智能体，往往需要借助这些无奖励信号来引导学习和行为。然而，尽管内在动机技术为智能体在缺乏显式奖励的情况下寻求新颖或不确定的状态提供了手段，但它们常常面临密集奖励环境或高维状态和动作空间复杂性的挑战。此外，现有大多数方法直接依赖未经处理的内在奖励信号，这可能使有效塑造或控制智能体的探索变得困难。我们提出了一种能够有效利用专家演示的框架，即使这些演示是不完整或不完美的。通过应用映射函数，将智能体状态与专家数据之间的相似性转化为有形的内在奖励，我们的方法实现了对专家行为的灵活且有针对性的探索。我们采用自动编码器专家混合模型来捕捉多样化的行为，并适应演示中缺失的信息。实验表明，我们的方法能够在稀疏和密集奖励环境中实现稳健的探索和强大的性能，即使演示稀疏或不完整。这为强化学习在现实场景中的应用提供了一个实用框架，其中最优数据不可用且需要精确的奖励控制。

> Recent trends in Reinforcement Learning (RL) highlight the need for agents to learn from reward-free interactions and alternative supervision signals, such as unlabeled or incomplete demonstrations, rather than relying solely on explicit reward maximization. Additionally, developing generalist agents that can adapt efficiently in real-world environments often requires leveraging these reward-free signals to guide learning and behavior. However, while intrinsic motivation techniques provide a means for agents to seek out novel or uncertain states in the absence of explicit rewards, they are often challenged by dense reward environments or the complexity of high-dimensional state and action spaces. Furthermore, most existing approaches rely directly on the unprocessed intrinsic reward signals, which can make it difficult to shape or control the agent's exploration effectively. We propose a framework that can effectively utilize expert demonstrations, even when they are incomplete and imperfect. By applying a mapping function to transform the similarity between an agent's state and expert data into a shaped intrinsic reward, our method allows for flexible and targeted exploration of expert-like behaviors. We employ a Mixture of Autoencoder Experts to capture a diverse range of behaviors and accommodate missing information in demonstrations. Experiments show our approach enables robust exploration and strong performance in both sparse and dense reward environments, even when demonstrations are sparse or incomplete. This provides a practical framework for RL in realistic settings where optimal data is unavailable and precise reward control is needed.

[Arxiv](https://arxiv.org/abs/2507.15287)