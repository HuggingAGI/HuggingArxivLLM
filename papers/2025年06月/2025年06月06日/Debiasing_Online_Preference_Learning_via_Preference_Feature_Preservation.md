# 基于偏好特征保持的在线偏好学习偏见去除方法

发布时间：2025年06月06日

`LLM理论` `人工智能` `机器学习`

> Debiasing Online Preference Learning via Preference Feature Preservation

# 摘要

> 当前针对大型语言模型（LLMs）的偏好学习框架将人类偏好简化为二元比较和标量奖励。这种简化可能导致LLMs的响应过于偏向主要偏好特征，而这一问题在在线偏好学习迭代过程中会进一步加剧。为了解决这些挑战，我们提出了名为PFP（Preference Feature Preservation，偏好特征保持）的新颖框架。PFP的核心理念是保持人类偏好特征的分布，并在整个在线偏好学习过程中充分利用这些丰富信号。具体而言，PFP首先从离线的人类偏好配对数据中提取偏好特征并训练特征分类器。然后，在线学习过程中，PFP利用已训练的分类器和分布保持优化，为新的输入指令映射合适的偏好特征。最后，PFP通过在系统提示中融入偏好特征，并使LLM能够显式处理各种人类偏好，采用现有偏好学习方法对LLM进行训练。我们的实验表明，PFP成功缓解了在线学习过程中偏好特征的偏差，因此在评估LLM对齐的标准基准上，相较于先前的偏好学习方法，PFP取得了更优的性能表现。

> Recent preference learning frameworks for large language models (LLMs) simplify human preferences with binary pairwise comparisons and scalar rewards. This simplification could make LLMs' responses biased to mostly preferred features, and would be exacerbated during the iterations of online preference learning steps. To address these challenges, we propose a novel framework coined PFP (Preference Feature Preservation). The key idea of PFP is maintaining the distribution of human preference features and utilizing such rich signals throughout the online preference learning process. Specifically, PFP first extract preference features from offline pairwise human preference data and trains a feature classifier. Then, using trained classifier and the distribution preserving optimization, PFP maps appropriate preference features for a new input instruction during online learning. Lastly, PFP trains LLM using the existing preference learning method, by incorporating the preference feature into system prompts and enabling LLM to explicitly handle various human preferences. Our experiments demonstrate that PFP successfully mitigates the bias in preference features during online learning, and hence achieves superior performance compared to previous preference learning methods on standard benchmarks to evaluate LLM alignment.

[Arxiv](https://arxiv.org/abs/2506.11098)