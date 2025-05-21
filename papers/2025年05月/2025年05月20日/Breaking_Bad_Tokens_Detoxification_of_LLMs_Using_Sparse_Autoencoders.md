# 消除有害标记：基于稀疏自编码器的 LLM 净化方法

发布时间：2025年05月20日

`LLM应用` `人工智能`

> Breaking Bad Tokens: Detoxification of LLMs Using Sparse Autoencoders

# 摘要

> 大型语言模型（LLMs）如今在用户端应用中无处不在，但它们仍然会产生令人不快的有毒输出，包括脏话、低俗内容和贬低性言论。尽管存在众多的 detoxification 方法，但大多数方法都采用广泛且表面的修复，因此很容易被 jailbreak 攻击绕过。在这篇文章中，我们利用稀疏自动编码器（SAEs）识别模型残差流中与毒性相关的方向，并使用相应的解码器向量进行针对性的激活引导。我们引入了三个级别的引导强度，并在 GPT-2 Small 和 Gemma-2-2B 上进行评估，揭示了毒性减少与语言流畅性之间的权衡。在更强的引导强度下，这些因果干预在减少毒性方面比有竞争力的基线方法高出 20%，尽管在 GPT-2 Small 上，流畅性可能会因强度不同而明显下降。至关重要的是，引导后的标准 NLP 基准分数保持稳定，表明模型的知识和一般能力得以保留。我们进一步表明，更宽的 SAE 中的特征分割阻碍了安全干预，强调了分离特征学习的重要性。我们的研究结果突显了基于 SAE 的因果干预在 LLM detoxification 中的潜力和当前限制，并进一步提出了更安全的语言模型部署的实际指南。

> Large language models (LLMs) are now ubiquitous in user-facing applications, yet they still generate undesirable toxic outputs, including profanity, vulgarity, and derogatory remarks. Although numerous detoxification methods exist, most apply broad, surface-level fixes and can therefore easily be circumvented by jailbreak attacks. In this paper we leverage sparse autoencoders (SAEs) to identify toxicity-related directions in the residual stream of models and perform targeted activation steering using the corresponding decoder vectors. We introduce three tiers of steering aggressiveness and evaluate them on GPT-2 Small and Gemma-2-2B, revealing trade-offs between toxicity reduction and language fluency. At stronger steering strengths, these causal interventions surpass competitive baselines in reducing toxicity by up to 20%, though fluency can degrade noticeably on GPT-2 Small depending on the aggressiveness. Crucially, standard NLP benchmark scores upon steering remain stable, indicating that the model's knowledge and general abilities are preserved. We further show that feature-splitting in wider SAEs hampers safety interventions, underscoring the importance of disentangled feature learning. Our findings highlight both the promise and the current limitations of SAE-based causal interventions for LLM detoxification, further suggesting practical guidelines for safer language-model deployment.

[Arxiv](https://arxiv.org/abs/2505.14536)