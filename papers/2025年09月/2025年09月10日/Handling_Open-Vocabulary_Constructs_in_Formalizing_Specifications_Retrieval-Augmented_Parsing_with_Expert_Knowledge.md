# 规格说明形式化中的开放词汇结构处理：结合专家知识的检索增强解析

发布时间：2025年09月10日

`RAG` `基础理论`

> Handling Open-Vocabulary Constructs in Formalizing Specifications: Retrieval-Augmented Parsing with Expert Knowledge

# 摘要

> 我们研究开放词汇构造（OVCs）问题——即事先未知的构造——具体场景为将自然语言（NL）规范转换为形式语言（如时态逻辑或代码）。由于缺乏必要的先验知识，模型在OVCs上表现欠佳。此时，领域专家可依据自身偏好或领域知识，在推理阶段提供正确构造。我们的目标是无需重新训练模型，即可将推理时专家提供的知识有效复用至未来的解析任务中。我们提出动态知识增强解析（DKAP）：除输入句子外，模型还接收（动态增长的）专家知识作为键值词典，该词典将NL短语与正确的OVC构造关联起来。我们提出ROLex——一种基于该词典的检索增强解析方法。通过训练检索器与生成器，使其能够查找并利用键值存储生成正确的解析结果。关键挑战之一是为此检索增强解析器整理数据。我们利用合成数据生成与数据增强技术，对带注释的（NL句子，FL语句）对进行处理，从而训练增强解析器。为提升训练效果，我们提出多种策略，引导模型关注检索知识中的相关子集。最后，我们设计了一种模仿DKAP问题的新评估范式，并在三个形式化任务（NL2LTL、NL2Code、NL2CMD）中模拟该场景。评估结果显示，DKAP极具挑战性，而ROLex通过有效利用动态专家知识，能够提升基线模型的性能。

> We study the problem of Open-Vocabulary Constructs(OVCs) -- ones not known beforehand -- in the context of converting natural language (NL) specifications into formal languages (e.g., temporal logic or code). Models fare poorly on OVCs due to a lack of necessary knowledge a priori. In such situations, a domain expert can provide correct constructs at inference time based on their preferences or domain knowledge. Our goal is to effectively reuse this inference-time, expert-provided knowledge for future parses without retraining the model. We present dynamic knowledge-augmented parsing(DKAP), where in addition to the input sentence, the model receives (dynamically growing) expert knowledge as a key-value lexicon that associates NL phrases with correct OVC constructs. We propose ROLex, a retrieval-augmented parsing approach that uses this lexicon. A retriever and a generator are trained to find and use the key-value store to produce the correct parse. A key challenge lies in curating data for this retrieval-augmented parser. We utilize synthetic data generation and the data augmentation techniques on annotated (NL sentence, FL statement) pairs to train the augmented parser. To improve training effectiveness, we propose multiple strategies to teach models to focus on the relevant subset of retrieved knowledge. Finally, we introduce a new evaluation paradigm modeled after the DKAP problem and simulate the scenario across three formalization tasks (NL2LTL, NL2Code, and NL2CMD). Our evaluations show that DKAP is a difficult challenge, and ROLex helps improve the performance of baseline models by using dynamic expert knowledge effectively.

[Arxiv](https://arxiv.org/abs/2509.08808)