# 真相还是反转？基于LLM反事实分析的标签翻转评估中模型选择的最优解

发布时间：2025年05月20日

`LLM应用` `数据增强`

> Truth or Twist? Optimal Model Selection for Reliable Label Flipping Evaluation in LLM-based Counterfactuals

# 摘要

> 反事实例子通过反事实数据增强（CDA）被广泛用于提升大型语言模型（LLMs）的性能和鲁棒性。然而，用于评估生成反事实有效性的主要指标——标签翻转（label flipping）——其判别模型的选择却导致了不一致的结果。为了揭开这一现象的面纱，我们定义了反事实生成器与判别模型之间的四种关系类型。通过涉及两种先进LLM基方法、三个数据集、五种生成器模型和15种判别模型的大量实验，辅以一项用户研究（n = 90），我们发现：与生成器模型具有独立且未经微调关系的判别模型，提供了最可靠的标签翻转评估。生成器与判别模型之间的关系，与CDA的用户研究高度契合，能带来更好的模型性能和鲁棒性。然而，最有效的判别模型与用户研究结果之间的差距仍然相当大。这表明，一个完全自动化的CDA流水线可能不够完善，需要人工干预。

> Counterfactual examples are widely employed to enhance the performance and robustness of large language models (LLMs) through counterfactual data augmentation (CDA). However, the selection of the judge model used to evaluate label flipping, the primary metric for assessing the validity of generated counterfactuals for CDA, yields inconsistent results. To decipher this, we define four types of relationships between the counterfactual generator and judge models. Through extensive experiments involving two state-of-the-art LLM-based methods, three datasets, five generator models, and 15 judge models, complemented by a user study (n = 90), we demonstrate that judge models with an independent, non-fine-tuned relationship to the generator model provide the most reliable label flipping evaluations. Relationships between the generator and judge models, which are closely aligned with the user study for CDA, result in better model performance and robustness. Nevertheless, we find that the gap between the most effective judge models and the results obtained from the user study remains considerably large. This suggests that a fully automated pipeline for CDA may be inadequate and requires human intervention.

[Arxiv](https://arxiv.org/abs/2505.13972)