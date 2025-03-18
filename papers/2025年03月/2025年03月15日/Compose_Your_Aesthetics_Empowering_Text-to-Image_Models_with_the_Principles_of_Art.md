# # 组成你的美学：用艺术原则赋予文本到图像模型力量，塑造独特美学风格

发布时间：2025年03月15日

`LLM应用` `人工智能`

> Compose Your Aesthetics: Empowering Text-to-Image Models with the Principles of Art

# 摘要

> 文本到图像（T2I）扩散模型凭借其生成高保真度图像的能力和易于使用的特性，受到了广泛应用。然而，这些模型常常会生成不吸引人的图像，与它们训练时使用的随机互联网图像类似。现有方法试图解决这一问题时，往往基于视觉美学具有普遍性的假设，这一假设具有局限性。在T2I生成场景中，美学应体现个性化，因此我们提出了一个全新的美学对齐任务，旨在将用户的美学偏好与生成结果相匹配。受到艺术品为美学研究提供独特视角的启发，我们采用艺术家使用的构图框架——即艺术原则（PoA）——来编码视觉美学。为了支持这项研究，我们构建了CompArt，这是一个基于WikiArt的大型构图艺术数据集，附有由具备能力的多模态LLM标注的PoA分析。通过利用LLMs的强大表达能力和训练一个轻量级且可迁移的适配器，我们证明T2I扩散模型能够通过用户指定的PoA条件实现10种构图控制。此外，我们设计了一个合适的评估框架来验证我们的方法的有效性。

> Text-to-Image (T2I) diffusion models (DM) have garnered widespread adoption due to their capability in generating high-fidelity outputs and accessibility to anyone able to put imagination into words. However, DMs are often predisposed to generate unappealing outputs, much like the random images on the internet they were trained on. Existing approaches to address this are founded on the implicit premise that visual aesthetics is universal, which is limiting. Aesthetics in the T2I context should be about personalization and we propose the novel task of aesthetics alignment which seeks to align user-specified aesthetics with the T2I generation output. Inspired by how artworks provide an invaluable perspective to approach aesthetics, we codify visual aesthetics using the compositional framework artists employ, known as the Principles of Art (PoA). To facilitate this study, we introduce CompArt, a large-scale compositional art dataset building on top of WikiArt with PoA analysis annotated by a capable Multimodal LLM. Leveraging the expressive power of LLMs and training a lightweight and transferrable adapter, we demonstrate that T2I DMs can effectively offer 10 compositional controls through user-specified PoA conditions. Additionally, we design an appropriate evaluation framework to assess the efficacy of our approach.

[Arxiv](https://arxiv.org/abs/2503.12018)