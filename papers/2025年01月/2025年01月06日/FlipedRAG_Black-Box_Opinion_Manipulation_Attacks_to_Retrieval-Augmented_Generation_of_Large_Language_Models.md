# FlipedRAG: 大型语言模型检索增强生成的黑箱意见操纵攻击

发布时间：2025年01月06日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统的安全问题，特别是针对RAG系统的舆论操纵攻击。论文提出了一种新的黑盒攻击方法FlipedRAG，并探讨了其在实际应用中的效果和防御机制的不足。因此，这篇论文的核心内容与RAG系统直接相关，应归类为RAG。` `信息安全` `舆论分析`

> FlipedRAG: Black-Box Opinion Manipulation Attacks to Retrieval-Augmented Generation of Large Language Models

# 摘要

> # 摘要
检索增强生成（RAG）通过动态从知识库中检索相关信息来补充 LLM 的输入，有效解决了幻觉和实时性限制问题。当接收到查询时，RAG 会从知识库中选取语义最相似的文本作为上下文，帮助 LLM 生成更准确的响应。然而，RAG 也引入了新的攻击面，尤其是其数据库多来自公共领域。尽管现有研究主要聚焦于优化 RAG 的性能和效率，但新兴研究已开始关注其安全问题。不过，这些研究存在局限性，通常局限于白盒方法或启发式黑盒攻击，且主要针对简单的问答任务，缺乏实际挑战性和抗纠正性。本文揭示了一个更具威胁的场景：针对 RAG 的争议性话题的舆论操纵。我们提出了一种新的黑盒攻击方法 FlipedRAG，基于迁移学习，通过指令工程从黑盒 RAG 系统中获取部分检索模型输出，训练代理模型以提升舆论操纵攻击的效果。实验表明，该方法将舆论操纵的平均成功率提高了 16.7%，并在四个主题中使 RAG 响应的意见极性平均发生了 50% 的方向性变化，同时引发了 20% 的用户认知变化。最后，我们讨论了现有防御机制的不足，强调开发新型防御策略的紧迫性。

> Retrieval-Augmented Generation (RAG) addresses hallucination and real-time constraints by dynamically retrieving relevant information from a knowledge database to supplement the LLMs' input. When presented with a query, RAG selects the most semantically similar texts from its knowledge bases and uses them as context for the LLMs to generate more accurate responses. RAG also creates a new attack surface, especially since RAG databases are frequently sourced from public domains. While existing studies have predominantly focused on optimizing RAG's performance and efficiency, emerging research has begun addressing the security concerns associated with RAG. However, these works have some limitations, typically focusing on either white-box methodologies or heuristic-based black-box attacks. Furthermore, prior research has mainly targeted simple factoid question answering, which is neither practically challenging nor resistant to correction. In this paper, we unveil a more realistic and threatening scenario: opinion manipulation for controversial topics against RAG. Particularly, we propose a novel RAG black-box attack method, termed FlipedRAG, which is transfer-based. By leveraging instruction engineering, we obtain partial retrieval model outputs from black-box RAG system, facilitating the training of surrogate models to enhance the effectiveness of opinion manipulation attack. Extensive experimental results confirms that our approach significantly enhances the average success rate of opinion manipulation by 16.7%. It achieves an average of a 50% directional change in the opinion polarity of RAG responses across four themes. Additionally, it induces a 20% shift in user cognition. Furthermore, we discuss the efficacy of potential defense mechanisms and conclude that they are insufficient in mitigating this type of attack, highlighting the urgent need to develop novel defensive strategies.

[Arxiv](https://arxiv.org/abs/2501.02968)