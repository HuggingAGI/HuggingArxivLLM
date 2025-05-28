# 通过无监督概念发现提升文本解释的可理解性

发布时间：2025年05月26日

`LLM理论` `人工智能` `可解释人工智能`

> Enhancing the Comprehensibility of Text Explanations via Unsupervised Concept Discovery

# 摘要

> 基于概念的可解释方法因其能够以符合人类推理的方式解释模型，已成为可解释人工智能领域的一种有前景的方法。然而，这类方法在文本领域的应用却十分有限。现有大多数方法依赖预定义的概念标注，无法发现未见过的概念；而其他无需监督的概念提取方法往往生成难以被人类直观理解的解释，这可能削弱用户信任。这些方法未能实现对可理解概念的自动发现。为解决这一问题，我们提出	extbf{ECO-Concept}，一个无需概念标注即可自动发现可理解概念的本征可解释性框架。ECO-Concept首先利用基于对象中心的架构自动提取语义概念，随后通过大型语言模型评估提取概念的可理解性，最后依据评估结果指导模型微调，以获得更具可理解性的解释。实验表明，我们的方法在各类任务中均表现出色。进一步的概念评估验证了ECO-Concept所学习的概念在可理解性方面超越了现有方法。

> Concept-based explainable approaches have emerged as a promising method in explainable AI because they can interpret models in a way that aligns with human reasoning. However, their adaption in the text domain remains limited. Most existing methods rely on predefined concept annotations and cannot discover unseen concepts, while other methods that extract concepts without supervision often produce explanations that are not intuitively comprehensible to humans, potentially diminishing user trust. These methods fall short of discovering comprehensible concepts automatically. To address this issue, we propose \textbf{ECO-Concept}, an intrinsically interpretable framework to discover comprehensible concepts with no concept annotations. ECO-Concept first utilizes an object-centric architecture to extract semantic concepts automatically. Then the comprehensibility of the extracted concepts is evaluated by large language models. Finally, the evaluation result guides the subsequent model fine-tuning to obtain more understandable explanations. Experiments show that our method achieves superior performance across diverse tasks. Further concept evaluations validate that the concepts learned by ECO-Concept surpassed current counterparts in comprehensibility.

[Arxiv](https://arxiv.org/abs/2505.20293)