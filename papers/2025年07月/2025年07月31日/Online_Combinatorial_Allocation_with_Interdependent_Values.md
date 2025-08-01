# 在线组合分配问题中的相互关联价值研究

发布时间：2025年07月31日

`其他` `组合优化` `在线算法`

> Online Combinatorial Allocation with Interdependent Values

# 摘要

> 我们在秘书设置下研究具有相互依赖价值的在线组合分配问题。根据 Milgrom 和 Weber (1982) 的模型，每个代理人都拥有一个私人信号，该信号反映了他们对销售物品的了解，而每个代理人的价值取决于所有代理人的信号。Mauras, Mohan 和 Reiffenhäuser (2024) 是首批在在线设置中研究相互依赖价值的研究者，他们在秘书设置下提供了常数近似保证，其中代理人在携带信号和价值的同时在线到达，目标是选择价值最高的代理人。

在这项工作中，我们将这一框架扩展到 {\em 组合} 秘书问题，其中代理人在 {\em 物品组合} 上具有相互依赖的估值，由于组合结构和相互依赖性，这带来了额外的挑战。我们为包括子模函数和 XOS 函数在内的广泛类别的估值函数提供了【数学公式】-竞争算法，与单选择秘书设置中的近似保证相匹配。此外，我们的结果涵盖了在经典（非相互依赖）秘书设置中存在常数因子算法的相同范围的估值类，而仅因相互依赖性额外增加了 $2$ 的因子。最后，我们将研究扩展到战略设置，并为具有相互依赖估值的在线二分匹配提供了一个【数学公式】-竞争的真实机制，再次达到了已知的前沿，即使没有相互依赖性也是如此。


> We study online combinatorial allocation problems in the secretary setting, under interdependent values. In the interdependent model, introduced by Milgrom and Weber (1982), each agent possesses a private signal that captures her information about an item for sale, and the value of every agent depends on the signals held by all agents. Mauras, Mohan, and Reiffenhäuser (2024) were the first to study interdependent values in online settings, providing constant-approximation guarantees for secretary settings, where agents arrive online along with their signals and values, and the goal is to select the agent with the highest value.
  In this work, we extend this framework to {\em combinatorial} secretary problems, where agents have interdependent valuations over {\em bundles} of items, introducing additional challenges due to both combinatorial structure and interdependence. We provide $2e$-competitive algorithms for a broad class of valuation functions, including submodular and XOS functions, matching the approximation guarantees in the single-choice secretary setting. Furthermore, our results cover the same range of valuation classes for which constant-factor algorithms exist in classical (non-interdependent) secretary settings, while incurring only an additional factor of $2$ due to interdependence. Finally, we extend our study to strategic settings, and provide a $4e$-competitive truthful mechanism for online bipartite matching with interdependent valuations, again meeting the frontier of what is known, even without interdependence.

[Arxiv](https://arxiv.org/abs/2507.23500)