# Chengyu-Bench: 评估大型语言模型在中文成语理解与应用中的表现

发布时间：2025年06月22日

`LLM应用` `中文处理`

> Chengyu-Bench: Benchmarking Large Language Models for Chinese Idiom Understanding and Use

# 摘要

> 中文成语（Chengyu）是四字成语，浸润着历史和文化，其字面翻译往往无法完全传达其含义。这种复杂性使得语言模型难以正确理解和使用成语。现有的基准测试专注于狭窄的任务——多项选择填空、孤立翻译或简单的改写。我们引入Chengyu-Bench，一个包含三个任务的综合基准测试：(1) 评价性含义，将成语分类为积极或消极；(2) 适当性，检测上下文中成语的误用；(3) 开放式填空，在没有选项的情况下填充长篇文章中的空白。Chengyu-Bench包含2,937个人工验证的示例，涵盖来自多种语料库的1,765个常见成语。我们评估了领先的LLMs，发现它们在评价性含义任务中准确率超过95%，但在适当性任务中仅约85%，在开放式填空中仅约40%的top-1准确率。错误分析表明，大多数错误源于对成语含义的基本误解。Chengyu-Bench证明，尽管LLMs可以可靠地评估成语情感，但它们仍然难以掌握正确使用所需的文化和语境细微差别。基准和源代码可在以下链接获取：https://github.com/sofyc/ChengyuBench。

> Chinese idioms (Chengyu) are concise four-character expressions steeped in history and culture, whose literal translations often fail to capture their full meaning. This complexity makes them challenging for language models to interpret and use correctly. Existing benchmarks focus on narrow tasks - multiple-choice cloze tests, isolated translation, or simple paraphrasing. We introduce Chengyu-Bench, a comprehensive benchmark featuring three tasks: (1) Evaluative Connotation, classifying idioms as positive or negative; (2) Appropriateness, detecting incorrect idiom usage in context; and (3) Open Cloze, filling blanks in longer passages without options. Chengyu-Bench comprises 2,937 human-verified examples covering 1,765 common idioms sourced from diverse corpora. We evaluate leading LLMs and find they achieve over 95% accuracy on Evaluative Connotation, but only ~85% on Appropriateness and ~40% top-1 accuracy on Open Cloze. Error analysis reveals that most mistakes arise from fundamental misunderstandings of idiom meanings. Chengyu-Bench demonstrates that while LLMs can reliably gauge idiom sentiment, they still struggle to grasp the cultural and contextual nuances essential for proper usage. The benchmark and source code are available at: https://github.com/sofyc/ChengyuBench.

[Arxiv](https://arxiv.org/abs/2506.18105)