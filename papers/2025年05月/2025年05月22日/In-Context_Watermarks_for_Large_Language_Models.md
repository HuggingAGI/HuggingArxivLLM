# # 大型语言模型的上下文水印技术

发布时间：2025年05月22日

`LLM应用` `AI伦理` `内容安全`

> In-Context Watermarks for Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在敏感领域的广泛应用，确保AI生成文本的来源追踪和责任归属变得尤为重要。然而，现有的水印技术大多受限于需要访问解码过程，这在实际应用中存在局限。例如，在学术同行评审中，不诚实的审稿人可能利用LLMs生成审稿意见，而会议组织者往往无法获取所使用的模型，却仍需检测AI生成的内容。针对这一问题，我们提出了基于上下文的水印技术（ICW），通过提示工程将水印嵌入生成文本，充分利用了LLMs的上下文学习和指令遵循能力。我们研究了四种不同粒度级别的ICW策略，并为每种策略设计了专门的检测方法。此外，我们还深入探讨了间接提示注入（IPI）这一特定场景，其中通过修改输入文档（如学术论文）来隐秘地触发水印嵌入。实验结果验证了ICW作为一种模型无关且实用的水印方法的可行性。更重要的是，随着LLMs能力的不断提升，ICW为实现可扩展且易于实现的内容归属提供了有前景的方向。

> The growing use of large language models (LLMs) for sensitive applications has highlighted the need for effective watermarking techniques to ensure the provenance and accountability of AI-generated text. However, most existing watermarking methods require access to the decoding process, limiting their applicability in real-world settings. One illustrative example is the use of LLMs by dishonest reviewers in the context of academic peer review, where conference organizers have no access to the model used but still need to detect AI-generated reviews. Motivated by this gap, we introduce In-Context Watermarking (ICW), which embeds watermarks into generated text solely through prompt engineering, leveraging LLMs' in-context learning and instruction-following abilities. We investigate four ICW strategies at different levels of granularity, each paired with a tailored detection method. We further examine the Indirect Prompt Injection (IPI) setting as a specific case study, in which watermarking is covertly triggered by modifying input documents such as academic manuscripts. Our experiments validate the feasibility of ICW as a model-agnostic, practical watermarking approach. Moreover, our findings suggest that as LLMs become more capable, ICW offers a promising direction for scalable and accessible content attribution.

[Arxiv](https://arxiv.org/abs/2505.16934)