# 双管齐下，相得益彰：LLM 对齐中的协作奖励建模

发布时间：2025年05月15日

`LLM理论` `人工智能`

> Two Minds Better Than One: Collaborative Reward Modeling for LLM Alignment

# 摘要

> 奖励模型（RMs）是实现大型语言模型（LLMs）与人类价值观对齐的关键。然而，人类反馈中的噪声偏好常导致奖励模型出现错误泛化，使其过度拟合虚假模式并在策略优化过程中发出误导性信号。通过对偏好对的训练动态进行系统性分析，我们发现噪声示例更难拟合，且会引入不稳定性。实证研究表明，使用基于完整噪声数据集训练的奖励模型优化的LLMs表现劣于基于过滤后的高质量偏好训练的模型。为解决这一问题，我们提出了协作奖励建模（CRM），这是一种结合同行评审和课程学习的在线框架，旨在增强模型的鲁棒性。在CRM中，两个奖励模型并行训练，互相评估数据选择以过滤潜在噪声。课程学习将偏好数据从简单到困难进行结构化，确保同步训练和稳定反馈。大量实验表明，CRM显著提升了模型的泛化能力，在40%标签噪声下，RewardBench上的准确率提高了9.94个百分点。此外，CRM还与隐式奖励对齐方法兼容，为实现稳健对齐提供了一种实用且灵活的策略。


> Reward models (RMs) are essential for aligning large language models (LLMs) with human values. However, noisy preferences in human feedback often lead to reward misgeneralization, where RMs overfit to spurious patterns and provide misleading signals during policy optimization. We systematically analyze the training dynamics of preference pairs and identify that noisy examples are harder to fit and introduce instability. Empirical evidence shows that LLMs optimized using reward models trained on full noisy datasets perform worse than those trained on filtered, high-quality preferences. To address this, we propose Collaborative Reward Modeling (CRM), an online framework that enhances robustness by combining peer review and curriculum learning. Two reward models are trained in parallel and assess each other's data selections to filter out potential noise. Curriculum learning structures the preference data from easy to hard, ensuring synchronized training and stable feedback. Extensive experiments demonstrate that CRM improves generalization, with up to 9.94 points of accuracy gain on RewardBench under 40 percent label noise. CRM is also compatible with implicit-reward alignment methods, offering a practical and versatile strategy for robust alignment.

[Arxiv](https://arxiv.org/abs/2505.10597)