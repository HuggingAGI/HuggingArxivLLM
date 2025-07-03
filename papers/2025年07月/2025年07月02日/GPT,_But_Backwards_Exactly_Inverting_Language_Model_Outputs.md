# GPT的逆向工程：精确还原语言模型输出

发布时间：2025年07月02日

`LLM理论

论文摘要：现有审计技术试图识别大型语言模型中的潜在不良行为，而我们则从互补的角度解决另一个问题：如何精确还原导致特定输出的原始输入。这将有助于事后分析，并可能检测到虚假输出报告。

我们将精确输入重建定义为一个具有唯一全局最小值的离散优化问题，并提出了一种高效且基于梯度的算法SODA。该算法在输入搜索空间的连续松弛上运行，采用周期性重启和参数衰减策略。

通过在参数规模从33M到3B的大型语言模型上进行的全面实验，我们证明SODA显著优于现有方法。我们成功从下一个令牌的 logits 中完整恢复了79.5%的较短分布外输入，且无一误报。但对于长度超过15个令牌的输入序列，我们难以从输出中提取私密信息。

这表明目前的标准部署实践可能已为防止恶意使用我们的方法提供了足够的保护。我们的代码可在 https://doi.org/10.5281/zenodo.15539879 获取。` `人工智能` `信息安全`

> GPT, But Backwards: Exactly Inverting Language Model Outputs

# 摘要

> 现有审计技术试图识别大型语言模型中的潜在不良行为，而我们则从互补的角度解决另一个问题：如何精确还原导致特定输出的原始输入。这将有助于事后分析，并可能检测到虚假输出报告。

我们将精确输入重建定义为一个具有唯一全局最小值的离散优化问题，并提出了一种高效且基于梯度的算法SODA。该算法在输入搜索空间的连续松弛上运行，采用周期性重启和参数衰减策略。

通过在参数规模从33M到3B的大型语言模型上进行的全面实验，我们证明SODA显著优于现有方法。我们成功从下一个令牌的 logits 中完整恢复了79.5%的较短分布外输入，且无一误报。但对于长度超过15个令牌的输入序列，我们难以从输出中提取私密信息。

这表明目前的标准部署实践可能已为防止恶意使用我们的方法提供了足够的保护。我们的代码可在 https://doi.org/10.5281/zenodo.15539879 获取。

> While existing auditing techniques attempt to identify potential unwanted behaviours in large language models (LLMs), we address the complementary forensic problem of reconstructing the exact input that led to an existing LLM output - enabling post-incident analysis and potentially the detection of fake output reports. We formalize exact input reconstruction as a discrete optimisation problem with a unique global minimum and introduce SODA, an efficient gradient-based algorithm that operates on a continuous relaxation of the input search space with periodic restarts and parameter decay. Through comprehensive experiments on LLMs ranging in size from 33M to 3B parameters, we demonstrate that SODA significantly outperforms existing approaches. We succeed in fully recovering 79.5% of shorter out-of-distribution inputs from next-token logits, without a single false positive, but struggle to extract private information from the outputs of longer (15+ token) input sequences. This suggests that standard deployment practices may currently provide adequate protection against malicious use of our method. Our code is available at https://doi.org/10.5281/zenodo.15539879.

[Arxiv](https://arxiv.org/abs/2507.01693)