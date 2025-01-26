# 欺骗模式的50种阴影：统一分类、多模态检测与安全影响

发布时间：2025年01月22日

`LLM应用

理由：这篇论文主要讨论了利用多模态大型语言模型（MLLMs）进行欺骗性模式检测的工具DPGuard的开发和应用。虽然论文涉及了欺骗性模式的分类和数据集的创建，但其核心在于利用LLM技术来解决实际问题，即自动检测用户界面中的欺骗性模式。因此，这篇论文应归类为LLM应用。` `网络安全` `用户界面设计`

> 50 Shades of Deceptive Patterns: A Unified Taxonomy, Multimodal Detection, and Security Implications

# 摘要

> # 摘要
欺骗性模式（DPs）是用户界面设计中故意设计的元素，旨在通过利用认知偏差来操纵用户做出非预期的决策，通常是为了公司或服务的利益。尽管许多研究已经探索了识别这些欺骗性模式的方法，但许多现有解决方案需要大量的人工干预，并且难以跟上欺骗性设计的演变。为了解决这些挑战，我们从安全和隐私的角度扩展了欺骗性模式的分类法，并细化了其类别和范围。我们通过整合现有小规模数据集和新样本，创建了一个包含6,725张图片和10,421个DP实例的全面数据集，这些实例来自移动应用和网站。然后，我们开发了DPGuard，这是一种利用商业多模态大型语言模型（MLLMs）进行欺骗性模式检测的新型自动工具。实验结果表明，DPGuard优于现有最先进的方法。最后，我们对2,000个流行的移动应用和网站进行了广泛的实证评估，结果显示23.61%的移动截图和47.27%的网站截图至少包含一个欺骗性模式实例。通过四个未探索的案例研究，我们强调了统一分类法在应对日益增长的互联网欺骗挑战中的关键重要性。

> Deceptive patterns (DPs) are user interface designs deliberately crafted to manipulate users into unintended decisions, often by exploiting cognitive biases for the benefit of companies or services. While numerous studies have explored ways to identify these deceptive patterns, many existing solutions require significant human intervention and struggle to keep pace with the evolving nature of deceptive designs. To address these challenges, we expanded the deceptive pattern taxonomy from security and privacy perspectives, refining its categories and scope. We created a comprehensive dataset of deceptive patterns by integrating existing small-scale datasets with new samples, resulting in 6,725 images and 10,421 DP instances from mobile apps and websites. We then developed DPGuard, a novel automatic tool leveraging commercial multimodal large language models (MLLMs) for deceptive pattern detection. Experimental results show that DPGuard outperforms state-of-the-art methods. Finally, we conducted an extensive empirical evaluation on 2,000 popular mobile apps and websites, revealing that 23.61% of mobile screenshots and 47.27% of website screenshots feature at least one deceptive pattern instance. Through four unexplored case studies that inform security implications, we highlight the critical importance of the unified taxonomy in addressing the growing challenges of Internet deception.

[Arxiv](https://arxiv.org/abs/2501.13351)