# KRISTEVA：细读作为评估解释性推理的新基准测试。

发布时间：2025年05月14日

`LLM应用`

> KRISTEVA: Close Reading as a Novel Task for Benchmarking Interpretive Reasoning

# 摘要

> 每年，大学英语课程中都会撰写和批改数千万篇作文。学生们通过细读法（close reading）分析文学和文化文本，在这一过程中他们收集文本细节以形成基于证据的论点。尽管细读法被视为批判性思维的重要基础并在大学课程中被广泛采用为必修内容，但它从未在大型语言模型（LLMs）上进行过评估，且现有的多学科基准测试如MMLU也不包括文学科目。为填补这一空白，我们推出了KRISTEVA——首个专注于评估解释性推理的细读基准测试，包含1331个从课堂数据改编而来的问题。借助KRISTEVA，我们设计了三个难度逐步提升的任务集，以模拟细读过程的不同要素，并用它们来测试LLMs对文学作品的理解和推理能力：1）提取文体特征，2）从参数化知识中检索相关上下文信息，3）在文体与外部语境间进行多跳推理。我们的基线结果显示，尽管最先进的LLMs在某些细读任务上具备一定大学水平能力（准确率49.7% - 69.7%），但在我们11个任务中的10个任务上，它们的表现仍不及有经验的人类评估者。


> Each year, tens of millions of essays are written and graded in college-level English courses. Students are asked to analyze literary and cultural texts through a process known as close reading, in which they gather textual details to formulate evidence-based arguments. Despite being viewed as a basis for critical thinking and widely adopted as a required element of university coursework, close reading has never been evaluated on large language models (LLMs), and multi-discipline benchmarks like MMLU do not include literature as a subject. To fill this gap, we present KRISTEVA, the first close reading benchmark for evaluating interpretive reasoning, consisting of 1331 multiple-choice questions adapted from classroom data. With KRISTEVA, we propose three progressively more difficult sets of tasks to approximate different elements of the close reading process, which we use to test how well LLMs may seem to understand and reason about literary works: 1) extracting stylistic features, 2) retrieving relevant contextual information from parametric knowledge, and 3) multi-hop reasoning between style and external contexts. Our baseline results find that, while state-of-the-art LLMs possess some college-level close reading competency (accuracy 49.7% - 69.7%), their performances still trail those of experienced human evaluators on 10 out of our 11 tasks.

[Arxiv](https://arxiv.org/abs/2505.09825)