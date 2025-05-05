# 如何通过差分隐私微调来增强大型语言模型的隐私防护能力？

发布时间：2025年05月01日

`LLM理论` `数据隐私` `人工智能安全`

> Can Differentially Private Fine-tuning LLMs Protect Against Privacy Attacks?

# 摘要

> 微调大型语言模型（LLMs）是适应专业任务的关键策略，但这一过程可能带来敏感数据泄露的隐私风险。尽管差分隐私（DP）在理论上能有效防止信息泄露，但其在LLMs上的实际效果尚不明确，尤其是在不同微调方法下。本文系统性研究了差分隐私在不同微调方法和隐私预算下的影响，通过数据提取和成员推断攻击评估实际隐私风险。我们的主要发现包括：（1）差分隐私降低了模型实用性，但其影响因微调方法而异。（2）未应用差分隐私时，不同方法微调的模型在隐私风险上存在显著差异。（3）即使在较高隐私预算下，应用差分隐私仍能大幅降低隐私风险。（4）不同微调方法在差分隐私下的隐私-效用权衡差异显著，某些方法因效用下降而不适合使用DP。这些发现为隐私保护的LLMs部署提供了实用指导，并为未来优化微调方法中的隐私-效用权衡研究奠定了基础。


> Fine-tuning large language models (LLMs) has become an essential strategy for adapting them to specialized tasks; however, this process introduces significant privacy challenges, as sensitive training data may be inadvertently memorized and exposed. Although differential privacy (DP) offers strong theoretical guarantees against such leakage, its empirical privacy effectiveness on LLMs remains unclear, especially under different fine-tuning methods. In this paper, we systematically investigate the impact of DP across fine-tuning methods and privacy budgets, using both data extraction and membership inference attacks to assess empirical privacy risks. Our main findings are as follows: (1) Differential privacy reduces model utility, but its impact varies significantly across different fine-tuning methods. (2) Without DP, the privacy risks of models fine-tuned with different approaches differ considerably. (3) When DP is applied, even a relatively high privacy budget can substantially lower privacy risk. (4) The privacy-utility trade-off under DP training differs greatly among fine-tuning methods, with some methods being unsuitable for DP due to severe utility degradation. Our results provide practical guidance for privacy-conscious deployment of LLMs and pave the way for future research on optimizing the privacy-utility trade-off in fine-tuning methodologies.

[Arxiv](https://arxiv.org/abs/2504.21036)