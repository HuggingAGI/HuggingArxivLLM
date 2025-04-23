# 双优化器：提升机器学习遗忘的有效性与稳定性

发布时间：2025年04月22日

`其他` `人工智能` `计算机视觉`

> DualOptim: Enhancing Efficacy and Stability in Machine Unlearning with Dual Optimizers

# 摘要

> 现有的机器学习遗忘机制（MU）方法对超参数表现出显著的敏感性，需要精细的调参，这限制了其实际应用。本文中，我们首先通过实证展示了现有的 popular MU 方法在不同场景下的不稳定性和次优性能。为了解决这一问题，我们提出了 Dual Optimizer（DualOptim），该方法结合了自适应学习率和分离的动量因子。实证和理论证据表明，DualOptim 有助于实现有效的稳定遗忘。通过广泛的实验，我们展示了 DualOptim 能够显著提升 MU 在图像分类、图像生成和大型语言模型等多样化任务中的效果和稳定性，使其成为增强现有 MU 算法的通用方法。


> Existing machine unlearning (MU) approaches exhibit significant sensitivity to hyperparameters, requiring meticulous tuning that limits practical deployment. In this work, we first empirically demonstrate the instability and suboptimal performance of existing popular MU methods when deployed in different scenarios. To address this issue, we propose Dual Optimizer (DualOptim), which incorporates adaptive learning rate and decoupled momentum factors. Empirical and theoretical evidence demonstrates that DualOptim contributes to effective and stable unlearning. Through extensive experiments, we show that DualOptim can significantly boost MU efficacy and stability across diverse tasks, including image classification, image generation, and large language models, making it a versatile approach to empower existing MU algorithms.

[Arxiv](https://arxiv.org/abs/2504.15827)