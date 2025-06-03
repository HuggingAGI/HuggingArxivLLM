# 不考虑上下文信息：评估大型语言模型对指示元素的理解能力

发布时间：2025年06月01日

`LLM应用` `语言学`

> Un-considering Contextual Information: Assessing LLMs' Understanding of Indexical Elements

# 摘要

> 大型语言模型（LLMs）在共指消解任务中表现卓越，但此前研究主要关注名词和第三人称代词的消解。本研究首次聚焦于指示代词（如I, you, here和tomorrow）的共指消解，这些代词因语言特性而更具挑战性。我们发布了包含1600个多项选择题的英语指示代词数据集，并评估了GPT-4o、Claude 3.5 Sonnet、Gemini 1.5 Pro和DeepSeek V3等先进模型。结果显示，LLMs在处理部分指示代词（如I）时表现出色，但对you、here和tomorrow等则较为吃力。此外，句法线索（如引语）对某些指示代词的性能有正向作用，而对其他指示代词则可能产生负面影响。代码和数据已开源，详情请访问：https://github.com/metehanoguzz/LLMs-Indexicals-English.

> Large Language Models (LLMs) have demonstrated impressive performances in tasks related to coreference resolution. However, previous studies mostly assessed LLM performance on coreference resolution with nouns and third person pronouns. This study evaluates LLM performance on coreference resolution with indexical like I, you, here and tomorrow, which come with unique challenges due to their linguistic properties. We present the first study examining how LLMs interpret indexicals in English, releasing the English Indexical Dataset with 1600 multiple-choice questions. We evaluate pioneering LLMs, including GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro, and DeepSeek V3. Our results reveal that LLMs exhibit an impressive performance with some indexicals (I), while struggling with others (you, here, tomorrow), and that syntactic cues (e.g. quotation) contribute to LLM performance with some indexicals, while they reduce performance with others. Code and data are available at: https://github.com/metehanoguzz/LLMs-Indexicals-English.

[Arxiv](https://arxiv.org/abs/2506.01089)