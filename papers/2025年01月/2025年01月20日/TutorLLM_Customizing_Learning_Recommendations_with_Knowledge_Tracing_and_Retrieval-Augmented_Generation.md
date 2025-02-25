# TutorLLM：通过知识追踪与检索增强生成实现个性化学习推荐

发布时间：2025年01月20日

`LLM应用` `个性化学习`

> TutorLLM: Customizing Learning Recommendations with Knowledge Tracing and Retrieval-Augmented Generation

# 摘要

> 人工智能在教育领域的应用为提升学习效率带来了巨大潜力。以ChatGPT、Gemini和Llama为代表的大型语言模型（LLMs）为学生提供了前所未有的学习灵活性，使他们能够轻松查询各类知识。然而，现有LLMs在内容相关性和个性化方面仍存在不足。为此，我们提出了TutorLLM——一个基于知识追踪（KT）与检索增强生成（RAG）技术的个性化学习推荐系统。TutorLLM的创新之处在于它将KT与RAG技术与LLMs相结合，能够动态检索特定上下文的知识，并根据学生个人学习状态提供个性化学习建议。具体而言，这种整合使TutorLLM能够根据多特征隐含关系BERT基知识追踪（MLFBK）模型预测的个人学习状态定制响应，并通过Scrapper模型提升响应准确性。通过用户评估问卷和性能指标的综合评估，结果显示与仅使用通用LLMs相比，TutorLLM使用户满意度提升了10%，考试分数提高了5%。

> The integration of AI in education offers significant potential to enhance learning efficiency. Large Language Models (LLMs), such as ChatGPT, Gemini, and Llama, allow students to query a wide range of topics, providing unprecedented flexibility. However, LLMs face challenges, such as handling varying content relevance and lack of personalization. To address these challenges, we propose TutorLLM, a personalized learning recommender LLM system based on Knowledge Tracing (KT) and Retrieval-Augmented Generation (RAG). The novelty of TutorLLM lies in its unique combination of KT and RAG techniques with LLMs, which enables dynamic retrieval of context-specific knowledge and provides personalized learning recommendations based on the student's personal learning state. Specifically, this integration allows TutorLLM to tailor responses based on individual learning states predicted by the Multi-Features with Latent Relations BERT-based KT (MLFBK) model and to enhance response accuracy with a Scraper model. The evaluation includes user assessment questionnaires and performance metrics, demonstrating a 10\% improvement in user satisfaction and a 5\% increase in quiz scores compared to using general LLMs alone.

[Arxiv](https://arxiv.org/abs/2502.15709)