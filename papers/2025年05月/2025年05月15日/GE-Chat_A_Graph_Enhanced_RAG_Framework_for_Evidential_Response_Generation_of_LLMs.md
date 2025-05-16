# GE-Chat：为大型语言模型打造的图增强RAG框架，助力证据性响应生成

发布时间：2025年05月15日

`RAG` `决策支持` `可信度评估`

> GE-Chat: A Graph Enhanced RAG Framework for Evidential Response Generation of LLMs

# 摘要

> 大型语言模型（LLMs）如今已成为人类决策过程中的得力助手，但一个普遍的提醒始终相伴：“LLMs 可能会出错。请谨慎处理重要信息。”这揭示了一个现实：并非所有来自 LLMs 的输出都值得信赖，用户必须手动评估它们。随着幻觉式回答的出现，这些回答通常伴有看似合理的解释，这为用户带来了复杂性并引发了信任问题。为了解决这一问题，本文提出了一种基于知识图谱增强的检索增强生成框架 GE-Chat，用于实现基于证据的响应生成。具体来说，当用户上传材料文档时，将创建一个知识图谱，这有助于构建一个检索增强型代理，通过超越其训练语料库的知识来提升代理的响应能力。然后，我们利用链式思维（CoT）逻辑生成、n 跳子图搜索和基于蕴含的句子生成来实现准确的证据检索。我们证明，我们的方法在识别自由文本上下文中的确切证据方面改进了现有模型的性能，提供了一种可靠的方式来审查 LLM 结论的资源来源，并帮助判断其可信度。

> Large Language Models are now key assistants in human decision-making processes. However, a common note always seems to follow: "LLMs can make mistakes. Be careful with important info." This points to the reality that not all outputs from LLMs are dependable, and users must evaluate them manually. The challenge deepens as hallucinated responses, often presented with seemingly plausible explanations, create complications and raise trust issues among users. To tackle such issue, this paper proposes GE-Chat, a knowledge Graph enhanced retrieval-augmented generation framework to provide Evidence-based response generation. Specifically, when the user uploads a material document, a knowledge graph will be created, which helps construct a retrieval-augmented agent, enhancing the agent's responses with additional knowledge beyond its training corpus. Then we leverage Chain-of-Thought (CoT) logic generation, n-hop sub-graph searching, and entailment-based sentence generation to realize accurate evidence retrieval. We demonstrate that our method improves the existing models' performance in terms of identifying the exact evidence in a free-form context, providing a reliable way to examine the resources of LLM's conclusion and help with the judgment of the trustworthiness.

[Arxiv](https://arxiv.org/abs/2505.10143)