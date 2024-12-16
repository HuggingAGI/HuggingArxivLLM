# AdvPrefix：用于实现细微的 LLM 越狱的目标

发布时间：2024年12月13日

`LLM应用` `语言模型` `网络安全`

> AdvPrefix: An Objective for Nuanced LLM Jailbreaks

# 摘要

> 许多针对大型语言模型（LLMs）的越狱攻击都有一个共同目标：让模型以“Sure, here is （有害请求）”为前缀进行响应。不过，这一目标虽简单直接，却存在两个局限：对模型行为的控制有限，常导致响应不完整或不切实际；格式僵化，不利于优化。为克服这些局限，我们推出了 AdvPrefix，这一新的前缀强制目标能更精细地控制模型行为，且易于优化。我们的目标借助了依赖模型的前缀，依据两个标准自动选取：高的预填充攻击成功率和低的负对数似然。通过为单个用户请求使用多个前缀，还能进一步简化优化。AdvPrefix 能无缝融入现有的越狱攻击，免费提升其性能。比如，在 Llama-3 上，仅用我们的前缀替换 GCG 攻击的目标前缀，就能将精细的攻击成功率从 14%提升至 80%，这表明当前的对齐难以推广到未见过的前缀。我们的工作表明，越狱目标对于实现精细越狱至关重要。

> Many jailbreak attacks on large language models (LLMs) rely on a common objective: making the model respond with the prefix "Sure, here is (harmful request)". While straightforward, this objective has two limitations: limited control over model behaviors, often resulting in incomplete or unrealistic responses, and a rigid format that hinders optimization. To address these limitations, we introduce AdvPrefix, a new prefix-forcing objective that enables more nuanced control over model behavior while being easy to optimize. Our objective leverages model-dependent prefixes, automatically selected based on two criteria: high prefilling attack success rates and low negative log-likelihood. It can further simplify optimization by using multiple prefixes for a single user request. AdvPrefix can integrate seamlessly into existing jailbreak attacks to improve their performance for free. For example, simply replacing GCG attack's target prefixes with ours on Llama-3 improves nuanced attack success rates from 14% to 80%, suggesting that current alignment struggles to generalize to unseen prefixes. Our work demonstrates the importance of jailbreak objectives in achieving nuanced jailbreaks.

[Arxiv](https://arxiv.org/abs/2412.10321)