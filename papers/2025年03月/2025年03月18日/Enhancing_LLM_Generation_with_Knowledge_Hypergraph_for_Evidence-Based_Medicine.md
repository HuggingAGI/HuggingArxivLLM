# 利用知识超图增强大型语言模型生成，助力循证医学

发布时间：2025年03月18日

`RAG` `知识图谱`

> Enhancing LLM Generation with Knowledge Hypergraph for Evidence-Based Medicine

# 摘要

> 循证医学（EBM）在大型语言模型（LLMs）于医疗领域的应用中至关重要，它为医疗决策提供了可靠支持。尽管当前检索增强生成（RAG）技术带来裨益，EBM仍面临两大挑战：分散证据的收集与高效组织，以满足复杂的查询需求。为解决这些问题，我们提出利用LLMs聚合多源证据，并开发了一种基于知识超图的证据管理模型，以整合证据并捕捉复杂关联。此外，我们还开发了重要性驱动的证据优先化（IDEP）算法，通过LLM生成多维度证据特征，并赋予每项特征重要性评分，从而实现证据排序与最终检索结果的生成。基于六个数据集的实验表明，我们的方法在医学问答、幻觉检测及决策支持等EBM相关领域，显著超越现有RAG技术。测试集及构建的知识图谱可访问：\href{https://drive.google.com/file/d/1WJ9QTokK3MdkjEmwuFQxwH96j_Byawj_/view?usp=drive_link}{https://drive.google.com/rag4ebm}。

> Evidence-based medicine (EBM) plays a crucial role in the application of large language models (LLMs) in healthcare, as it provides reliable support for medical decision-making processes. Although it benefits from current retrieval-augmented generation~(RAG) technologies, it still faces two significant challenges: the collection of dispersed evidence and the efficient organization of this evidence to support the complex queries necessary for EBM. To tackle these issues, we propose using LLMs to gather scattered evidence from multiple sources and present a knowledge hypergraph-based evidence management model to integrate these evidence while capturing intricate relationships. Furthermore, to better support complex queries, we have developed an Importance-Driven Evidence Prioritization (IDEP) algorithm that utilizes the LLM to generate multiple evidence features, each with an associated importance score, which are then used to rank the evidence and produce the final retrieval results. Experimental results from six datasets demonstrate that our approach outperforms existing RAG techniques in application domains of interest to EBM, such as medical quizzing, hallucination detection, and decision support. Testsets and the constructed knowledge graph can be accessed at \href{https://drive.google.com/file/d/1WJ9QTokK3MdkjEmwuFQxwH96j_Byawj_/view?usp=drive_link}{https://drive.google.com/rag4ebm}.

[Arxiv](https://arxiv.org/abs/2503.16530)