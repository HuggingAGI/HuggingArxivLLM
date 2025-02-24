# # ExpliCa: 评估大型语言模型的显式因果推理能力

发布时间：2025年02月21日

`LLM理论` `人工智能` `因果推理`

> ExpliCa: Evaluating Explicit Causal Reasoning in Large Language Models

# 摘要

> 大型语言模型（LLMs）在需要解释和推理准确性的任务中发挥越来越重要的作用。本文介绍了一个名为ExpliCa的新数据集，用于评估LLMs在明确因果推理方面的性能。ExpliCa创新性地整合了因果关系和时间关系，这些关系以不同的语言顺序呈现，并通过语言连接词明确表达。数据集还包含了基于众包的人类可接受性评分。我们采用提示和困惑度指标在ExpliCa上对LLMs进行了测试。经过对七种商业和开源LLMs的评估，我们发现即使是顶级模型也难以达到0.80的准确率。值得注意的是，模型往往将时间关系与因果关系混淆，且其性能还受到事件语言顺序的显著影响。最后，我们发现困惑度分数和提示性能受到模型规模的显著影响。

> Large Language Models (LLMs) are increasingly used in tasks requiring interpretive and inferential accuracy. In this paper, we introduce ExpliCa, a new dataset for evaluating LLMs in explicit causal reasoning. ExpliCa uniquely integrates both causal and temporal relations presented in different linguistic orders and explicitly expressed by linguistic connectives. The dataset is enriched with crowdsourced human acceptability ratings. We tested LLMs on ExpliCa through prompting and perplexity-based metrics. We assessed seven commercial and open-source LLMs, revealing that even top models struggle to reach 0.80 accuracy. Interestingly, models tend to confound temporal relations with causal ones, and their performance is also strongly influenced by the linguistic order of the events. Finally, perplexity-based scores and prompting performance are differently affected by model size.

[Arxiv](https://arxiv.org/abs/2502.15487)