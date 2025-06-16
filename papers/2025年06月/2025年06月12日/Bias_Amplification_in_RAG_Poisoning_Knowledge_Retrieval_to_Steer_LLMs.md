# RAG中的偏见放大：毒化知识检索以控制大型语言模型

发布时间：2025年06月12日

`RAG` `人工智能` `公平性`

> Bias Amplification in RAG: Poisoning Knowledge Retrieval to Steer LLMs

# 摘要

> 在大型语言模型中，检索增强生成（RAG）系统通过整合外部知识显著提升了模型性能。然而，这也带来了新的安全风险。现有研究主要关注RAG系统中的中毒攻击如何影响模型输出质量，却忽视了这些攻击可能加剧模型偏见的潜在问题。例如，当查询关于家庭暴力受害者时，被操控的RAG系统可能会优先检索描绘女性为受害者的文档，导致模型生成带有性别刻板印象的输出，即使原始查询是性别中立的。为了展示偏见的影响，本文提出了一种偏见检索与奖励攻击（BRRA）框架，系统地研究了通过操控RAG系统来放大语言模型偏见的攻击途径。我们设计了一种基于多目标奖励函数的对抗性文档生成方法，采用子空间投影技术来操控检索结果，并构建了一个循环反馈机制以实现持续的偏见放大。在多个主流大型语言模型上的实验表明，BRRA攻击可以在多个维度显著增强模型的偏见。此外，我们还探索了一种双阶段防御机制，以有效缓解攻击的影响。这项研究揭示了RAG系统中的中毒攻击如何直接放大模型输出偏见，并阐明了RAG系统安全与模型公平性之间的关系。这种新型潜在攻击表明，我们需要密切关注RAG系统的公平性问题。

> In Large Language Models, Retrieval-Augmented Generation (RAG) systems can significantly enhance the performance of large language models by integrating external knowledge. However, RAG also introduces new security risks. Existing research focuses mainly on how poisoning attacks in RAG systems affect model output quality, overlooking their potential to amplify model biases. For example, when querying about domestic violence victims, a compromised RAG system might preferentially retrieve documents depicting women as victims, causing the model to generate outputs that perpetuate gender stereotypes even when the original query is gender neutral. To show the impact of the bias, this paper proposes a Bias Retrieval and Reward Attack (BRRA) framework, which systematically investigates attack pathways that amplify language model biases through a RAG system manipulation. We design an adversarial document generation method based on multi-objective reward functions, employ subspace projection techniques to manipulate retrieval results, and construct a cyclic feedback mechanism for continuous bias amplification. Experiments on multiple mainstream large language models demonstrate that BRRA attacks can significantly enhance model biases in dimensions. In addition, we explore a dual stage defense mechanism to effectively mitigate the impacts of the attack. This study reveals that poisoning attacks in RAG systems directly amplify model output biases and clarifies the relationship between RAG system security and model fairness. This novel potential attack indicates that we need to keep an eye on the fairness issues of the RAG system.

[Arxiv](https://arxiv.org/abs/2506.11415)