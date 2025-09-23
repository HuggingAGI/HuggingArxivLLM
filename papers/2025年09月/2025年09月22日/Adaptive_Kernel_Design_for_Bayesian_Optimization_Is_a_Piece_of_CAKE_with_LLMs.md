# LLMs助力下，贝叶斯优化的自适应核设计小菜一碟

发布时间：2025年09月22日

`LLM应用` `工业与制造`

> Adaptive Kernel Design for Bayesian Optimization Is a Piece of CAKE with LLMs

# 摘要

> 贝叶斯优化（BO）的效率很大程度上取决于高斯过程（GP）核函数的选择，该核函数在有限评估预算下平衡探索与利用方面扮演着核心角色。传统BO方法常采用固定或启发式的核函数选择策略，当所选核函数与底层目标函数适配性较差时，易导致收敛缓慢或解的次优性。为解决这一局限，我们全新提出了上下文感知核函数进化（CAKE）方法，借助大型语言模型（LLMs）增强BO。具体而言，CAKE将LLMs作为交叉和变异算子，在整个优化过程中基于观测数据自适应生成并优化GP核函数。为充分发挥CAKE的效能，我们进一步提出BIC-获取核函数排序（BAKER）方法，通过平衡贝叶斯信息准则（BIC）衡量的模型拟合度与BO每次迭代的期望改进，选出最有效的核函数。大量实验证实，我们提出的全新CAKE增强型BO方法在一系列现实任务中（包括超参数优化、控制器调优和光子芯片设计）均持续优于现有基准方法。我们的代码已开源，地址为https://github.com/cake4bo/cake。

> The efficiency of Bayesian optimization (BO) relies heavily on the choice of the Gaussian process (GP) kernel, which plays a central role in balancing exploration and exploitation under limited evaluation budgets. Traditional BO methods often rely on fixed or heuristic kernel selection strategies, which can result in slow convergence or suboptimal solutions when the chosen kernel is poorly suited to the underlying objective function. To address this limitation, we propose a freshly-baked Context-Aware Kernel Evolution (CAKE) to enhance BO with large language models (LLMs). Concretely, CAKE leverages LLMs as the crossover and mutation operators to adaptively generate and refine GP kernels based on the observed data throughout the optimization process. To maximize the power of CAKE, we further propose BIC-Acquisition Kernel Ranking (BAKER) to select the most effective kernel through balancing the model fit measured by the Bayesian information criterion (BIC) with the expected improvement at each iteration of BO. Extensive experiments demonstrate that our fresh CAKE-based BO method consistently outperforms established baselines across a range of real-world tasks, including hyperparameter optimization, controller tuning, and photonic chip design. Our code is publicly available at https://github.com/cake4bo/cake.

[Arxiv](https://arxiv.org/abs/2509.17998)