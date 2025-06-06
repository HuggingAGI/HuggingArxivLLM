# 选择性匹配损失——并非所有分数都生来平等

发布时间：2025年06月04日

`LLM理论

摘要讨论了损失函数的设计和优化，特别是在多分类任务和大型语言模型中的应用。核心贡献在于提出新的损失函数框架，探讨其理论性质和优化方法，属于理论层面。因此，归类为LLM理论。` `信息检索`

> Selective Matching Losses -- Not All Scores Are Created Equal

# 摘要

> 学习系统通过在某个域内将预测分数与观测结果进行匹配来工作。通常，准确预测某个子集（或区域）内的结果至关重要，而在其他区域的预测准确性则相对不那么重要。我们通过设计在分数域上递增的链接函数来构建选择性匹配损失函数。匹配损失是对链接函数的积分，而链接函数定义了损失灵敏度，作为分数的函数，强调高斜率高灵敏度区域，而非平坦区域。损失不对称性驱动模型解决其欠规范问题，在高灵敏度（即更重要）的区域做出更好的预测，并区分高重要性和低重要性区域。通过使用缩放和平移的Sigmoid和双曲正弦链接函数，可以设计出多种选择性标量损失。然而，这些损失的性质并不适用于多分类任务。按维度应用它们会缺乏排名灵敏度，无法根据类分数排名分配重要性。我们利用复合Softmax函数，开发了一个多维选择性损失框架，克服了标准Softmax函数的局限性，后者适合分类，但不适合区分相邻分数。选择性损失在具有更重要分数区域的应用中比传统损失具有显著优势，包括驻留时间预测、检索、点式、对比式、列表式损失的排序问题、蒸馏问题以及大型语言模型（LLMs）的微调对齐。

> Learning systems match predicted scores to observations over some domain. Often, it is critical to produce accurate predictions in some subset (or region) of the domain, yet less important to accurately predict in other regions. We construct selective matching loss functions by design of increasing link functions over score domains. A matching loss is an integral over the link. A link defines loss sensitivity as function of the score, emphasizing high slope high sensitivity regions over flat ones. Loss asymmetry drives a model and resolves its underspecification to predict better in high sensitivity regions where it is more important, and to distinguish between high and low importance regions. A large variety of selective scalar losses can be designed with scaled and shifted Sigmoid and hyperbolic sine links. Their properties, however, do not extend to multi-class. Applying them per dimension lacks ranking sensitivity that assigns importance according to class score ranking. Utilizing composite Softmax functions, we develop a framework for multidimensional selective losses. We overcome limitations of the standard Softmax function, that is good for classification, but not for distinction between adjacent scores. Selective losses have substantial advantage over traditional losses in applications with more important score regions, including dwell-time prediction, retrieval, ranking with either pointwise, contrastive pairwise, or listwise losses, distillation problems, and fine-tuning alignment of Large Language Models (LLMs).

[Arxiv](https://arxiv.org/abs/2506.04446)