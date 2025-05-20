# 批量自洽性显著提升 LLM 相关性评估与排序

发布时间：2025年05月18日

`LLM应用` `信息检索`

> Batched Self-Consistency Improves LLM Relevance Assessment and Ranking

# 摘要

> 针对特定信息需求，大型语言模型（LLMs）在候选文本相关性评估中发挥着越来越重要的作用，通常采用逐一评估的点式（PW）策略，即每次LLM调用仅评估一个候选文本。与此同时，研究表明，通过自洽性（即提示LLM以相同任务多次运行，可能以扰动方式，然后聚合结果），可以显著提升LLM性能。为了更好地利用自洽性优势，我们假设批量点式策略（即一次LLM调用中评估多个段落）比逐一PW方法更合适，因为更大的输入上下文可以在自洽性调用中引发更广泛的LLM采样。为此，我们提出了几种候选批量策略，通过子集重新选择和排列组合来创建跨自洽性调用的提示多样性。随后，我们在相关性评估和排序任务上测试了批量PW方法，对比了一一PW和列表式LLM排序基线（带与不带自洽性），使用了三个段落检索数据集和GPT-4o、Claude Sonnet 3以及Amazon Nova Pro模型。实验结果表明，批量PW方法在所有基线中表现最佳，并且显著放大了自洽性的积极效果。例如，在我们的法律搜索数据集中，GPT-4o一一PW排序的NDCG@10在无自洽性时为44.9%，带15次自洽性调用时提升至46.8%；而批量PW排序则从43.8%提升至51.3%。这一结果充分证明了批量处理在提升LLM性能方面的巨大潜力。

> Given some information need, Large Language Models (LLMs) are increasingly used for candidate text relevance assessment, typically using a one-by-one pointwise (PW) strategy where each LLM call evaluates one candidate at a time. Meanwhile, it has been shown that LLM performance can be improved through self-consistency: prompting the LLM to do the same task multiple times (possibly in perturbed ways) and then aggregating the responses. To take advantage of self-consistency, we hypothesize that batched PW strategies, where multiple passages are judged in one LLM call, are better suited than one-by-one PW methods since a larger input context can induce more diverse LLM sampling across self-consistency calls. We first propose several candidate batching strategies to create prompt diversity across self-consistency calls through subset reselection and permutation. We then test our batched PW methods on relevance assessment and ranking tasks against one-by-one PW and listwise LLM ranking baselines with and without self-consistency, using three passage retrieval datasets and GPT-4o, Claude Sonnet 3, and Amazon Nova Pro. We find that batched PW methods outperform all baselines, and show that batching can greatly amplify the positive effects of self-consistency. For instance, on our legal search dataset, GPT-4o one-by-one PW ranking NDCG@10 improves only from 44.9% to 46.8% without self-consistency vs. with 15 self consistency calls, while batched PW ranking improves from 43.8% to 51.3%, respectively.

[Arxiv](https://arxiv.org/abs/2505.12570)