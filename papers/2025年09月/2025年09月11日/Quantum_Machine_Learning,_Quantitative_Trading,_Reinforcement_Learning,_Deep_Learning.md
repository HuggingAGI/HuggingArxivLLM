# 量子机器学习、量化交易、强化学习、深度学习

发布时间：2025年09月11日

`Agent` `金融科技`

> Quantum Machine Learning, Quantitative Trading, Reinforcement Learning, Deep Learning

# 摘要

> 量子启发神经网络与深度强化学习的融合为金融交易开辟了一条充满潜力的新路径。我们将用于短期趋势预测的量子长短期记忆（QLSTM）与经典A3C的量子增强变体——量子异步优势演员-评论家（QA3C）相结合，为美元/新台币（USD/TWD）设计并实现了交易智能体。基于2000年1月1日至2025年4月30日的数据集（80%用于训练，20%用于测试）训练后，这只只做多（long-only）智能体在约5年期间实现了11.87%的回报率，最大回撤仅0.92%，表现超越了多只货币ETF。我们详细介绍了状态设计（包括QLSTM特征与指标）、用于趋势跟踪与风险控制的奖励函数，以及多核训练方法。结果显示，这种混合模型在外汇（FX）交易中展现出了极具竞争力的表现。研究发现，QLSTM在风险严控的小额盈利交易中成效显著，同时也为未来优化指明了方向。关键超参数：QLSTM序列长度【数学公式】，QA3C工作线程数【数学公式】。本研究的局限性在于采用了经典量子模拟和简化策略。ootnote{本文观点仅代表作者个人，与富国银行（Wells Fargo）无关。本文仅供参考，其中任何内容均不构成投资建议。富国银行不对本文作出任何明示或暗示的保证，并明确免除与本文相关的所有法律、税务及会计责任。

> The convergence of quantum-inspired neural networks and deep reinforcement learning offers a promising avenue for financial trading. We implemented a trading agent for USD/TWD by integrating Quantum Long Short-Term Memory (QLSTM) for short-term trend prediction with Quantum Asynchronous Advantage Actor-Critic (QA3C), a quantum-enhanced variant of the classical A3C. Trained on data from 2000-01-01 to 2025-04-30 (80\% training, 20\% testing), the long-only agent achieves 11.87\% return over around 5 years with 0.92\% max drawdown, outperforming several currency ETFs. We detail state design (QLSTM features and indicators), reward function for trend-following/risk control, and multi-core training. Results show hybrid models yield competitive FX trading performance. Implications include QLSTM's effectiveness for small-profit trades with tight risk and future enhancements. Key hyperparameters: QLSTM sequence length$=$4, QA3C workers$=$8. Limitations: classical quantum simulation and simplified strategy. \footnote{The views expressed in this article are those of the authors and do not represent the views of Wells Fargo. This article is for informational purposes only. Nothing contained in this article should be construed as investment advice. Wells Fargo makes no express or implied warranties and expressly disclaims all legal, tax, and accounting implications related to this article.

[Arxiv](https://arxiv.org/abs/2509.09176)