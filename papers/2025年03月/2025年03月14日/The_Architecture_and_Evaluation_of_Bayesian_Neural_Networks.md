# 贝叶斯神经网络的架构及评估

发布时间：2025年03月14日

`其他` `机器学习`

> The Architecture and Evaluation of Bayesian Neural Networks

# 摘要

> 现代神经网络的复杂性使得构建高预测性能且具备良好不确定性量化的模型更具挑战性。尽管贝叶斯神经网络在理论上展现出了一些令人鼓舞的结果，但常用的后验近似方法仍存在诸多问题。计算负担和不可处理的后验分布导致校准不当的贝叶斯神经网络面临低精度和不可靠的不确定性估计。近似贝叶斯推理旨在用更简单但可行的分布替代未知且不可处理的后验分布。现代深度模型的维度和缺乏可识别性使得马尔可夫链蒙特卡罗方法成本高昂且无法充分探索多峰后验。相比之下，变分推断在计算复杂性上有所改进，但缺乏基于采样的推理的渐近保证，并且倾向于集中在单一模式上。两种方法的性能在很大程度上取决于架构选择。本文通过考虑不同场景下的计算成本、准确性和不确定性量化（包括大宽度和外推数据）来探讨这一问题。为了改进后验探索，研究了不同的模型平均和集成技术及其对预测性能的好处。实验结果表明，变分推断总体上提供了比马尔可夫链蒙特卡罗更好的不确定性量化；此外，变分近似的堆叠和集成在显著降低计算成本的同时，提供了与马尔可夫链蒙特卡罗相当的精度。

> As modern neural networks get more complex, specifying a model with high predictive performance and sound uncertainty quantification becomes a more challenging task. Despite some promising theoretical results on the true posterior predictive distribution of Bayesian neural networks, the properties of even the most commonly used posterior approximations are often questioned. Computational burdens and intractable posteriors expose miscalibrated Bayesian neural networks to poor accuracy and unreliable uncertainty estimates. Approximate Bayesian inference aims to replace unknown and intractable posterior distributions with some simpler but feasible distributions. The dimensions of modern deep models coupled with the lack of identifiability make Markov chain Monte Carlo tremendously expensive and unable to fully explore the multimodal posterior. On the other hand, variational inference benefits from improved computational complexity but lacks the asymptotical guarantees of sampling-based inference and tends to concentrate around a single mode. The performance of both approaches heavily depends on architectural choices; this paper aims to shed some light on this, by considering the computational costs, accuracy and uncertainty quantification in different scenarios including large width and out-of-sample data. To improve posterior exploration, different model averaging and ensembling techniques are studied, along with their benefits on predictive performance. In our experiments, variational inference overall provided better uncertainty quantification than Markov chain Monte Carlo; further, stacking and ensembles of variational approximations provided comparable to Markov chain Monte Carlo accuracy at a much-reduced cost.

[Arxiv](https://arxiv.org/abs/2503.11808)