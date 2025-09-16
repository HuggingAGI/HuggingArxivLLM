# CultureSynth：分层分类法引导的检索增强型文化问答合成框架

发布时间：2025年09月13日

`RAG` `基础理论`

> CultureSynth: A Hierarchical Taxonomy-Guided and Retrieval-Augmented Framework for Cultural Question-Answer Synthesis

# 摘要

> 文化胜任力——即理解并适应多元文化环境的能力——在全球场景下对大型语言模型（LLMs）而言愈发关键。尽管已有多项文化基准可用于评估LLMs的文化胜任力，但现有评估仍面临分类体系零散、领域局限突出及过度依赖人工数据标注等挑战。为应对这些问题，我们提出新型框架CultureSynth，该框架包含两部分：（1）全面的层级化多语言文化分类体系，覆盖12个一级主题与130个二级主题；（2）基于检索增强生成（RAG）的方法，借助事实知识合成具有文化相关性的问答对。CultureSynth-7合成基准包含19,360条数据，其中4,149条经人工验证，覆盖7种语言。对14款不同规模主流LLMs的评估结果显示，模型性能呈现明显分层，ChatGPT-4o-Latest与Qwen2.5-72B-Instruct位居前列。研究结果表明，模型需达到30亿参数规模才能具备基本文化胜任力，不同模型在知识处理上存在架构偏差，且各模型间的地域差异显著。我们认为，CultureSynth为开发具有文化感知能力的AI系统提供了可扩展框架，同时降低了对人工标注的依赖ootnote{基准可在https://github.com/Eyr3/CultureSynth获取。}。

> Cultural competence, defined as the ability to understand and adapt to multicultural contexts, is increasingly vital for large language models (LLMs) in global environments. While several cultural benchmarks exist to assess LLMs' cultural competence, current evaluations suffer from fragmented taxonomies, domain specificity, and heavy reliance on manual data annotation. To address these limitations, we introduce CultureSynth, a novel framework comprising (1) a comprehensive hierarchical multilingual cultural taxonomy covering 12 primary and 130 secondary topics, and (2) a Retrieval-Augmented Generation (RAG)-based methodology leveraging factual knowledge to synthesize culturally relevant question-answer pairs. The CultureSynth-7 synthetic benchmark contains 19,360 entries and 4,149 manually verified entries across 7 languages. Evaluation of 14 prevalent LLMs of different sizes reveals clear performance stratification led by ChatGPT-4o-Latest and Qwen2.5-72B-Instruct. The results demonstrate that a 3B-parameter threshold is necessary for achieving basic cultural competence, models display varying architectural biases in knowledge processing, and significant geographic disparities exist across models. We believe that CultureSynth offers a scalable framework for developing culturally aware AI systems while reducing reliance on manual annotation\footnote{Benchmark is available at https://github.com/Eyr3/CultureSynth.}.

[Arxiv](https://arxiv.org/abs/2509.10886)