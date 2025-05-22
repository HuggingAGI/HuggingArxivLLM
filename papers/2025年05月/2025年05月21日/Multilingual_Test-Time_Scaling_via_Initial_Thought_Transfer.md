# # 多语言测试时的缩放：通过初始思维迁移实现

发布时间：2025年05月21日

`LLM应用` `跨语言处理`

> Multilingual Test-Time Scaling via Initial Thought Transfer

# 摘要

> 测试时缩放作为一种广泛采用的推理阶段策略，已被证明能显著提升推理性能。然而，其有效性研究几乎完全局限于英语环境，其他语言的行为仍待探索。我们首次系统性地研究了多语言环境下测试时缩放的表现，评估了DeepSeek-R1-Distill-LLama-8B和DeepSeek-R1-Distill-Qwen-7B在高低资源拉丁语系语言中的表现。研究发现，不同语言在测试时缩放中的相对收益差异显著。此外，模型在推理过程中常常转向使用英语，即使在严格的单语提示下也是如此。我们进一步发现，低资源语言不仅在初始推理思路与英语有显著差异，而且在早期推理中生成内容的一致性较低。基于这些发现，我们提出了MITT（多语言初始思路迁移），一种无监督且轻量级的推理前缀微调方法，通过迁移高资源语言的推理前缀来提升所有语言的测试时缩放效果，解决多语言推理性能不一致的问题。MITT显著提升了DeepSeek-R1-Distill-Qwen-7B的推理性能，尤其对代表性不足的语言效果更为显著。

> Test-time scaling has emerged as a widely adopted inference-time strategy for boosting reasoning performance. However, its effectiveness has been studied almost exclusively in English, leaving its behavior in other languages largely unexplored. We present the first systematic study of test-time scaling in multilingual settings, evaluating DeepSeek-R1-Distill-LLama-8B and DeepSeek-R1-Distill-Qwen-7B across both high- and low-resource Latin-script languages. Our findings reveal that the relative gains from test-time scaling vary significantly across languages. Additionally, models frequently switch to English mid-reasoning, even when operating under strictly monolingual prompts. We further show that low-resource languages not only produce initial reasoning thoughts that differ significantly from English but also have lower internal consistency across generations in their early reasoning. Building on our findings, we introduce MITT (Multilingual Initial Thought Transfer), an unsupervised and lightweight reasoning prefix-tuning approach that transfers high-resource reasoning prefixes to enhance test-time scaling across all languages, addressing inconsistencies in multilingual reasoning performance. MITT significantly boosts DeepSeek-R1-Distill-Qwen-7B's reasoning performance, especially for underrepresented languages.

[Arxiv](https://arxiv.org/abs/2505.15508)