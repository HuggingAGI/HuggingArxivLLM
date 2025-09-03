# 无约束重拟合：Bregman损失下不透明机器学习/人工智能模型的无模型超额风险评估

发布时间：2025年09月02日

`LLM理论` `基础理论`

> Wild Refitting for Model-Free Excess Risk Evaluation of Opaque ML/AI Models under Bregman Loss

# 摘要

> 我们研究了基于Bregman损失的经典惩罚经验风险最小化（ERM）超额风险评估问题。研究表明，借助最新提出的野生重拟合方法（Wainwright, 2025），通过所谓的“野生乐观性”可高效地为超额风险提供上界，且无需依赖底层函数类的全局结构。这一特性使该方法具有内在的无模型属性。与传统分析不同，我们的框架仅需一个数据集，并通过黑箱方式访问训练过程。该方法通过对预测残差进行适当缩放实现随机向量值对称化，同时构建人工修改的结果，进而重新训练第二个预测器以估计超额风险。我们在固定设计与随机设计两种设置下均确立了高概率性能保证，结果显示：在Bregman损失下，通过合理选择野生噪声尺度，野生重拟合能够为超额风险提供有效上界。因此，这项工作有望为现代不透明机器学习与人工智能模型（如深度神经网络和大型语言模型）的理论评估提供支持——这类模型的复杂度远超经典学习理论和经验过程技术的适用范围。

> We study the problem of evaluating the excess risk of classical penalized empirical risk minimization (ERM) with Bregman losses. We show that by leveraging the recently proposed wild refitting procedure (Wainwright, 2025), one can efficiently upper bound the excess risk through the so-called "wild optimism," without relying on the global structure of the underlying function class. This property makes our approach inherently model-free. Unlike conventional analyses, our framework operates with just one dataset and black-box access to the training procedure. The method involves randomized vector-valued symmetrization with an appropriate scaling of the prediction residues and constructing artificially modified outcomes, upon which we retrain a second predictor for excess risk estimation. We establish high-probability performance guarantees both under the fixed design setting and the random design setting, demonstrating that wild refitting under Bregman losses, with an appropriately chosen wild noise scale, yields a valid upper bound on the excess risk. This work thus is promising for theoretically evaluating modern opaque ML and AI models such as deep neural networks and large language models, where the model class is too complex for classical learning theory and empirical process techniques to apply.

[Arxiv](https://arxiv.org/abs/2509.02476)