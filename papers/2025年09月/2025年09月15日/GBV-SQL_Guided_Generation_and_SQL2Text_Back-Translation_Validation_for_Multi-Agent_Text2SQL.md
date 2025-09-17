# GBV-SQL：面向多智能体文本转SQL的引导式生成及SQL到文本反向翻译验证

发布时间：2025年09月15日

`Agent` `基础理论`

> GBV-SQL: Guided Generation and SQL2Text Back-Translation Validation for Multi-Agent Text2SQL

# 摘要

> 大型语言模型虽已显著推动Text2SQL生成的发展，但一个关键问题仍未解决：语法正确的查询常与用户真实意图脱节，形成语义鸿沟。为此，我们提出新型多智能体框架GBV-SQL，其核心是基于SQL2Text回译验证的引导式生成机制。该机制通过专用智能体将生成的SQL反向翻译成自然语言，从而校验其与原始问题的逻辑是否一致。值得注意的是，我们的研究揭示了当前评估体系的一大隐患——基准测试集自身质量堪忧，这严重影响了评估结果的可靠性。我们将这类普遍存在于真实数据中的缺陷定义为“黄金错误”（Gold Errors），并构建了正式分类体系，揭示其如何掩盖模型的真实性能。实验显示，在极具挑战性的BIRD基准测试集上，GBV-SQL的执行准确率达63.23%，较现有方法绝对提升5.8%；而在剔除Spider基准测试集中的缺陷样本后，其开发集和测试集执行准确率更分别高达96.5%和97.6%。综上，我们的研究既构建了语义验证的稳健框架，也对基准测试集的完整性提出批判性反思，同时呼吁学界重视更严谨的数据集构建工作。

> While Large Language Models have significantly advanced Text2SQL generation, a critical semantic gap persists where syntactically valid queries often misinterpret user intent. To mitigate this challenge, we propose GBV-SQL, a novel multi-agent framework that introduces Guided Generation with SQL2Text Back-translation Validation. This mechanism uses a specialized agent to translate the generated SQL back into natural language, which verifies its logical alignment with the original question. Critically, our investigation reveals that current evaluation is undermined by a systemic issue: the poor quality of the benchmarks themselves. We introduce a formal typology for "Gold Errors", which are pervasive flaws in the ground-truth data, and demonstrate how they obscure true model performance. On the challenging BIRD benchmark, GBV-SQL achieves 63.23% execution accuracy, a 5.8% absolute improvement. After removing flawed examples, GBV-SQL achieves 96.5% (dev) and 97.6% (test) execution accuracy on the Spider benchmark. Our work offers both a robust framework for semantic validation and a critical perspective on benchmark integrity, highlighting the need for more rigorous dataset curation.

[Arxiv](https://arxiv.org/abs/2509.12612)