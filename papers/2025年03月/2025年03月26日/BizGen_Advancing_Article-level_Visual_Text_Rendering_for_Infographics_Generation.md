# # BizGen：提升文章级视觉文本呈现，助力信息图生成

发布时间：2025年03月26日

`LLM应用` `商业智能` `数据可视化`

> BizGen: Advancing Article-level Visual Text Rendering for Infographics Generation

# 摘要

> 最近，Flux和Ideogram 2.0等先进的文本到图像生成模型在句子级别的视觉文本呈现方面取得了显著进展。然而，我们关注更具挑战性的文章级别视觉文本呈现场景，并提出了一项新任务：基于用户提供的文章级别描述性提示和超密集布局，生成高质量的商业内容，包括信息图和幻灯片。这一任务面临两大核心挑战：显著更长的上下文长度和高质量商业内容数据的稀缺性。
与大多数专注于少量子区域和句子级别提示的先前工作不同，确保在包含数十甚至数百个子区域的商业内容中精准遵循超密集布局要困难得多。我们提出了两项关键技术贡献：(i) 构建了一个可扩展的高质量商业内容数据集Infographics-650K，通过实施分层检索增强的信息图生成方案，配备了超密集布局和提示；(ii) 提出了一种基于布局的交叉注意力机制，根据超密集布局将数十个区域级提示注入到一组裁剪区域的潜在空间中，并在推理过程中使用布局条件的CFG灵活优化每个子区域。
我们在BizEval提示集上展示了系统相较于Flux和SD3等SOTA模型的优越性能。此外，通过彻底的消融实验验证了各组件的有效性。我们希望Infographics-650K和BizEval能够推动商业内容生成领域的进一步发展。

> Recently, state-of-the-art text-to-image generation models, such as Flux and Ideogram 2.0, have made significant progress in sentence-level visual text rendering. In this paper, we focus on the more challenging scenarios of article-level visual text rendering and address a novel task of generating high-quality business content, including infographics and slides, based on user provided article-level descriptive prompts and ultra-dense layouts. The fundamental challenges are twofold: significantly longer context lengths and the scarcity of high-quality business content data.
  In contrast to most previous works that focus on a limited number of sub-regions and sentence-level prompts, ensuring precise adherence to ultra-dense layouts with tens or even hundreds of sub-regions in business content is far more challenging. We make two key technical contributions: (i) the construction of scalable, high-quality business content dataset, i.e., Infographics-650K, equipped with ultra-dense layouts and prompts by implementing a layer-wise retrieval-augmented infographic generation scheme; and (ii) a layout-guided cross attention scheme, which injects tens of region-wise prompts into a set of cropped region latent space according to the ultra-dense layouts, and refine each sub-regions flexibly during inference using a layout conditional CFG.
  We demonstrate the strong results of our system compared to previous SOTA systems such as Flux and SD3 on our BizEval prompt set. Additionally, we conduct thorough ablation experiments to verify the effectiveness of each component. We hope our constructed Infographics-650K and BizEval can encourage the broader community to advance the progress of business content generation.

[Arxiv](https://arxiv.org/abs/2503.20672)