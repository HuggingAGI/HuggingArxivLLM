# 基于文献的科学观点新颖性评估

发布时间：2025年06月27日

`RAG` `科学创意生成` `新颖性评估`

> Literature-Grounded Novelty Assessment of Scientific Ideas

# 摘要

> 自动科学创意生成系统取得了显著进展，然而创意新颖性的自动评估仍是一个关键且未充分探索的挑战。通过文献综述进行人工新颖性评估耗时费力，易因主观性出错，且难以大规模实施。为解决这些问题，我们提出了创意新颖性评估器，这是一个基于LLM的增强生成（RAG）框架，采用两阶段检索再重排方法。创意新颖性评估器首先通过关键词和片段检索收集大量相关论文，然后通过嵌入过滤并结合基于维度的LLM重排对这些论文进行精炼。它还整合了专家标注的示例，以指导系统进行论文比较以评估新颖性，并生成基于文献的推理。我们广泛实验表明，我们的新颖性评估器比现有方法达成约13%的更高一致性。消融实验进一步凸显了基于维度的重排器在识别用于新颖性评估的最相关文献中的重要性。

> Automated scientific idea generation systems have made remarkable progress, yet the automatic evaluation of idea novelty remains a critical and underexplored challenge. Manual evaluation of novelty through literature review is labor-intensive, prone to error due to subjectivity, and impractical at scale. To address these issues, we propose the Idea Novelty Checker, an LLM-based retrieval-augmented generation (RAG) framework that leverages a two-stage retrieve-then-rerank approach. The Idea Novelty Checker first collects a broad set of relevant papers using keyword and snippet-based retrieval, then refines this collection through embedding-based filtering followed by facet-based LLM re-ranking. It incorporates expert-labeled examples to guide the system in comparing papers for novelty evaluation and in generating literature-grounded reasoning. Our extensive experiments demonstrate that our novelty checker achieves approximately 13% higher agreement than existing approaches. Ablation studies further showcases the importance of the facet-based re-ranker in identifying the most relevant literature for novelty evaluation.

[Arxiv](https://arxiv.org/abs/2506.22026)