# # KCluster: 基于 LLM 的聚类方法用于知识组件发现

发布时间：2025年05月09日

`LLM应用` `教育技术`

> KCluster: An LLM-based Clustering Approach to Knowledge Component Discovery

# 摘要

> 教育工作者通过知识组件（KC）模型将评估问题与知识组件进行映射，以此评估学生知识。然而，为大规模试题库设计知识组件模型仍是教师们难以逾越的挑战，因为他们需逐题手动分析。随着生成式AI在教育领域的广泛应用，这一长期存在的专家设计知识组件模型的不足预计将更加凸显，因为课程工程师难以跟上试题生成的速度。在此项研究中，我们提出了一种名为KCluster的新颖知识组件发现算法，该算法基于大型语言模型（LLM）所诱导的一种新的相似性度量，通过识别具有相似性的题目簇来实现。我们通过三个数据集证明，大型语言模型能够生成一种有效的题目相似性度量，进而使聚类算法能够仅需极小的人工干预即可从试题中构建知识组件模型。KCluster结合了大型语言模型和聚类算法的优势，生成描述性的知识组件标签，并发现优于现有最佳专家设计模型的知识组件模型，以更好地预测学生表现。展望未来的研究方向，我们展示了KCluster如何揭示难以掌握的知识组件的见解，并为教学改进提供建议。
    

> Educators evaluate student knowledge using knowledge component (KC) models that map assessment questions to KCs. Still, designing KC models for large question banks remains an insurmountable challenge for instructors who need to analyze each question by hand. The growing use of Generative AI in education is expected only to aggravate this chronic deficiency of expert-designed KC models, as course engineers designing KCs struggle to keep up with the pace at which questions are generated. In this work, we propose KCluster, a novel KC discovery algorithm based on identifying clusters of congruent questions according to a new similarity metric induced by a large language model (LLM). We demonstrate in three datasets that an LLM can create an effective metric of question similarity, which a clustering algorithm can use to create KC models from questions with minimal human effort. Combining the strengths of LLM and clustering, KCluster generates descriptive KC labels and discovers KC models that predict student performance better than the best expert-designed models available. In anticipation of future work, we illustrate how KCluster can reveal insights into difficult KCs and suggest improvements to instruction.

[Arxiv](https://arxiv.org/abs/2505.06469)