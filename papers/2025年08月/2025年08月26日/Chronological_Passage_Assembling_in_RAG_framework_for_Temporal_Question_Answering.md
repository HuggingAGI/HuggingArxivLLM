# RAG框架中用于时间问答的时序段落组装

发布时间：2025年08月26日

`RAG` `基础理论`

> Chronological Passage Assembling in RAG framework for Temporal Question Answering

# 摘要

> 长上下文叙事问答任务颇具挑战，因为正确答案往往需要在有限的上下文窗口内重建连贯的事件时间线，同时还要保持上下文的流畅性。检索增强生成（RAG）索引方法试图通过选择性检索必要文档片段来应对这一难题，然而叙事文本的独特属性却限制了现有方法的效果。具体来说，理解叙事文本不能仅依靠孤立片段，更广泛的上下文及片段间的顺序关系对理解至关重要。为此，我们提出ChronoRAG——一种专为叙事文本设计的新型RAG框架。该方法聚焦两个核心要点：一是将分散的文档信息提炼为连贯且结构化的段落，二是通过明确捕捉和维护检索段落间的时间顺序来保留叙事脉络。我们在NarrativeQA数据集上进行实验，实证验证了ChronoRAG的有效性。结果表明，在需要事实识别和复杂顺序关系理解的任务中，该方法显著提升了性能，这也凸显了时间顺序推理在叙事问答中的关键作用。

> Long-context question answering over narrative tasks is challenging because correct answers often hinge on reconstructing a coherent timeline of events while preserving contextual flow in a limited context window. Retrieval-augmented generation (RAG) indexing methods aim to address this challenge by selectively retrieving only necessary document segments. However, narrative texts possess unique characteristics that limit the effectiveness of these existing approaches. Specifically, understanding narrative texts requires more than isolated segments, as the broader context and sequential relationships between segments are crucial for comprehension. To address these limitations, we propose ChronoRAG, a novel RAG framework specialized for narrative texts. This approach focuses on two essential aspects: refining dispersed document information into coherent and structured passages, and preserving narrative flow by explicitly capturing and maintaining the temporal order among retrieved passages. We empirically demonstrate the effectiveness of ChronoRAG through experiments on the NarrativeQA dataset, showing substantial improvements in tasks requiring both factual identification and comprehension of complex sequential relationships, underscoring that reasoning over temporal order is crucial in resolving narrative QA.

[Arxiv](https://arxiv.org/abs/2508.18748)