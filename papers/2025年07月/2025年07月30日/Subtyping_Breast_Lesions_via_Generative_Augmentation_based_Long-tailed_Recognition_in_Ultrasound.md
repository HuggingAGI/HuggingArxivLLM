# 基于生成式增强的长尾识别在超声波乳腺病变分类中的应用

发布时间：2025年07月30日

`其他` `医学影像分析`

> Subtyping Breast Lesions via Generative Augmentation based Long-tailed Recognition in Ultrasound

# 摘要

> 准确识别乳腺病变亚型对个性化治疗至关重要，而超声检查作为一种安全便捷的影像手段，在乳腺疾病筛查中发挥着重要作用。然而，不同病变亚型的发病率呈现高度不均衡的长尾分布，这对自动化识别带来了巨大挑战。生成式增强技术为解决这一问题提供了新的思路。受此启发，我们提出了一种创新的双阶段长尾分类框架，通过高保真的数据合成缓解分布偏差，同时避免过度使用导致性能下降。框架中的强化学习驱动自适应采样器，能够动态调整合成与真实数据的比例，通过多智能体协作弥补真实数据不足，同时保持分类性能稳定。此外，我们的可控合成网络还集成了基于解剖学先验的感知模块，既能保持类别特征的独特性，又支持无标注推理。在内部长尾数据集和公开的不平衡乳腺超声数据集上的实验表明，与现有方法相比，我们的方法展现出更优的性能。更多合成图像可访问 https://github.com/Stinalalala/Breast-LT-GenAug 查看。

> Accurate identification of breast lesion subtypes can facilitate personalized treatment and interventions. Ultrasound (US), as a safe and accessible imaging modality, is extensively employed in breast abnormality screening and diagnosis. However, the incidence of different subtypes exhibits a skewed long-tailed distribution, posing significant challenges for automated recognition. Generative augmentation provides a promising solution to rectify data distribution. Inspired by this, we propose a dual-phase framework for long-tailed classification that mitigates distributional bias through high-fidelity data synthesis while avoiding overuse that corrupts holistic performance. The framework incorporates a reinforcement learning-driven adaptive sampler, dynamically calibrating synthetic-real data ratios by training a strategic multi-agent to compensate for scarcities of real data while ensuring stable discriminative capability. Furthermore, our class-controllable synthetic network integrates a sketch-grounded perception branch that harnesses anatomical priors to maintain distinctive class features while enabling annotation-free inference. Extensive experiments on an in-house long-tailed and a public imbalanced breast US datasets demonstrate that our method achieves promising performance compared to state-of-the-art approaches. More synthetic images can be found at https://github.com/Stinalalala/Breast-LT-GenAug.

[Arxiv](https://arxiv.org/abs/2507.22568)