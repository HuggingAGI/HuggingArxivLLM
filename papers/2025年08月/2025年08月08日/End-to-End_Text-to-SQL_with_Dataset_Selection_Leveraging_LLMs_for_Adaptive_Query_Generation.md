# 端到端文本到SQL生成：基于数据集选择，利用LLMs实现自适应查询生成

发布时间：2025年08月08日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在文本到SQL转换任务中的应用，提出了一种新的三阶段框架，利用LLMs和提示工程来识别数据库意图并生成SQL查询。这属于将LLMs应用于具体任务的范畴，因此归类为LLM应用。` `数据库`

> End-to-End Text-to-SQL with Dataset Selection: Leveraging LLMs for Adaptive Query Generation

# 摘要

> 文本到SQL（Text-to-SQL）架起了自然语言与结构化数据库语言之间的桥梁，使非技术人员能够轻松查询数据库。传统方法将文本到SQL建模为直接翻译任务，其中给定的自然语言查询（NLQ）被映射到SQL命令。大型语言模型（LLMs）的最新进展显著提高了翻译准确性，然而，这些方法都需要目标数据库预先指定。这在涉及多个大型数据库的场景下成为一个问题，因为识别正确的数据库成为一个关键但常被忽视的步骤。本文中，我们提出了一种三阶段端到端的文本到SQL框架，在生成SQL查询之前识别用户的意图数据库。我们的方法利用LLMs和提示工程，从自然语言查询（NLQs）中提取隐含信息，形成规则集。然后，我们训练一个大型的数据库ID（db_id）预测模型，该模型包括一个基于RoBERTa的微调编码器，根据NLQ和LLM生成的规则预测正确的数据库标识符（db_id）。最后，我们使用批评代理来修正生成的SQL中的错误。实验结果表明，我们的框架在数据库意图预测和SQL生成准确性方面均优于当前最先进的模型。

> Text-to-SQL bridges the gap between natural language and structured database language, thus allowing non-technical users to easily query databases. Traditional approaches model text-to-SQL as a direct translation task, where a given Natural Language Query (NLQ) is mapped to an SQL command. Recent advances in large language models (LLMs) have significantly improved translation accuracy, however, these methods all require that the target database is pre-specified. This becomes problematic in scenarios with multiple extensive databases, where identifying the correct database becomes a crucial yet overlooked step. In this paper, we propose a three-stage end-to-end text-to-SQL framework to identify the user's intended database before generating SQL queries. Our approach leverages LLMs and prompt engineering to extract implicit information from natural language queries (NLQs) in the form of a ruleset. We then train a large db\_id prediction model, which includes a RoBERTa-based finetuned encoder, to predict the correct Database identifier (db\_id) based on both the NLQ and the LLM-generated rules. Finally, we refine the generated SQL by using critic agents to correct errors. Experimental results demonstrate that our framework outperforms the current state-of-the-art models in both database intent prediction and SQL generation accuracy.

[Arxiv](https://arxiv.org/abs/2508.06387)