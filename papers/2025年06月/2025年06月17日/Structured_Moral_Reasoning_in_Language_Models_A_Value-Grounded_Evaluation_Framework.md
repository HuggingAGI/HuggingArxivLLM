# 语言模型中的结构化道德推理：一种基于价值的评估框架

发布时间：2025年06月17日

`LLM应用` `伦理学` `社会学`

> Structured Moral Reasoning in Language Models: A Value-Grounded Evaluation Framework

# 摘要

> 大型语言模型（LLMs）正越来越多地被应用于需要道德理解的领域，但它们的推理往往浅薄且与人类推理存在偏差。与人类不同，人类的道德推理整合了情境权衡、价值体系和伦理理论，而LLMs常常依赖于表面模式，导致在道德和伦理复杂的场景中做出有偏见的决策。为了解决这一问题，我们提出了一种基于价值的框架，用于评估和提炼LLMs中的结构化道德推理。我们使用基于价值体系、伦理理论和认知推理策略的提示分类法，在四个道德数据集上对12个开源模型进行了基准测试。我们的评估由四个关键问题驱动：（1）推理是否能显著改善LLM在直接提示下的决策质量？（2）哪些类型的价值/伦理框架最能有效引导LLM推理？（3）哪些认知推理策略能带来更优的道德表现？（4）小型LLM是否能通过蒸馏获得道德能力？研究发现，带有明确道德结构的提示能持续提升准确性和连贯性，其中基于第一性原理的推理和Schwartz的关怀伦理框架带来了最大的性能提升。此外，我们的监督蒸馏方法能够将道德能力从大型模型转移到小型模型，且无需额外的推理成本。综上所述，我们的研究成果为构建可解释的、基于价值的模型提供了一条可扩展的路径。

> Large language models (LLMs) are increasingly deployed in domains requiring moral understanding, yet their reasoning often remains shallow, and misaligned with human reasoning. Unlike humans, whose moral reasoning integrates contextual trade-offs, value systems, and ethical theories, LLMs often rely on surface patterns, leading to biased decisions in morally and ethically complex scenarios. To address this gap, we present a value-grounded framework for evaluating and distilling structured moral reasoning in LLMs. We benchmark 12 open-source models across four moral datasets using a taxonomy of prompts grounded in value systems, ethical theories, and cognitive reasoning strategies. Our evaluation is guided by four questions: (1) Does reasoning improve LLM decision-making over direct prompting? (2) Which types of value/ethical frameworks most effectively guide LLM reasoning? (3) Which cognitive reasoning strategies lead to better moral performance? (4) Can small-sized LLMs acquire moral competence through distillation? We find that prompting with explicit moral structure consistently improves accuracy and coherence, with first-principles reasoning and Schwartz's + care-ethics scaffolds yielding the strongest gains. Furthermore, our supervised distillation approach transfers moral competence from large to small models without additional inference cost. Together, our results offer a scalable path toward interpretable and value-grounded models.

[Arxiv](https://arxiv.org/abs/2506.14948)