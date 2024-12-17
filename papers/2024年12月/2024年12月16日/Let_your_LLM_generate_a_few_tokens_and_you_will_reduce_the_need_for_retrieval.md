# 让您的 LLM 生成一些标记，您对检索的需求就会降低。

发布时间：2024年12月16日

`RAG` `语言模型` `训练数据`

> Let your LLM generate a few tokens and you will reduce the need for retrieval

# 摘要

> 在本文中，我们探究大型语言模型（LLM）训练效率如何，以检验答案是否已存于其参数化内存。我们提炼出一个充当裁判的LLM来计算IK（我知道）分数。我们发现，此方法在检索辅助增强生成（RAG）情境中益处显著，准确率达80%。它能大幅减少（超50%）某些数据集所需的搜索和重新排序步骤数量。我们还引入了IK分数，其通过助力分类任务，成为表征数据集的有用工具。有趣的是，将响应标记作为输入，结果表明仅需约20,000个训练样本即可实现良好性能。这项工作的核心在于使用教师模型——即作为裁判的LLM——来生成训练数据。我们还通过用各类教师（包括基于字符串的方法和LLM）对IK分类器进行评估，来衡量其稳健性，后者效果更佳。

> In this paper, we investigate how efficiently large language models (LLM) can be trained to check whether an answer is already stored in their parametric memory. We distill an LLM-as-a-judge to compute the IK (I Know) score. We found that this method is particularly beneficial in the context of retrieval-assisted augmented generation (RAG), with a respectable accuracy of 80%. It enables a significant reduction (more than 50%) in the number of search and reranking steps required for certain data sets. We have also introduced the IK score, which serves as a useful tool for characterising datasets by facilitating the classification task. Interestingly, through the inclusion of response tokens as input, our results suggest that only about 20,000 training samples are required to achieve good performance. The central element of this work is the use of a teacher model - the LLM as a judge - to generate training data. We also assess the robustness of the IK classifier by evaluating it with various types of teachers, including both string-based methods and LLMs, with the latter providing better results.

[Arxiv](https://arxiv.org/abs/2412.11536)