# 通过提示工程模拟检索增强生成，提升LLMs长上下文理解能力

发布时间：2025年02月17日

`RAG` `问答系统`

> Emulating Retrieval Augmented Generation via Prompt Engineering for Enhanced Long Context Comprehension in LLMs

# 摘要

> 本文针对大型语言模型（LLMs）理解超长上下文的挑战，提出了一种通过专门的提示工程和思维链（CoT）推理模拟检索增强生成（RAG）的方法。尽管近期的LLMs支持单次提示中包含超过10万的tokens，但单纯扩大上下文窗口并未在关键细节分散于海量输入时确保稳健的多跳推理。我们的方法将模型同时作为检索器和推理器：首先在长段落中标记相关片段，然后采用分步的CoT工作流整合这些证据。这种单次处理方法减少了对外部检索器的依赖，同时保持对关键片段的关注。我们在精选自BABILong的任务上评估了我们的方法，这些任务将标准的bAbI问答问题与大量干扰文本交织。与基线（无检索）和简单的RAG管道相比，我们的方法在处理多事实问题（如物体位置追踪、计数和不定知识）时更为准确。此外，我们分析了提示结构（包括问题顺序、相关文本标记和整体指令）对性能的影响。这些发现表明，优化的提示工程结合引导推理，可以提升LLMs的长上下文理解能力，并作为传统检索管道的轻量级替代方案。

> This paper addresses the challenge of comprehending very long contexts in Large Language Models (LLMs) by proposing a method that emulates Retrieval Augmented Generation (RAG) through specialized prompt engineering and chain-of-thought (CoT) reasoning. While recent LLMs support over 100,000 tokens in a single prompt, simply enlarging context windows has not guaranteed robust multi-hop reasoning when key details are scattered across massive input. Our approach treats the model as both the retriever and the reasoner: it first tags relevant segments within a long passage, then employs a stepwise CoT workflow to integrate these pieces of evidence. This single-pass method thereby reduces reliance on an external retriever, yet maintains focus on crucial segments. We evaluate our approach on selected tasks from BABILong, which interleaves standard bAbI QA problems with large amounts of distractor text. Compared to baseline (no retrieval) and naive RAG pipelines, our approach more accurately handles multi-fact questions such as object location tracking, counting, and indefinite knowledge. Furthermore, we analyze how prompt structure, including the order of question, relevant-text tags, and overall instructions, significantly affects performance. These findings underscore that optimized prompt engineering, combined with guided reasoning, can enhance LLMs' long-context comprehension and serve as a lightweight alternative to traditional retrieval pipelines.

[Arxiv](https://arxiv.org/abs/2502.12462)