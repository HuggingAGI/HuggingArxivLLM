# HypoGeneAgent：基于Perturb-seq数据集的基因集聚类分辨率选择假设语言智能体

发布时间：2025年09月10日

`Agent` `医疗健康`

> HypoGeneAgent: A Hypothesis Language Agent for Gene-Set Cluster Resolution Selection Using Perturb-seq Datasets

# 摘要

> 大规模单细胞和扰动测序（Perturb-seq）研究通常需要先对细胞进行聚类，再用基因本体论（GO）术语注释每个集群，以阐明潜在的生物学程序。但这两个阶段（分辨率选择和功能注释）本质上都带有主观性，依赖于启发式方法和专家整理。为此，我们提出了HYPOGENEAGENT——一个由大型语言模型（LLM）驱动的框架，它将集群注释转变为可量化优化的任务。该框架首先让LLM扮演基因集分析师的角色，分析每个基因程序或扰动模块的内容，生成基于GO的假设排序列表，并附上校准后的置信分数。接着，我们用句子嵌入模型对所有预测描述进行嵌入，计算成对余弦相似度，再由智能体裁判组从两方面评分：（i）预测的内部一致性（同一集群内的平均相似度高，称为簇内一致性）；（ii）外部独特性（集群间的相似度低，称为簇间分离）。这两个指标结合后生成智能体导出的分辨率分数，当集群同时具备连贯性和互斥性时，该分数达到最高。在公开的K562 CRISPRi扰动测序数据集上进行初步测试时，我们的分辨率分数所选择的聚类粒度与已知通路的匹配度，优于轮廓分数、基因功能富集总结的模块性分数等经典指标。这些发现证实，LLM智能体可作为集群分辨率和功能注释的客观裁判，为单细胞多组学研究打造全自动、上下文感知的解释管道奠定了基础。

> Large-scale single-cell and Perturb-seq investigations routinely involve clustering cells and subsequently annotating each cluster with Gene-Ontology (GO) terms to elucidate the underlying biological programs. However, both stages, resolution selection and functional annotation, are inherently subjective, relying on heuristics and expert curation. We present HYPOGENEAGENT, a large language model (LLM)-driven framework, transforming cluster annotation into a quantitatively optimizable task. Initially, an LLM functioning as a gene-set analyst analyzes the content of each gene program or perturbation module and generates a ranked list of GO-based hypotheses, accompanied by calibrated confidence scores. Subsequently, we embed every predicted description with a sentence-embedding model, compute pair-wise cosine similarities, and let the agent referee panel score (i) the internal consistency of the predictions, high average similarity within the same cluster, termed intra-cluster agreement (ii) their external distinctiveness, low similarity between clusters, termed inter-cluster separation. These two quantities are combined to produce an agent-derived resolution score, which is maximized when clusters exhibit simultaneous coherence and mutual exclusivity. When applied to a public K562 CRISPRi Perturb-seq dataset as a preliminary test, our Resolution Score selects clustering granularities that exhibit alignment with known pathway compared to classical metrics such silhouette score, modularity score for gene functional enrichment summary. These findings establish LLM agents as objective adjudicators of cluster resolution and functional annotation, thereby paving the way for fully automated, context-aware interpretation pipelines in single-cell multi-omics studies.

[Arxiv](https://arxiv.org/abs/2509.09740)