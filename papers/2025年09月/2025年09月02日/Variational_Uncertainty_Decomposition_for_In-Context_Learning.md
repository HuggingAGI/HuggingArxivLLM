# 上下文学习中的变分不确定性分解

发布时间：2025年09月02日

`LLM理论` `基础理论`

> Variational Uncertainty Decomposition for In-Context Learning

# 摘要

> 随着大型语言模型（LLMs）在上下文预测任务中的应用愈发广泛，理解上下文学习的不确定性来源成为保障可靠性的关键。上下文学习执行预测性贝叶斯推理这一最新假设，为贝叶斯不确定性估计——尤其是将不确定性分解为因上下文数据不足导致的认知不确定性和上下文预测任务固有的随机不确定性——提供了新途径。然而，由于底层贝叶斯模型的潜在参数后验难以处理，这一分解思路尚未得到充分探索。为此，本研究提出一种适用于上下文学习的变分不确定性分解框架：无需显式采样潜在参数后验，而是通过优化辅助查询作为探针，得到LLM上下文学习过程中随机不确定性的上界，进而推导出认知不确定性的下界。通过在合成与真实任务上的实验，我们从定量和定性角度均验证了：我们方法得到的分解不确定性具有认知与随机不确定性的理想特性。

> As large language models (LLMs) gain popularity in conducting prediction tasks in-context, understanding the sources of uncertainty in in-context learning becomes essential to ensuring reliability. The recent hypothesis of in-context learning performing predictive Bayesian inference opens the avenue for Bayesian uncertainty estimation, particularly for decomposing uncertainty into epistemic uncertainty due to lack of in-context data and aleatoric uncertainty inherent in the in-context prediction task. However, the decomposition idea remains under-explored due to the intractability of the latent parameter posterior from the underlying Bayesian model. In this work, we introduce a variational uncertainty decomposition framework for in-context learning without explicitly sampling from the latent parameter posterior, by optimising auxiliary queries as probes to obtain an upper bound to the aleatoric uncertainty of an LLM's in-context learning procedure, which also induces a lower bound to the epistemic uncertainty. Through experiments on synthetic and real-world tasks, we show quantitatively and qualitatively that the decomposed uncertainties obtained from our method exhibit desirable properties of epistemic and aleatoric uncertainty.

[Arxiv](https://arxiv.org/abs/2509.02327)