# MuRating：面向多语言大语言模型预训练的高质量数据筛选方法

发布时间：2025年07月02日

`LLM应用` `多语言处理` `数据质量评估`

> MuRating: A High Quality Data Selecting Approach to Multilingual Large Language Model Pretraining

# 摘要

> 数据质量对大型语言模型的表现至关重要，然而现有的基于模型的筛选方法几乎只关注英语。我们引入了MuRating，一个可扩展的框架，能够将高质量的英语数据质量信号转化为适用于17种目标语言的单一评分器。通过成对比较，MuRating聚合多个英语'评分者'，学习统一的文档质量评分。随后，它通过翻译将这些判断投射到单语、跨语和双语文本对上，训练一个多语言评估器。应用到网络数据上，MuRating选择平衡的英语和多语言内容子集，用于预训练一个12亿参数的LLaMA模型。与包括QuRater、AskLLM、DCLM等在内的强大基线方法相比，我们的方法在英语基准测试和多语言评估中的平均准确率均有所提升，尤其是在知识密集型任务上表现尤为突出。我们进一步分析了翻译忠实度、选择偏差以及叙述材料代表性不足的问题，并为未来的研究指明了方向。

> Data quality is a critical driver of large language model performance, yet existing model-based selection methods focus almost exclusively on English. We introduce MuRating, a scalable framework that transfers high-quality English data-quality signals into a single rater for 17 target languages. MuRating aggregates multiple English "raters" via pairwise comparisons to learn unified document-quality scores,then projects these judgments through translation to train a multilingual evaluator on monolingual, cross-lingual, and parallel text pairs. Applied to web data, MuRating selects balanced subsets of English and multilingual content to pretrain a 1.2 B-parameter LLaMA model. Compared to strong baselines, including QuRater, AskLLM, DCLM and so on, our approach boosts average accuracy on both English benchmarks and multilingual evaluations, with especially large gains on knowledge-intensive tasks. We further analyze translation fidelity, selection biases, and underrepresentation of narrative material, outlining directions for future work.

[Arxiv](https://arxiv.org/abs/2507.01785)