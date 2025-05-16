# # 使用大型语言模型进行儿科脓毒症队列的上下文表型分析

发布时间：2025年05月14日

`LLM应用` `数据分析`

> Contextual Phenotyping of Pediatric Sepsis Cohort Using Large Language Models

# 摘要

> 患者亚群的聚类分析在个性化医疗和资源优化中扮演着关键角色。然而，传统聚类方法在面对高维、异质医疗数据时往往表现欠佳，且缺乏对数据背景的理解。本研究利用来自低收入国家的儿童脓毒症数据集，包含2,686条记录、28个数值变量和119个分类变量，对比了基于大型语言模型（LLM）的聚类方法与传统方法的效能。通过有无聚类目标的方式将患者记录转化为文本形式。采用量化LLAMA 3.1 8B、DeepSeek-R1-Distill-Llama-8B（结合低秩自适应技术LoRA）和Stella-En-400M-V5模型生成嵌入表示，并对这些嵌入进行K-means聚类。传统方法则包括UMAP和FAMD降维后的混合数据上的K-Medoids聚类。通过轮廓系数和统计检验评估了聚类的质量和独特性。结果显示，Stella-En-400M-V5模型获得了最高的轮廓系数（0.86）。LLAMA 3.1 8B在有聚类目标的情况下，随着聚类数量的增加表现更佳，成功识别出具有不同营养、临床和社会经济特征的患者亚群。基于LLM的方法通过捕捉更丰富的上下文信息和突出关键特征，显著优于传统技术。这些发现凸显了LLMs在资源有限环境中进行上下文表型分析和辅助决策的巨大潜力。

> Clustering patient subgroups is essential for personalized care and efficient resource use. Traditional clustering methods struggle with high-dimensional, heterogeneous healthcare data and lack contextual understanding. This study evaluates Large Language Model (LLM) based clustering against classical methods using a pediatric sepsis dataset from a low-income country (LIC), containing 2,686 records with 28 numerical and 119 categorical variables. Patient records were serialized into text with and without a clustering objective. Embeddings were generated using quantized LLAMA 3.1 8B, DeepSeek-R1-Distill-Llama-8B with low-rank adaptation(LoRA), and Stella-En-400M-V5 models. K-means clustering was applied to these embeddings. Classical comparisons included K-Medoids clustering on UMAP and FAMD-reduced mixed data. Silhouette scores and statistical tests evaluated cluster quality and distinctiveness. Stella-En-400M-V5 achieved the highest Silhouette Score (0.86). LLAMA 3.1 8B with the clustering objective performed better with higher number of clusters, identifying subgroups with distinct nutritional, clinical, and socioeconomic profiles. LLM-based methods outperformed classical techniques by capturing richer context and prioritizing key features. These results highlight potential of LLMs for contextual phenotyping and informed decision-making in resource-limited settings.

[Arxiv](https://arxiv.org/abs/2505.09805)