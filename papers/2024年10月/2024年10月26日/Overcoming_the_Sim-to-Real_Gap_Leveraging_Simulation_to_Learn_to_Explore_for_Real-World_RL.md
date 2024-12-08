# 克服仿真与现实的差距：借助仿真学习探索真实世界的强化学习

发布时间：2024年10月26日

`Agent` `机器人`

> Overcoming the Sim-to-Real Gap: Leveraging Simulation to Learn to Explore for Real-World RL

# 摘要

> 摘要：为降低现实世界强化学习的样本复杂度，通常会先在样本获取成本低的模拟器中训练策略，再将其部署到现实世界，期望能有效泛化。但这种“直接的模拟转现实”不一定能成功，若失败，也不知如何最优利用模拟器。本研究指出，在很多情形下，即便直接的模拟转现实失败，仍能借助模拟器学习一组“探索性”策略，以在现实世界实现高效探索。特别是在低秩 MDP 设定中，将这些探索性策略与简单实用的方法（如最小二乘回归预言机和朴素随机探索）相结合，能在现实世界产生多项式样本复杂度，相比直接的模拟转现实或无法使用模拟器学习，有指数级的提升。据我们所知，这是首次有证据表明，在直接的模拟转现实失败的情况下，模拟转移在强化学习中能带来可证明的收益。我们在多个现实的机器人模拟器和一个现实世界的机器人模拟转现实任务中验证了理论结果，表明转移探索性策略在实践中也能带来显著收益。

> 
Abstract:In order to mitigate the sample complexity of real-world reinforcement learning, common practice is to first train a policy in a simulator where samples are cheap, and then deploy this policy in the real world, with the hope that it generalizes effectively. Such \emph{direct sim2real} transfer is not guaranteed to succeed, however, and in cases where it fails, it is unclear how to best utilize the simulator. In this work, we show that in many regimes, while direct sim2real transfer may fail, we can utilize the simulator to learn a set of \emph{exploratory} policies which enable efficient exploration in the real world. In particular, in the setting of low-rank MDPs, we show that coupling these exploratory policies with simple, practical approaches -- least-squares regression oracles and naive randomized exploration -- yields a polynomial sample complexity in the real world, an exponential improvement over direct sim2real transfer, or learning without access to a simulator. To the best of our knowledge, this is the first evidence that simulation transfer yields a provable gain in reinforcement learning in settings where direct sim2real transfer fails. We validate our theoretical results on several realistic robotic simulators and a real-world robotic sim2real task, demonstrating that transferring exploratory policies can yield substantial gains in practice as well.
    

[Arxiv](https://arxiv.org/pdf/2410.20254)