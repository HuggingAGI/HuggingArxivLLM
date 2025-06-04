# HAM：迈向调节隐式偏见的双曲一步

发布时间：2025年06月03日

`LLM理论` `机器学习`

> HAM: A Hyperbolic Step to Regulate Implicit Bias

# 摘要

> 理解优化算法的隐式偏差已成为解释深度学习模型泛化行为的核心。例如，过参数化 $m \odot w$ 诱导的双曲隐式偏差虽然能有效促进稀疏性，却会导致较小的有效学习率，从而减缓收敛速度。为克服这一障碍，我们提出 HAM（双曲感知最小化），它通过在优化器步骤和新的双曲镜面步骤之间交替进行，实现了改进的收敛性和与 $m \odot w$ 相似的有益双曲几何特征学习。我们通过将其与自然梯度下降相关联，对算法进行了诠释，并对其在欠定线性回归中的隐式偏差进行了精确表征。实验结果表明，HAM 的隐式偏差始终能显著提升性能——甚至在密集训练中表现更优。HAM 与不同的稀疏化方法结合使用时尤其有效，超越了现有技术水平。双曲步骤所需计算和内存开销极小，即使在小批量情况下也能成功，并且其实现可以与现有优化器无缝集成。

> Understanding the implicit bias of optimization algorithms has become central to explaining the generalization behavior of deep learning models. For instance, the hyperbolic implicit bias induced by the overparameterization $m \odot w$--though effective in promoting sparsity--can result in a small effective learning rate, which slows down convergence. To overcome this obstacle, we propose HAM (Hyperbolic Aware Minimization), which alternates between an optimizer step and a new hyperbolic mirror step. We derive the Riemannian gradient flow for its combination with gradient descent, leading to improved convergence and a similar beneficial hyperbolic geometry as $m \odot w$ for feature learning. We provide an interpretation of the the algorithm by relating it to natural gradient descent, and an exact characterization of its implicit bias for underdetermined linear regression. HAM's implicit bias consistently boosts performance--even of dense training, as we demonstrate in experiments across diverse tasks, including vision, graph and node classification, and large language model fine-tuning. HAM is especially effective in combination with different sparsification methods, improving upon the state of the art. The hyperbolic step requires minimal computational and memory overhead, it succeeds even with small batch sizes, and its implementation integrates smoothly with existing optimizers.

[Arxiv](https://arxiv.org/abs/2506.02630)