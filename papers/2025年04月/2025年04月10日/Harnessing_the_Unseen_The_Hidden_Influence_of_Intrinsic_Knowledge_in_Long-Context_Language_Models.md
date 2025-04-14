# 驾驭无形：长上下文语言模型中的内在知识如何潜移默化地影响表现

发布时间：2025年04月10日

`LLM理论` `机器学习`

> Harnessing the Unseen: The Hidden Influence of Intrinsic Knowledge in Long-Context Language Models

# 摘要

> 近期长上下文模型（LCMs）的研究进展主要集中在如何利用外部上下文信息，而对大型语言模型内在知识的影响研究却相对较少。本研究探讨了这种内在知识对内容生成的影响，并发现随着上下文长度的增加，其影响逐渐增强。进一步研究表明，模型利用内在知识的能力（我们称之为内在检索能力）并不会与利用外在检索能力（通过外部知识提升性能）同步提升。此外，更好的外在检索能力可能会干扰模型有效利用自身知识，限制其潜力的充分发挥。为填补这一研究空白，我们设计了一种简单而有效的混合针在稻草堆测试，该测试从内在和外在检索能力两个维度综合评估模型性能，而非仅关注外在检索能力。实验结果表明，Qwen-2.5模型显著优于Llama-3.1模型，展现出更卓越的内在检索能力。值得注意的是，即使是性能更强的Llama-3.1-70B-Instruct模型，在长上下文模型条件下也未能表现出更好的性能，这凸显了从双检索能力角度评估模型的重要性。

> Recent advances in long-context models (LCMs), designed to handle extremely long input contexts, primarily focus on utilizing external contextual information, often leaving the influence of large language models' intrinsic knowledge underexplored. In this work, we investigate how this intrinsic knowledge affects content generation and demonstrate that its impact becomes increasingly pronounced as context length extends. Furthermore, we show that the model's ability to utilize intrinsic knowledge, which we call intrinsic retrieval ability, does not improve simultaneously with its ability to leverage contextual knowledge through extrinsic retrieval ability. Moreover, better extrinsic retrieval can interfere with the model's ability to use its own knowledge effectively, limiting its full potential. To bridge this gap, we design a simple yet effective Hybrid Needle-in-a-Haystack test that evaluates models based on their capabilities across both retrieval abilities, rather than solely emphasizing extrinsic retrieval ability. Our experimental results reveal that Qwen-2.5 models significantly outperform Llama-3.1 models, demonstrating superior intrinsic retrieval ability. Moreover, even the more powerful Llama-3.1-70B-Instruct model fails to exhibit better performance under LCM conditions, highlighting the importance of evaluating models from a dual-retrieval perspective.

[Arxiv](https://arxiv.org/abs/2504.08202)