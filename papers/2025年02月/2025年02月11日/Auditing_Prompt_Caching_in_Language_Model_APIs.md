# 审核语言模型API中的提示缓存机制

发布时间：2025年02月11日

`LLM应用` `API安全` `隐私保护`

> Auditing Prompt Caching in Language Model APIs

# 摘要

> # 提示缓存
在大型语言模型（LLMs）中，提示缓存会导致数据相关的处理时间差异：缓存过的提示比未缓存的提示处理得更快。这些时间差异引入了侧信道计时攻击的风险。例如，如果缓存是跨用户共享的，攻击者可以通过快速的API响应时间识别出缓存的提示，从而获取其他用户提示的相关信息。由于提示缓存可能导致隐私泄露，因此API提供商的缓存策略透明度非常重要。为此，我们开发并实施了统计审计，以检测真实世界LLM API提供商中的提示缓存现象。我们发现包括OpenAI在内的七个API提供商存在跨用户的全局缓存共享，这可能导致用户提示的潜在隐私泄露。提示缓存引起的时间差异也可能导致模型架构信息的泄露。具体来说，我们发现证据表明OpenAI的嵌入模型是一个仅解码的Transformer模型，这一信息此前并未公开披露。

> Prompt caching in large language models (LLMs) results in data-dependent timing variations: cached prompts are processed faster than non-cached prompts. These timing differences introduce the risk of side-channel timing attacks. For example, if the cache is shared across users, an attacker could identify cached prompts from fast API response times to learn information about other users' prompts. Because prompt caching may cause privacy leakage, transparency around the caching policies of API providers is important. To this end, we develop and conduct statistical audits to detect prompt caching in real-world LLM API providers. We detect global cache sharing across users in seven API providers, including OpenAI, resulting in potential privacy leakage about users' prompts. Timing variations due to prompt caching can also result in leakage of information about model architecture. Namely, we find evidence that OpenAI's embedding model is a decoder-only Transformer, which was previously not publicly known.

[Arxiv](https://arxiv.org/abs/2502.07776)