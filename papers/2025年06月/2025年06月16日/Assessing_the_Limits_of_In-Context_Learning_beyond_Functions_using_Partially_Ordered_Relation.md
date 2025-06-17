# 通过偏序关系探索上下文学习的边界：超越函数的限制

发布时间：2025年06月16日

`LLM理论` `上下文学习`

> Assessing the Limits of In-Context Learning beyond Functions using Partially Ordered Relation

# 摘要

> 大型语言模型（LLM）的上下文学习（ICL）能力无需更新参数空间，即可通过生成合理且准确的任务响应（通常附带示例演示）展现出来。尽管当前研究主要关注文档级别概念的推理，但ICL在学习上下文中明确函数或关系方面的行为仍需深入探究。本文通过引入提示中归纳复杂性递增的概念，探讨了ICL在部分有序关系上的表现。研究发现，尽管ICL提供了一定优势，但随着提示复杂性的增加，其有效性受到限制，即使在有足够演示示例的情况下也是如此。这一发现得到了实证研究的支持，并通过其隐式优化过程得到了理论验证。代码可在\href{https://anonymous.4open.science/r/ICLonPartiallyOrderSet}{此处}获取。

> Generating rational and generally accurate responses to tasks, often accompanied by example demonstrations, highlights Large Language Model's (LLM's) remarkable In-Context Learning (ICL) capabilities without requiring updates to the model's parameter space. Despite having an ongoing exploration focused on the inference from a document-level concept, its behavior in learning well-defined functions or relations in context needs a careful investigation. In this article, we present the performance of ICL on partially ordered relation by introducing the notion of inductively increasing complexity in prompts. In most cases, the saturated performance of the chosen metric indicates that while ICL offers some benefits, its effectiveness remains constrained as we increase the complexity in the prompts even in presence of sufficient demonstrative examples. The behavior is evident from our empirical findings and has further been theoretically justified in term of its implicit optimization process. The code is available \href{https://anonymous.4open.science/r/ICLonPartiallyOrderSet}{here}.

[Arxiv](https://arxiv.org/abs/2506.13608)