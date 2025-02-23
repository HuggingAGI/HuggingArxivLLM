# # 摘要
架起桥梁：借助抽象查询模式和上下文模式标记，将自然语言问题转化为SQL查询

发布时间：2025年02月20日

`LLM应用` `数据库`

> Bridging the Gap: Transforming Natural Language Questions into SQL Queries via Abstract Query Pattern and Contextual Schema Markup

# 摘要

> 大型语言模型在众多任务中展现出卓越性能，尤其在文本到SQL领域，这得益于其强大的上下文学习能力。尽管如此，这些方法与人类表现仍存在显著差距，尤其是在处理复杂问题时。随着问题复杂性的提升，问题与SQL之间的差距愈发明显。我们发现两大核心问题：结构映射差距与词汇映射差距。针对这两大挑战，我们提出了基于LLM的高效SQL生成管道PAS-SQL，通过抽象查询模式（AQP）与上下文模式标记（CSM）有效缓解这些差距。AQP通过去除与数据库相关的信息，提取问题的结构模式，帮助我们找到结构相似的示例。CSM则将问题中与数据库相关的文本片段与数据库中的具体表或列相关联，从而缩小词汇映射差距。实验结果表明，PAS-SQL在Spider和BIRD数据集上表现优异。其中，PAS-SQL + GPT-4o在Spider基准测试中以87.9%的执行准确率树立新标杆，并在BIRD数据集上以64.67%的执行准确率取得领先成绩。

> Large language models have demonstrated excellent performance in many tasks, including Text-to-SQL, due to their powerful in-context learning capabilities. They are becoming the mainstream approach for Text-to-SQL. However, these methods still have a significant gap compared to human performance, especially on complex questions. As the complexity of questions increases, the gap between questions and SQLs increases. We identify two important gaps: the structural mapping gap and the lexical mapping gap. To tackle these two gaps, we propose PAS-SQL, an efficient SQL generation pipeline based on LLMs, which alleviates gaps through Abstract Query Pattern (AQP) and Contextual Schema Markup (CSM). AQP aims to obtain the structural pattern of the question by removing database-related information, which enables us to find structurally similar demonstrations. CSM aims to associate database-related text span in the question with specific tables or columns in the database, which alleviates the lexical mapping gap. Experimental results on the Spider and BIRD datasets demonstrate the effectiveness of our proposed method. Specifically, PAS-SQL + GPT-4o sets a new state-of-the-art on the Spider benchmark with an execution accuracy of 87.9\%, and achieves leading results on the BIRD dataset with an execution accuracy of 64.67\%.

[Arxiv](https://arxiv.org/abs/2502.14682)