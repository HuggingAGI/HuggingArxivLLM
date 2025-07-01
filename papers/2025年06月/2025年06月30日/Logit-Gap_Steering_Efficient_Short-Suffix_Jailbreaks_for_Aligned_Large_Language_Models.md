# Logit-Gap引导：面向对齐大型语言模型的高效短后缀越狱方法

发布时间：2025年06月30日

`LLM应用` `人工智能` `模型安全`

> Logit-Gap Steering: Efficient Short-Suffix Jailbreaks for Aligned Large Language Models

# 摘要

> 我们提出了logit差引导（logit-gap steering），这是一种快速的越狱框架。该方法将与RLHF对齐的语言模型中的拒绝-肯定差距转化为对词汇表的单次遍历。通过一个可前向计算的分数，我们将差距缩减与KL惩罚和奖励偏移的轻量级代理相结合，实现了在不到一秒钟内完成“排序-求和-停止”扫描，并返回一个简短的后缀——与束搜索或梯度攻击相比，模型调用次数减少了两个数量级。这一后缀不仅能够推广到未见过的提示，还能在0.5B到70B的检查点之间扩展，同时保持主题连贯性，将单次攻击的成功率从基线水平显著提升至80-100%。此外，这些后缀揭示了句界奖励悬崖和其他对齐人工制品，为研究安全调优如何重塑内部表示提供了一种轻量级的探测方法。

> We introduce logit-gap steering, a fast jailbreak framework that casts the refusal-affirmation gap of RLHF-aligned language models as a single pass over the vocabulary. A forward-computable score blends gap reduction with lightweight proxies for KL penalty and reward shift, allowing a "sort-sum-stop" sweep to complete in under a second and return a short suffix--two orders of magnitude fewer model calls than beam or gradient attacks. The same suffix generalises to unseen prompts and scales from 0.5 B to 70 B checkpoints, lifting one-shot attack success from baseline levels to 80-100% while preserving topical coherence. Beyond efficiency, these suffixes expose sentence-boundary reward cliffs and other alignment artefacts, offering a lightweight probe into how safety tuning reshapes internal representations.

[Arxiv](https://arxiv.org/abs/2506.24056)