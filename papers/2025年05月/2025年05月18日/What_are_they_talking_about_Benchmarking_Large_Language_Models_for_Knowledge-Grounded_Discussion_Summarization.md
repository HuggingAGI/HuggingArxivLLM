# 他们在聊什么？评估大型语言模型在知识导向对话摘要中的表现

发布时间：2025年05月18日

`LLM应用` `对话摘要`

> What are they talking about? Benchmarking Large Language Models for Knowledge-Grounded Discussion Summarization

# 摘要

> 本研究聚焦于大型语言模型在结合讨论内容与背景知识进行摘要任务中的表现。这项研究旨在解决现有对话摘要系统中存在的旁观者困惑问题，这些问题源于系统仅依赖于对话信息。为此，我们将任务输出建模为背景摘要和观点摘要，并定义了两种标准化的摘要模式。为了支持评估，我们引入了首个基准数据集，其中包含由人工专家一致标注的高质量样本，并提出了一种新颖的层次化评估框架，该框架具有细致、可解释的指标。我们在结构化提示和自我反思范式下评估了12种大型语言模型。研究发现：(1) 大型语言模型在背景摘要的检索、生成以及观点摘要的整合方面存在困难。(2) 甚至顶级大型语言模型在两种模式下的平均表现也低于69%。(3) 当前大型语言模型在此任务上缺乏足够的自我评估和自我校正能力。

> In this work, we investigate the performance of LLMs on a new task that requires combining discussion with background knowledge for summarization. This aims to address the limitation of outside observer confusion in existing dialogue summarization systems due to their reliance solely on discussion information. To achieve this, we model the task output as background and opinion summaries and define two standardized summarization patterns. To support assessment, we introduce the first benchmark comprising high-quality samples consistently annotated by human experts and propose a novel hierarchical evaluation framework with fine-grained, interpretable metrics. We evaluate 12 LLMs under structured-prompt and self-reflection paradigms. Our findings reveal: (1) LLMs struggle with background summary retrieval, generation, and opinion summary integration. (2) Even top LLMs achieve less than 69% average performance across both patterns. (3) Current LLMs lack adequate self-evaluation and self-correction capabilities for this task.

[Arxiv](https://arxiv.org/abs/2505.12474)