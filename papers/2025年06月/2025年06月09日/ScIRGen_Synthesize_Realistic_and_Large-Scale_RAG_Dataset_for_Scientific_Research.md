# ScIRGen：面向科学研究的真实大规模 RAG 数据集生成方法

发布时间：2025年06月09日

`RAG` `数据科学`

> ScIRGen: Synthesize Realistic and Large-Scale RAG Dataset for Scientific Research

# 摘要

> 科学研究人员需要大量关于数据集的信息，以便有效地评估和发展理论和方法。这些信息需求通常隐含在特定的研究任务中，而不是在搜索查询中明确表达。然而，现有的科学检索和问答（QA）数据集通常处理简单直接的问题，这与现实世界中研究查询的分布并不一致。为了填补这一空白，我们开发了ScIRGen，这是一个用于科学问答和检索的数据生成框架，它更准确地反映了专业科学研究人员的信息需求，并利用它创建了一个大规模的科学检索增强生成（RAG）数据集，包含现实的查询、数据集和论文。在技术层面，我们设计了一种面向数据集的信息提取方法，利用学术论文来增强数据集的表示。然后，我们提出了一个基于认知分类法的问题生成框架，以确保合成问题的质量。我们还设计了一种基于大语言模型困惑度变化的自动过滤合成答案的方法，这种方法与人类对答案有效性的判断高度一致。综上所述，这些方法最终促成了包含61,000个问答的ScIRGen-Geo数据集的创建。我们在ScIRGen-Geo数据集上对代表性方法进行了基准测试，评估它们的问答和检索能力，发现当前方法在处理复杂问题时仍然存在问题。这项工作推动了更复杂工具的发展，以支持科学界复杂的的信息需求。

> Scientific researchers need intensive information about datasets to effectively evaluate and develop theories and methodologies. The information needs regarding datasets are implicitly embedded in particular research tasks, rather than explicitly expressed in search queries. However, existing scientific retrieval and question-answering (QA) datasets typically address straightforward questions, which do not align with the distribution of real-world research inquiries. To bridge this gap, we developed ScIRGen, a dataset generation framework for scientific QA \& retrieval that more accurately reflects the information needs of professional science researchers, and uses it to create a large-scale scientific retrieval-augmented generation (RAG) dataset with realistic queries, datasets and papers. Technically, we designed a dataset-oriented information extraction method that leverages academic papers to augment the dataset representation. We then proposed a question generation framework by employing cognitive taxonomy to ensure the quality of synthesized questions. We also design a method to automatically filter synthetic answers based on the perplexity shift of LLMs, which is highly aligned with human judgment of answers' validity. Collectively, these methodologies culminated in the creation of the 61k QA dataset, ScIRGen-Geo. We benchmarked representative methods on the ScIRGen-Geo dataset for their question-answering and retrieval capabilities, finding out that current methods still suffer from reasoning from complex questions. This work advances the development of more sophisticated tools to support the intricate information needs of the scientific community.

[Arxiv](https://arxiv.org/abs/2506.11117)