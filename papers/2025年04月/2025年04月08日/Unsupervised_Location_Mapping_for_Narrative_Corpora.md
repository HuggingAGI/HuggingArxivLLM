# 无监督叙事语料库的地点映射

发布时间：2025年04月08日

`LLM应用`

> Unsupervised Location Mapping for Narrative Corpora

# 摘要

> 本研究提出了一种无监督位置映射任务，旨在将个人叙述的轨迹映射到包含大量叙述发生地点的空间位置图上。尽管这一任务基础且普遍，但目前针对叙述文本的空间映射研究寥寥无几。该任务分为两部分：(1) 通过文本中提到的地点构建“地图”，以及 (2) 从单个叙述中提取轨迹并定位在地图上。基于大型语言模型上下文长度的最新提升，我们提出了一种完全无监督的流水线方法，无需预先定义标签集。我们在两个领域进行了测试：(1) 大屠杀证词，以及 (2) 英国湖区文学作品。我们进行了内在和外在评估，结果令人鼓舞，为该任务设定了基准和评估实践，同时也揭示了相关挑战。

> This work presents the task of unsupervised location mapping, which seeks to map the trajectory of an individual narrative on a spatial map of locations in which a large set of narratives take place. Despite the fundamentality and generality of the task, very little work addressed the spatial mapping of narrative texts. The task consists of two parts: (1) inducing a ``map'' with the locations mentioned in a set of texts, and (2) extracting a trajectory from a single narrative and positioning it on the map. Following recent advances in increasing the context length of large language models, we propose a pipeline for this task in a completely unsupervised manner without predefining the set of labels. We test our method on two different domains: (1) Holocaust testimonies and (2) Lake District writing, namely multi-century literature on travels in the English Lake District. We perform both intrinsic and extrinsic evaluations for the task, with encouraging results, thereby setting a benchmark and evaluation practices for the task, as well as highlighting challenges.

[Arxiv](https://arxiv.org/abs/2504.05954)