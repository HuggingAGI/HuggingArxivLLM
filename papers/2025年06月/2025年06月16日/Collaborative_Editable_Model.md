# # 协作式可编辑模型

发布时间：2025年06月16日

`LLM应用`

> Collaborative Editable Model

# 摘要

> 垂直领域大型语言模型（LLMs）在金融、医疗和法律等专业场景中发挥着重要作用，但其训练往往需要依赖大规模标注数据和大量计算资源，这严重阻碍了快速开发和持续迭代。为解决这一问题，我们提出了协作可编辑模型（CoEM）。该模型通过用户贡献的领域片段构建候选知识池，并结合用户与模型的交互对话、用户评分和归因分析，精准定位高价值知识片段。随后，通过上下文提示将这些片段注入模型，实现轻量级领域适配。借助这些高价值知识，LLM可以生成更准确且领域相关的文本内容。在金融信息场景中，我们从约120名用户收集了1.5万条反馈，并通过用户评分验证CoEM，评估生成见解的质量。结果显示，CoEM在特定领域生成方面取得了显著提升，同时避免了传统微调工作流的时间和计算开销。

> Vertical-domain large language models (LLMs) play a crucial role in specialized scenarios such as finance, healthcare, and law; however, their training often relies on large-scale annotated data and substantial computational resources, impeding rapid development and continuous iteration. To address these challenges, we introduce the Collaborative Editable Model (CoEM), which constructs a candidate knowledge pool from user-contributed domain snippets, leverages interactive user-model dialogues combined with user ratings and attribution analysis to pinpoint high-value knowledge fragments, and injects these fragments via in-context prompts for lightweight domain adaptation. With high-value knowledge, the LLM can generate more accurate and domain-specific content. In a financial information scenario, we collect 15k feedback from about 120 users and validate CoEM with user ratings to assess the quality of generated insights, demonstrating significant improvements in domain-specific generation while avoiding the time and compute overhead of traditional fine-tuning workflows.

[Arxiv](https://arxiv.org/abs/2506.14146)