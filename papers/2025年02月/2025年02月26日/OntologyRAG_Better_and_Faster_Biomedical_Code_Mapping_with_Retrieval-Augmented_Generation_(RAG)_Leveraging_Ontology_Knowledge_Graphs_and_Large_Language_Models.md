# OntologyRAG: 利用本体知识图谱与大型语言模型，通过增强生成（RAG）技术实现更优更快的生物医学代码映射

发布时间：2025年02月26日

`RAG` `生物医学` `知识图谱`

> OntologyRAG: Better and Faster Biomedical Code Mapping with Retrieval-Augmented Generation (RAG) Leveraging Ontology Knowledge Graphs and Large Language Models

# 摘要

> 生物医学本体论在构建和形式化特定领域信息表示方面发挥着关键作用，它们全面定义了生物医学实体的概念和关系。生物医学代码映射旨在识别不同本体论概念之间的相似性或等价性。高质量代码映射的获取通常需要借助本体领域微调的语言模型（LM）自动生成未经优化的映射，随后由经验丰富的编码专家进行手动审核和修正。然而，现有的LM仅能以候选列表形式提供代码映射建议，且缺乏推理过程和证据支持，这意味着编码专家仍需逐一验证每个建议，以确保其与本体论来源的最佳匹配。由于本体论来源会定期更新以纳入新的研究成果，这一过程需要不断重复。因此，频繁的LM重新训练和手动优化使得代码映射成为一个耗时且劳动密集的任务。为解决这一问题，我们开发了OntologyRAG，这是一种基于知识图谱增强的检索增强生成（RAG）方法，通过利用知识图谱中的归纳偏见，在大型语言模型（LLM）中实现上下文学习（ICL）。我们的解决方案将LLMs与知识图谱相结合，通过未优化的本体论映射处理问题，并生成一套可解释的结果，包括预测推理和映射接近度评估。由于所有本体论更新均可通过标准流程更新知识图谱来实现，我们的解决方案无需重新训练LM。在自建的黄金数据集上的评估结果表明，使用我们的方法可帮助编码专家实现更高效、更精准的代码映射。代码可在https://github.com/iqvianlp/ontologyRAG获取。

> Biomedical ontologies, which comprehensively define concepts and relations for biomedical entities, are crucial for structuring and formalizing domain-specific information representations. Biomedical code mapping identifies similarity or equivalence between concepts from different ontologies. Obtaining high-quality mapping usually relies on automatic generation of unrefined mapping with ontology domain fine-tuned language models (LMs), followed by manual selections or corrections by coding experts who have extensive domain expertise and familiarity with ontology schemas. The LMs usually provide unrefined code mapping suggestions as a list of candidates without reasoning or supporting evidence, hence coding experts still need to verify each suggested candidate against ontology sources to pick the best matches. This is also a recurring task as ontology sources are updated regularly to incorporate new research findings. Consequently, the need of regular LM retraining and manual refinement make code mapping time-consuming and labour intensive. In this work, we created OntologyRAG, an ontology-enhanced retrieval-augmented generation (RAG) method that leverages the inductive biases from ontological knowledge graphs for in-context-learning (ICL) in large language models (LLMs). Our solution grounds LLMs to knowledge graphs with unrefined mappings between ontologies and processes questions by generating an interpretable set of results that include prediction rational with mapping proximity assessment. Our solution doesn't require re-training LMs, as all ontology updates could be reflected by updating the knowledge graphs with a standard process. Evaluation results on a self-curated gold dataset show promises of using our method to enable coding experts to achieve better and faster code mapping. The code is available at https://github.com/iqvianlp/ontologyRAG.

[Arxiv](https://arxiv.org/abs/2502.18992)