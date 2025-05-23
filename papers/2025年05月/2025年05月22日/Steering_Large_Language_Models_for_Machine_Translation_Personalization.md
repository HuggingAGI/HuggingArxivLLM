# # 引导大型语言模型实现机器翻译个性化

发布时间：2025年05月22日

`LLM应用` `机器翻译` `文学翻译`

> Steering Large Language Models for Machine Translation Personalization

# 摘要

> 基于大型语言模型（LLMs）的高质量机器翻译系统极大地简化了生成反映特定风格约束的个性化翻译的流程。然而，在风格要求不那么明确且可能更难通过提示传达的场景下，这些系统仍然面临挑战。我们探讨了在资源有限的环境下个性化LLM生成翻译的各种策略，重点关注具有挑战性的文学翻译领域。我们研究了引导模型生成向个性化风格靠拢的提示策略和推理时干预方法，并提出了一种对比框架，利用从稀疏自动编码器中提取的潜在概念来识别突出的个性化属性。实验结果表明，引导方法在保持翻译质量的同时实现了强大的个性化效果。进一步研究发现，多轮提示和我们的引导方法对模型表示的影响相似，表明可能存在相似的机制在起作用。

> High-quality machine translation systems based on large language models (LLMs) have simplified the production of personalized translations reflecting specific stylistic constraints. However, these systems still struggle in settings where stylistic requirements are less explicit and might be harder to convey via prompting. We explore various strategies for personalizing LLM-generated translations in low-resource settings, focusing on the challenging literary translation domain. We explore prompting strategies and inference-time interventions for steering model generations towards a personalized style, and propose a contrastive framework exploiting latent concepts extracted from sparse autoencoders to identify salient personalization properties. Our results show that steering achieves strong personalization while preserving translation quality. We further examine the impact of steering on LLM representations, finding model layers with a relevant impact for personalization are impacted similarly by multi-shot prompting and our steering method, suggesting similar mechanism at play.

[Arxiv](https://arxiv.org/abs/2505.16612)