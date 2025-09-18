# 关注差距：让知识库与用户需求精准匹配以提升心理健康检索

发布时间：2025年09月16日

`RAG` `医疗健康`

> Mind the Gap: Aligning Knowledge Bases with User Needs to Enhance Mental Health Retrieval

# 摘要

> 获取可靠的心理健康信息对早期求助至关重要，但扩展知识库不仅耗费资源，还常常与用户需求脱节。当用户提出的问题未被覆盖，或用非正式、情境化的语言表达时，检索系统的表现就会大打折扣。我们提出了一种基于AI的缺口感知语料库扩充框架，该框架通过叠加论坛帖子等自然用户数据，真实识别代表性不足的主题（即缺口），从而根据覆盖率和实用性优先进行扩充。在案例研究中，我们对比了定向扩充（基于缺口感知）与非定向扩充（随机添加），并在四个检索增强生成（RAG）管道中评估了检索信息的相关性和实用性。定向扩充通过适度扩充就实现了接近最优的性能——仅需分别增加42%（查询转换）、74%（重排序和分层）和318%（基线）的内容——就能达到详尽参考语料库约95%的性能水平。相比之下，非定向扩充要达到相当的性能，则需要大幅增加扩充量（分别为232%、318%、403%和763%），这在实际中根本不可行。这些结果表明，通过战略性定向扩充语料库，既能降低内容创作的需求，又能保持较高的检索和信息提供质量，为构建可信的健康信息库以及支持高风险领域的生成式AI应用提供了一种可扩展的方案。

> Access to reliable mental health information is vital for early help-seeking, yet expanding knowledge bases is resource-intensive and often misaligned with user needs. This results in poor performance of retrieval systems when presented concerns are not covered or expressed in informal or contextualized language. We present an AI-based gap-informed framework for corpus augmentation that authentically identifies underrepresented topics (gaps) by overlaying naturalistic user data such as forum posts in order to prioritize expansions based on coverage and usefulness. In a case study, we compare Directed (gap-informed augmentations) with Non-Directed augmentation (random additions), evaluating the relevance and usefulness of retrieved information across four retrieval-augmented generation (RAG) pipelines. Directed augmentation achieved near-optimal performance with modest expansions--requiring only a 42% increase for Query Transformation, 74% for Reranking and Hierarchical, and 318% for Baseline--to reach ~95% of the performance of an exhaustive reference corpus. In contrast, Non-Directed augmentation required substantially larger and thus practically infeasible expansions to achieve comparable performance (232%, 318%, 403%, and 763%, respectively). These results show that strategically targeted corpus growth can reduce content creation demands while sustaining high retrieval and provision quality, offering a scalable approach for building trusted health information repositories and supporting generative AI applications in high-stakes domains.

[Arxiv](https://arxiv.org/abs/2509.13626)