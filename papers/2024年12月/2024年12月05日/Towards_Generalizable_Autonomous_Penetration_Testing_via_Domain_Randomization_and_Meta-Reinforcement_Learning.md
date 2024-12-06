# 借助领域随机化与元强化学习达成可通用的自主渗透测试

发布时间：2024年12月05日

`Agent` `网络安全` `渗透测试`

> Towards Generalizable Autonomous Penetration Testing via Domain Randomization and Meta-Reinforcement Learning

# 摘要

> 随着互联网上暴露的漏洞日益增多，自主渗透测试已然成为新兴研究领域，而强化学习正适合用于研究自主渗透测试。以往基于强化学习的自主渗透测试研究，主要着眼于提升代理在抽象模拟训练环境中的学习成效。他们忽视了在与训练环境差异巨大的现实环境中部署代理策略的适用性及泛化要求。相较而言，我们首次将关注点转向渗透测试代理在未曾见过的真实环境中的泛化能力。为此，我们提出了一个可泛化的自主渗透测试框架（即 GAP），用于训练能够触类旁通的代理——这是自主渗透测试广泛应用的关键所在，也是人类智能的显著特征。GAP 引入了一条实到虚再到实的流程，包含两个关键方法：领域随机化和元强化学习。具体而言，我们率先在自主渗透测试中应用领域随机化，并提出一种由大型语言模型驱动的领域随机化方法用于生成合成环境。我们进一步应用元强化学习，借助合成环境提高代理在未见过的环境中的泛化能力。这两种方法相结合，能够有效缩小泛化差距，提升策略适应性能。在各类易受攻击的虚拟机上开展了实验，结果显示 GAP 能够（a）在未知的真实环境中进行策略学习，（b）在类似环境中实现零样本策略迁移，（c）在不同环境中实现快速策略适应。

> With increasing numbers of vulnerabilities exposed on the internet, autonomous penetration testing (pentesting) has emerged as an emerging research area, while reinforcement learning (RL) is a natural fit for studying autonomous pentesting. Previous research in RL-based autonomous pentesting mainly focused on enhancing agents' learning efficacy within abstract simulated training environments. They overlooked the applicability and generalization requirements of deploying agents' policies in real-world environments that differ substantially from their training settings. In contrast, for the first time, we shift focus to the pentesting agents' ability to generalize across unseen real environments. For this purpose, we propose a Generalizable Autonomous Pentesting framework (namely GAP) for training agents capable of drawing inferences from one to another -- a key requirement for the broad application of autonomous pentesting and a hallmark of human intelligence. GAP introduces a Real-to-Sim-to-Real pipeline with two key methods: domain randomization and meta-RL learning. Specifically, we are among the first to apply domain randomization in autonomous pentesting and propose a large language model-powered domain randomization method for synthetic environment generation. We further apply meta-RL to improve the agents' generalization ability in unseen environments by leveraging the synthetic environments. The combination of these two methods can effectively bridge the generalization gap and improve policy adaptation performance. Experiments are conducted on various vulnerable virtual machines, with results showing that GAP can (a) enable policy learning in unknown real environments, (b) achieve zero-shot policy transfer in similar environments, and (c) realize rapid policy adaptation in dissimilar environments.

[Arxiv](https://arxiv.org/abs/2412.04078)