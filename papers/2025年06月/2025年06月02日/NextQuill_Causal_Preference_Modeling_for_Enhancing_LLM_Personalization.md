# NextQuill：通过因果偏好建模提升 LLM 个性化体验

发布时间：2025年06月02日

`LLM理论` `个性化服务` `因果关系`

> NextQuill: Causal Preference Modeling for Enhancing LLM Personalization

# 摘要

> 为个人用户提供个性化的大型语言模型 (LLMs) 正变得越来越重要，因为它们正逐步融入现实世界的应用程序，以支持用户的日常生活。然而，现有的个性化方法通常无法区分模型预测和训练数据中的哪些部分真正反映了用户的偏好，导致了表面化的个性化对齐。本文中，我们介绍了 NextQuill，这是一个基于因果偏好建模的新型 LLM 个性化对齐框架。我们从因果的角度来处理个性化问题，将模型预测和真实数据生成都视为受用户偏好以及其他因素影响的结果。我们定义了真正偏好效应，即用户历史（反映偏好）对每个令牌预测或数据生成实例的因果影响，通过因果干预技术进行估计。基于这一见解，NextQuill 提出了两种互补的对齐策略：（1）将模型内部对预测的因果偏好效应与真实数据中反映的偏好效应进行对齐，而不是不加区分地拟合预测；（2）专注于拟合通过真实数据偏好效应识别出的带有偏好的令牌，而不是对所有令牌一视同仁。通过整合这些策略，NextQuill 将对齐过程转向学习因果偏好效应，从而促进更有效和个性化的适应。在多个个性化基准上的实验表明，NextQuill 显著提高了个性化质量，为 LLM 的个性化提供了一个基于因果关系的坚实基础。我们的代码可在 https://github.com/juntaoyou/NextQuill 获取。

> Personalizing large language models (LLMs) for individual users has become increasingly important as they are progressively integrated into real-world applications to support users' daily lives. However, existing personalization approaches often fail to distinguish which components of model predictions and training data truly reflect user preferences, leading to superficial personalization alignment. In this paper, we introduce NextQuill, a novel LLM personalization alignment framework grounded in causal preference modeling. We approach personalization from a causal perspective, treating both model predictions and ground-truth data generation as outcomes influenced by user preferences, along with other factors. We define the true preference effect as the causal impact of user history (which reflects preferences) on each token prediction or data generation instance, estimated through causal intervention techniques. Building on this insight, NextQuill introduces two complementary alignment strategies: (1) aligning model-internal causal preference effects on predictions with those reflected in ground-truth data, rather than indiscriminately fitting predictions, and (2) focusing on fitting preference-bearing tokens identified via ground-truth data preference effects, rather than treating all tokens uniformly. By integrating these strategies, NextQuill shifts the alignment process toward learning from causal preference effects, facilitating more effective and personalized adaptation. Experiments across multiple personalization benchmarks demonstrate that NextQuill significantly improves personalization quality, offering a principled, causal foundation for LLM personalization. Our codes are available on https://github.com/juntaoyou/NextQuill.

[Arxiv](https://arxiv.org/abs/2506.02368)