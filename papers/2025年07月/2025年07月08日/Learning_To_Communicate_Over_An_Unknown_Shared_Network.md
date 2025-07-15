# # 于未知共享网络中学习通信之道

发布时间：2025年07月08日

`Agent` `机器人` `无线网络`

> Learning To Communicate Over An Unknown Shared Network

# 摘要

> 随着机器人（边缘设备、代理）在越来越多的场景中得到应用，且边缘-云资源无处不在，无线网络将频繁地被代理与边缘云之间的数据流共享。在这些场景中，代理在与边缘云通信时，无法感知网络资源状态。这种状态不仅受当前代理通信行为的影响，还可能因其他代理的通信行为而改变，而这些对当前代理来说是未知的。我们致力于解决一个关键问题：如何让代理通过有限的通信反馈，学习到一个策略，决定是否与云端通信，以优化其效用。该策略需适用于任何数量的其他代理共享网络的情况，且无需针对特定网络配置进行训练。我们提出了一种基于深度强化学习（DRL）的模型——Query Net（QNet），并采用一种仿真到现实的框架对其进行训练。我们的仿真模型仅包含一个参数，且与任何特定无线网络配置无关。通过合理随机化仿真参数，该模型能够使代理在使用共享网络时，针对与其边缘云节点通信可能面临的一系列结果进行策略训练。我们还提出了一种学习算法，以解决训练QNet过程中遇到的挑战。我们通过在真实无线网络（包括WiFi和蜂窝网络）上进行的实验，验证了仿真到现实驱动方法的有效性。通过与其他策略的对比，我们证明了QNet的优越性。在WiFi实验中，参与的代理数量从最少5个（几乎无网络竞争）到最多50个（严重竞争）。蜂窝网络实验则涵盖了广泛的网络条件，基线RTT从低至0.07秒到高达0.83秒不等。

> As robots (edge-devices, agents) find uses in an increasing number of settings and edge-cloud resources become pervasive, wireless networks will often be shared by flows of data traffic that result from communication between agents and corresponding edge-cloud. In such settings, agent communicating with the edge-cloud is unaware of state of network resource, which evolves in response to not just agent's own communication at any given time but also to communication by other agents, which stays unknown to the agent. We address challenge of an agent learning a policy that allows it to decide whether or not to communicate with its cloud node, using limited feedback it obtains from its own attempts to communicate, to optimize its utility. The policy generalizes well to any number of other agents sharing the network and must not be trained for any particular network configuration. Our proposed policy is a DRL model Query Net (QNet) that we train using a proposed simulation-to-real framework. Our simulation model has just one parameter and is agnostic to specific configurations of any wireless network. It allows training an agent's policy over a wide range of outcomes that an agent's communication with its edge-cloud node may face when using a shared network, by suitably randomizing the simulation parameter. We propose a learning algorithm that addresses challenges observed in training QNet. We validate our simulation-to-real driven approach through experiments conducted on real wireless networks including WiFi and cellular. We compare QNet with other policies to demonstrate its efficacy. WiFi experiments involved as few as five agents, resulting in barely any contention for the network, to as many as fifty agents, resulting in severe contention. The cellular experiments spanned a broad range of network conditions, with baseline RTT ranging from a low of 0.07 second to a high of 0.83 second.

[Arxiv](https://arxiv.org/abs/2507.06499)