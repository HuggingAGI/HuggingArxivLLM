# MPCG：多轮角色条件生成——基于LLMs的错误信息演化建模

发布时间：2025年09月20日

`Agent` `基础理论`

> MPCG: Multi-Round Persona-Conditioned Generation for Modeling the Evolution of Misinformation with LLMs

# 摘要

> 错误信息在传播中不断演变，在语言、叙事框架和道德侧重点上不断调整，以适应新受众。然而，当前的错误信息检测方法却隐含假设错误信息是静态的。为此，我们提出MPCG——一个多轮、角色条件的框架，用于模拟具有不同意识形态视角的智能体如何对主张进行迭代重新解释。该方法利用未审查的大型语言模型（LLM）跨多轮生成特定角色的主张，每一轮生成均以先前轮次的输出为条件，从而能够研究错误信息的演变过程。我们通过人工与基于LLM的标注、认知努力指标（可读性、困惑度）、情感唤起指标（情感分析、道德性）、聚类、可行性及下游分类等多种方式对生成的主张进行评估。结果显示，人工标注与GPT-4o-mini标注高度一致，但在流畅度判断上存在较大分歧。生成的主张比原始主张需要更高的认知努力，并持续反映与角色对齐的情感及道德框架。聚类与余弦相似度分析证实，跨轮次存在语义漂移，但主题连贯性得以保留。可行性结果显示77%的可行性率，表明其适用于下游任务。分类结果显示，常用的错误信息检测器宏F1性能下降幅度高达49.7%。代码可通过https://github.com/bcjr1997/MPCG获取。

> Misinformation evolves as it spreads, shifting in language, framing, and moral emphasis to adapt to new audiences. However, current misinformation detection approaches implicitly assume that misinformation is static. We introduce MPCG, a multi-round, persona-conditioned framework that simulates how claims are iteratively reinterpreted by agents with distinct ideological perspectives. Our approach uses an uncensored large language model (LLM) to generate persona-specific claims across multiple rounds, conditioning each generation on outputs from the previous round, enabling the study of misinformation evolution. We evaluate the generated claims through human and LLM-based annotations, cognitive effort metrics (readability, perplexity), emotion evocation metrics (sentiment analysis, morality), clustering, feasibility, and downstream classification. Results show strong agreement between human and GPT-4o-mini annotations, with higher divergence in fluency judgments. Generated claims require greater cognitive effort than the original claims and consistently reflect persona-aligned emotional and moral framing. Clustering and cosine similarity analyses confirm semantic drift across rounds while preserving topical coherence. Feasibility results show a 77% feasibility rate, confirming suitability for downstream tasks. Classification results reveal that commonly used misinformation detectors experience macro-F1 performance drops of up to 49.7%. The code is available at https://github.com/bcjr1997/MPCG

[Arxiv](https://arxiv.org/abs/2509.16564)