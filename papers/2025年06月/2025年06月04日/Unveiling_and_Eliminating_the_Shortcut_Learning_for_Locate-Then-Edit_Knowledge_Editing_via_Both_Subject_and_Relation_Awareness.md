# 揭秘并消除定位-编辑的知识编辑中捷径学习：基于主题与关系的双管齐下
揭示并消除定位-编辑知识编辑中的捷径学习：通过主题和关系感知的双管齐下

发布时间：2025年06月04日

`LLM理论` `知识编辑` `大型语言模型`

> Unveiling and Eliminating the Shortcut Learning for Locate-Then-Edit Knowledge Editing via Both Subject and Relation Awareness

# 摘要

> 知识编辑的目标是在对无关知识产生最小副作用的同时，改变大型语言模型预测的目标知识。实现这一目标的有效方法是识别用于预测事实关联的关键参数，并通过优化过程进行修改以更新预测结果。然而，这些定位后编辑的方法存在不可控性，因为它们往往修改与目标编辑主题相关的大部分不相关关系。我们发现，这种不可控编辑的失败源于优化过程中存在的捷径学习问题。具体而言，我们发现模型在优化过程中学习的两个关键特征是主体特征和关系特征，但现有优化过程往往过度关注主体特征而忽视关系特征。为了解决这一问题，我们提出了一种新的两阶段优化过程，以平衡主体特征和关系特征的学习。实验结果表明，我们的方法成功避免了捷径学习，并在整体性能上达到了最优，为实现可控的知识编辑提供了有效解决方案。

> Knowledge editing aims to alternate the target knowledge predicted by large language models while ensuring the least side effects on unrelated knowledge. An effective way to achieve knowledge editing is to identify pivotal parameters for predicting factual associations and modify them with an optimization process to update the predictions. However, these locate-then-edit methods are uncontrollable since they tend to modify most unrelated relations connected to the subject of target editing. We unveil that this failure of controllable editing is due to a shortcut learning issue during the optimization process. Specifically, we discover two crucial features that are the subject feature and the relation feature for models to learn during optimization, but the current optimization process tends to over-learning the subject feature while neglecting the relation feature. To eliminate this shortcut learning of the subject feature, we propose a novel two-stage optimization process that balances the learning of the subject feature and the relation feature. Experimental results demonstrate that our approach successfully prevents knowledge editing from shortcut learning and achieves the optimal overall performance, contributing to controllable knowledge editing.

[Arxiv](https://arxiv.org/abs/2506.04042)