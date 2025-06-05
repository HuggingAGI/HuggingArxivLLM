# BPO：再探直接偏好优化中的偏好建模

发布时间：2025年06月04日

`LLM理论` `人工智能`

> BPO: Revisiting Preference Modeling in Direct Preference Optimization

# 摘要

> 直接偏好优化（DPO）作为一种流行方法，旨在使大型语言模型（LLMs）与人类偏好对齐。虽然DPO在保留选择和拒绝响应的相对顺序方面有效，但它常常忽视绝对奖励幅度。这种忽视不仅降低了选择响应的可能性，还增加了生成分布外响应的风险，导致性能不佳。我们称此问题为降级选择响应（DCR）。为了解决这一问题，我们提出了平衡偏好优化（BPO），这是一种通过平衡奖励边界和差距适配器动态平衡选择与拒绝响应优化的新框架。与以往方法不同，BPO能够从根本上解决DPO的DCR问题，而无需在损失函数中引入额外约束。在多个数学推理任务上的实验结果表明，BPO显著优于DPO，使用Llama-3.1-8B-Instruct时准确率提高了+10.1%（从18.8%到28.9%），使用Qwen2.5-Math-7B时提高了+11.7%（从35.0%到46.7%）。它还超越了DPO变体，相比IPO（43.1%）提高了+3.6%，相比SLiC（41.7%）提高了+5.0%，相比Cal-DPO（43.6%）提高了+3.1%。值得注意的是，我们的算法仅需一行代码修改，使其易于实现并与现有基于DPO的框架完全兼容。

> Direct Preference Optimization (DPO) have emerged as a popular method for aligning Large Language Models (LLMs) with human preferences. While DPO effectively preserves the relative ordering between chosen and rejected responses through pairwise ranking losses, it often neglects absolute reward magnitudes. This oversight can decrease the likelihood of chosen responses and increase the risk of generating out-of-distribution responses, leading to poor performance. We term this issue Degraded Chosen Responses (DCR).To address this issue, we propose Balanced Preference Optimization (BPO), a novel framework that dynamically balances the optimization of chosen and rejected responses through two key components: balanced reward margin and gap adaptor. Unlike previous methods, BPO can fundamentally resolve DPO's DCR issue, without introducing additional constraints to the loss function. Experimental results on multiple mathematical reasoning tasks show that BPO significantly outperforms DPO, improving accuracy by +10.1% with Llama-3.1-8B-Instruct (18.8% to 28.9%) and +11.7% with Qwen2.5-Math-7B (35.0% to 46.7%). It also surpasses DPO variants by +3.6% over IPO (43.1%), +5.0% over SLiC (41.7%), and +3.1% over Cal-DPO (43.6%) on the same model. Remarkably, our algorithm requires only a single line of code modification, making it simple to implement and fully compatible with existing DPO-based frameworks.

[Arxiv](https://arxiv.org/abs/2506.03557)