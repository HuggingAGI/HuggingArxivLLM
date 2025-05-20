# 批量自洽性显著提升LLM相关性评估与排序效果

发布时间：2025年05月18日

`LLM应用` `信息检索`

> Batched Self-Consistency Improves LLM Relevance Assessment and Ranking

# 摘要

> 在面对信息需求时，大型语言模型（LLMs）正越来越多地被用于候选文本的相关性评估，通常采用逐点评估（PW）策略，即每次 LLM 调用只评估一个候选文本。同时，已有研究表明，通过自洽性（self-consistency）可以提升 LLM 的性能：即多次提示 LLM 执行同一任务（可能以扰动方式），然后聚合响应。为了更好地利用自洽性，我们假设批量 PW 策略（即在一次 LLM 调用中评估多个文本片段）比逐点 PW 方法更合适，因为更大的输入上下文可以在自洽性调用中引发更多样的 LLM 采样。我们提出几种候选批量策略，通过子集重新选择和排列组合来增加自洽性调用中的提示多样性。在相关性评估和排序任务上，我们使用三个文本片段检索数据集和 GPT-4o、Claude Sonnet 3 以及 Amazon Nova Pro 模型，测试了批量 PW 方法，并对比了逐点 PW 和列表式 LLM 排序基线（带或不带自洽性）。结果表明，批量 PW 方法优于所有基线，并且显著放大了自洽性的正面效果。例如，在我们的法律搜索数据集中，GPT-4o 的逐点 PW 排名 NDCG@10 在没有自洽性时从 44.9% 提升至 46.8%，而批量 PW 排名则从 43.8% 提升至 51.3%。


> Given some information need, Large Language Models (LLMs) are increasingly used for candidate text relevance assessment, typically using a one-by-one pointwise (PW) strategy where each LLM call evaluates one candidate at a time. Meanwhile, it has been shown that LLM performance can be improved through self-consistency: prompting the LLM to do the same task multiple times (possibly in perturbed ways) and then aggregating the responses. To take advantage of self-consistency, we hypothesize that batched PW strategies, where multiple passages are judged in one LLM call, are better suited than one-by-one PW methods since a larger input context can induce more diverse LLM sampling across self-consistency calls. We first propose several candidate batching strategies to create prompt diversity across self-consistency calls through subset reselection and permutation. We then test our batched PW methods on relevance assessment and ranking tasks against one-by-one PW and listwise LLM ranking baselines with and without self-consistency, using three passage retrieval datasets and GPT-4o, Claude Sonnet 3, and Amazon Nova Pro. We find that batched PW methods outperform all baselines, and show that batching can greatly amplify the positive effects of self-consistency. For instance, on our legal search dataset, GPT-4o one-by-one PW ranking NDCG@10 improves only from 44.9% to 46.8% without self-consistency vs. with 15 self consistency calls, while batched PW ranking improves from 43.8% to 51.3%, respectively.

[Arxiv](https://arxiv.org/abs/2505.12570)