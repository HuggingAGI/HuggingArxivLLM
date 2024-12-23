# 输入归因能够解释上下文学习所引发的归纳推理过程吗？

发布时间：2024年12月20日

`LLM理论` `机器学习` `归纳推理`

> Can Input Attributions Interpret the Inductive Reasoning Process Elicited in In-Context Learning?

# 摘要

> 在机器学习领域，阐释神经模型输出的原理一直颇具挑战，这在如今大型语言模型（LLMs）和上下文学习（ICL）的时代也不例外。谈到估计输入归因（IA），ICL 带来了新的难题，即在由一系列示例构成的提示中，究竟是哪个示例有助于识别待解决的任务/规则。为此，本文引入了受归纳推理中刺激设计贫困启发的综合诊断任务。在这里，大多数上下文示例在其潜在规则方面是模糊的，而一个关键示例能消除所展示任务的歧义。问题在于，传统的 IA 方法在解释 ICL 中的归纳推理过程时，能否识别出这样的示例。我们的实验得出了一些实用的发现，比如某种简单的 IA 方法效果最佳，而且模型越大，使用基于梯度的 IA 方法解释 ICL 通常就越困难。

> Elucidating the rationale behind neural models' outputs has been challenging in the machine learning field, which is indeed applicable in this age of large language models (LLMs) and in-context learning (ICL). When it comes to estimating input attributions (IA), ICL poses a new issue of interpreting which example in the prompt, consisting of a set of examples, contributed to identifying the task/rule to be solved. To this end, in this paper, we introduce synthetic diagnostic tasks inspired by the poverty of the stimulus design in inductive reasoning; here, most in-context examples are ambiguous w.r.t. their underlying rule, and one critical example disambiguates the task demonstrated. The question is whether conventional IA methods can identify such an example in interpreting the inductive reasoning process in ICL. Our experiments provide several practical findings; for example, a certain simple IA method works the best, and the larger the model, the generally harder it is to interpret the ICL with gradient-based IA methods.

[Arxiv](https://arxiv.org/abs/2412.15628)