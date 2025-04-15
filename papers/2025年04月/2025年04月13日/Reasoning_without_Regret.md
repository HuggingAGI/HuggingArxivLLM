# 无悔推理

发布时间：2025年04月13日

`LLM理论

摘要讨论了大型语言模型在处理多步骤任务中的应用，特别是通过链式推理进行连续决策。论文引入了逆向自适应奖励塑造（BARS）框架，探讨了奖励机制在模型训练中的理论分析，属于LLM理论范畴。` `优化算法`

> Reasoning without Regret

# 摘要

> 链式思维推理让大型语言模型能够通过将问题求解建模为连续决策问题来解决多步骤任务。基于结果的奖励虽然对最终答案的反馈效果显著，但在信用分配和收敛速度上存在挑战。而基于过程的奖励虽能提供高效的步骤级反馈，却通常需要昂贵的人类监督。我们引入了\emph{逆向自适应奖励塑造}（BARS），一个无悔框架，能够将稀疏的结果奖励转化为有效的过程信号。通过利用终端状态先验和覆盖树生成的稀疏奖励，BARS实现了奖励扩展并防止被利用。借助贝尔曼收缩和$(Δ, ε)$-gap奖励，我们的反向欧拉求解器在$O\left((R_{\max}/Δ)\log(1/ε)ight)$次迭代中达到$ε$-精度，并在$T$轮中产生$O(\log T)$的动态遗憾。我们的分析基于通用链、连续缩放极限和非线性费曼-卡茨界，揭示了近期基于结果的方法的经验成功与中间监督优势之间的联系。综合来看，这为结果奖励塑造提供了首个严格的无悔算法，为DeepSeek的R1的经验成功奠定了理论基础。

> Chain-of-thought reasoning enables large language models to solve multi-step tasks by framing problem solving as sequential decision problems. Outcome-based rewards, which provide feedback only on final answers, show impressive success, but face challenges with credit assignment and slow convergence. In contrast, procedure-based rewards offer efficient step-level feedback, but typically require costly human supervision. We introduce \emph{Backwards Adaptive Reward Shaping} (BARS), a no-regret framework that converts sparse outcomes-based rewards into effective procedure-based signals. BARS uses sparse rewards generated from terminal-state priors and cover trees to scale rewards while preventing exploitation. With Bellman contraction and $(Δ, ε)$-gap rewards, our backward Euler solver achieves $ε$-accuracy in $O\left((R_{\max}/Δ)\log(1/ε)\right)$ iterations with $O(\log T)$ dynamic regret over $T$ rounds. Our analysis, based on generic chaining, continuous scaling limits, and non-linear Feynman-Kac bounds, connects recent outcome-based methods' empirical successes with the benefits of intermediate supervision. Combined, this provides the first rigorous no-regret algorithm for outcome reward shaping, providing a theoretical foundation for the empirical success of DeepSeek's R1.

[Arxiv](https://arxiv.org/abs/2504.09777)