# 谁的安全视角？深度DIVE数据集用于文本到图像模型的多视角对齐

发布时间：2025年07月15日

`LLM应用` `人工智能` `伦理学`

> Whose View of Safety? A Deep DIVE Dataset for Pluralistic Alignment of Text-to-Image Models

# 摘要

> 当前的文本到图像（T2I）模型常常忽略了人类经验的多样性，导致系统与人类价值观的不匹配。我们提倡多元对齐，即AI能够理解并引导至多样化的、常常相互冲突的人类价值观。我们的研究为在T2I模型中实现这一目标提供了三个核心贡献。

首先，我们引入了一个用于多样化交叉视觉评估（DIVE）的新数据集——这是首个用于多元对齐的多模态数据集。它通过一个大型的人口统计学交叉人类评分员池实现了对多样化安全视角的深度对齐，这些评分员在1000个提示中提供了丰富且细致入微的反馈，具有高度的可重复性，捕捉到了细微的安全感知。

其次，我们实证确认了人口统计学作为该领域多样化观点的重要代理，揭示了与常规评估不同的显著的、情境依赖的伤害感知差异。

最后，我们探讨了构建对齐T2I模型的启示，包括高效的数据收集策略、LLM判断能力以及模型引导至多样化视角的能力。

这项研究为构建更加公平和对齐的T2I系统提供了基础工具。内容警告：本文包含可能有害的敏感内容。

> Current text-to-image (T2I) models often fail to account for diverse human experiences, leading to misaligned systems. We advocate for pluralistic alignment, where an AI understands and is steerable towards diverse, and often conflicting, human values. Our work provides three core contributions to achieve this in T2I models. First, we introduce a novel dataset for Diverse Intersectional Visual Evaluation (DIVE) -- the first multimodal dataset for pluralistic alignment. It enable deep alignment to diverse safety perspectives through a large pool of demographically intersectional human raters who provided extensive feedback across 1000 prompts, with high replication, capturing nuanced safety perceptions. Second, we empirically confirm demographics as a crucial proxy for diverse viewpoints in this domain, revealing significant, context-dependent differences in harm perception that diverge from conventional evaluations. Finally, we discuss implications for building aligned T2I models, including efficient data collection strategies, LLM judgment capabilities, and model steerability towards diverse perspectives. This research offers foundational tools for more equitable and aligned T2I systems. Content Warning: The paper includes sensitive content that may be harmful.

[Arxiv](https://arxiv.org/abs/2507.13383)