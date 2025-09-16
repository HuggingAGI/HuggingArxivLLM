# 基于领域专家心智模型的大型语言模型增强：利用因果提示工程减少LLM幻觉

发布时间：2025年09月13日

`LLM应用` `基础理论`

> LLM Enhancement with Domain Expert Mental Model to Reduce LLM Hallucination with Causal Prompt Engineering

# 摘要

> 各个学科和领域中都充斥着棘手的决策难题。生成式技术（尤其是大型语言模型，LLMs）的蓬勃发展，激发了将其应用于决策支持的浓厚兴趣。但LLMs仍无法解决训练数据中的信息缺失问题，从而产生幻觉。检索增强生成（RAG）通过整合外部信息检索对LLMs进行增强，有效减少了幻觉并提升了准确性。然而，RAG及相关方法只是部分解决方案——它们可能无法获取所有必要来源或关键缺失信息，即便是日常问题也常常让LLMs难以应对。提交包含上下文和示例的更长提示词是弥补知识空白的一种思路，但设计有效的提示词绝非易事，也可能无法充分捕捉领域专家的复杂心智模型。对于缺少关键信息的任务，LLMs能力不足；许多现有系统在可用文档中描述不够充分，同样存在不足。本文探讨LLMs如何提升决策效率，并以评估是否响应征集提案为贯穿全文的案例。我们提出一种基于优化人机对话及单调布尔函数和k值函数的技术，用于发现计算可行的个人专家决策心智模型（EMM）。该EMM算法专为LLM提示词工程设计，分为四个步骤：（1）因素识别，（2）因素的层次化构建，（3）生成广义专家心智模型规范，（4）基于此规范生成详细的广义专家心智模型。

> Difficult decision-making problems abound in various disciplines and domains. The proliferation of generative techniques, especially large language models (LLMs), has excited interest in using them for decision support. However, LLMs cannot yet resolve missingness in their training data, leading to hallucinations. Retrieval-Augmented Generation (RAG) enhances LLMs by incorporating external information retrieval, reducing hallucinations and improving accuracy. Yet, RAG and related methods are only partial solutions, as they may lack access to all necessary sources or key missing information. Even everyday issues often challenge LLMs' abilities. Submitting longer prompts with context and examples is one approach to address knowledge gaps, but designing effective prompts is non-trivial and may not capture complex mental models of domain experts. For tasks with missing critical information, LLMs are insufficient, as are many existing systems poorly represented in available documents. This paper explores how LLMs can make decision-making more efficient, using a running example of evaluating whether to respond to a call for proposals. We propose a technology based on optimized human-machine dialogue and monotone Boolean and k-valued functions to discover a computationally tractable personal expert mental model (EMM) of decision-making. Our EMM algorithm for LLM prompt engineering has four steps: (1) factor identification, (2) hierarchical structuring of factors, (3) generating a generalized expert mental model specification, and (4) generating a detailed generalized expert mental model from that specification.

[Arxiv](https://arxiv.org/abs/2509.10818)