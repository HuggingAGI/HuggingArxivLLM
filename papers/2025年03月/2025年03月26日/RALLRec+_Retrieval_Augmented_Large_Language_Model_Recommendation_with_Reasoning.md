# RALLRec+: 集成推理能力的检索增强型大型语言模型推荐系统

发布时间：2025年03月26日

`LLM应用` `推荐系统`

> RALLRec+: Retrieval Augmented Large Language Model Recommendation with Reasoning

# 摘要

> 大型语言模型（LLMs）正在被广泛应用于推荐系统中，以提升对用户行为的理解。检索增强生成（RAG）技术进一步被引入，用于提高内容的相关性和系统性能。然而，现有RAG方法存在两大关键问题：	extit{(i)} 在	extit{检索阶段}，它们过度依赖文本语义，常常忽略最相关的内容，导致系统效果受限；	extit{(ii)} 在	extit{生成阶段}，缺乏明确的链式推理能力，进一步制约了其潜力。

    本文提出了一种创新的基于表示学习和推理增强的检索-增强大型语言模型推荐方法（RALLRec+）。具体而言，在检索阶段，我们通过提示LLMs生成详细的内容描述，并结合从LLM和推荐模型中提取的文本和协作信号进行联合表示学习。为了应对用户兴趣随时间变化的特性，我们设计了一种简单而有效的重排序方法，以捕捉用户偏好的动态变化。在生成阶段，我们首先评估推理型LLMs在推荐任务中的表现，揭示了其潜在的优势和挑战。随后，我们引入知识注入提示和基于一致性的融合方法，将推理型LLMs与通用型LLMs相结合，从而显著提升了整体推荐效果。通过在三个真实世界数据集上的广泛实验，我们验证了该方法的有效性和优越性。

> Large Language Models (LLMs) have been integrated into recommender systems to enhance user behavior comprehension. The Retrieval Augmented Generation (RAG) technique is further incorporated into these systems to retrieve more relevant items and improve system performance. However, existing RAG methods have two shortcomings. \textit{(i)} In the \textit{retrieval} stage, they rely primarily on textual semantics and often fail to incorporate the most relevant items, thus constraining system effectiveness. \textit{(ii)} In the \textit{generation} stage, they lack explicit chain-of-thought reasoning, further limiting their potential.
  In this paper, we propose Representation learning and \textbf{R}easoning empowered retrieval-\textbf{A}ugmented \textbf{L}arge \textbf{L}anguage model \textbf{Rec}ommendation (RALLRec+). Specifically, for the retrieval stage, we prompt LLMs to generate detailed item descriptions and perform joint representation learning, combining textual and collaborative signals extracted from the LLM and recommendation models, respectively. To account for the time-varying nature of user interests, we propose a simple yet effective reranking method to capture preference dynamics. For the generation phase, we first evaluate reasoning LLMs on recommendation tasks, uncovering valuable insights. Then we introduce knowledge-injected prompting and consistency-based merging approach to integrate reasoning LLMs with general-purpose LLMs, enhancing overall performance. Extensive experiments on three real world datasets validate our method's effectiveness.

[Arxiv](https://arxiv.org/abs/2503.20430)