# 语言模型的调色板：一个用于受控文本生成的工具

发布时间：2025年03月14日

`LLM应用

<example>
论文摘要：将文本信息表示为实数嵌入已成为 NLP 的规范。此外，随着公众对大型语言模型 (LLM) 兴趣的增加，嵌入即服务 (EaaS) 作为一种商业模式迅速受到关注。这并非没有突出的安全风险，因为之前的研究已经证明，即使不了解生成敏感数据的底层模型，也可以从嵌入中重建敏感数据。然而，此类工作因其仅关注英语而受到限制，使得所有其他语言都容易受到恶意行为者的攻击。由于许多国际和多语言公司利用 EaaS，迫切需要研究多语言 LLM 安全性。为此，本工作从多语言嵌入反转的角度研究LLM安全性。具体来说，我们定义了黑盒多语言和跨语言反转攻击问题，特别关注跨域场景。我们的研究结果表明，多语言模型可能比单语言模型更容易受到反转攻击。这是因为在底层语言事先未知的情况下，实现可比较的反演性能所需的数据量减少了。据我们所知，这项工作是第一个在反转攻击的背景下深入研究多语言性的工作，我们的发现强调了在 NLP 安全领域进一步调查和加强防御的必要性。
LLM应用
</example>

论文摘要：大型语言模型的突破性进展彻底革新了文本生成领域，其卓越能力令人瞩目。在适当提示下，这些模型能够生成严格符合特定要求的可控文本。然而，设计一个能够同时控制多个属性的最优提示往往充满挑战。线性组合单属性模型是常见的方法，但这种方法常常忽视属性重叠，可能导致冲突。因此，我们提出了一种基于全概率法则和条件互信息最小化启发的新型组合策略，并将其应用于生成语言模型。该方法针对单属性控制场景进行了调整，由于其在属性强度与生成风格之间建立了理论联系，类似于艺术家调色板上混合颜色，因此被命名为“语言模型调色板”。此外，我们还提出了正相关性和属性增强作为理论特性，以指导合理组合策略的设计。我们在单控制和多控制设置下进行了实验，取得了超越现有方法的优异结果。

LLM应用` `文本生成`

> Palette of Language Models: A Solver for Controlled Text Generation

# 摘要

> 大型语言模型的突破性进展彻底革新了文本生成领域，其卓越能力令人瞩目。在适当提示下，这些模型能够生成严格符合特定要求的可控文本。然而，设计一个能够同时控制多个属性的最优提示往往充满挑战。线性组合单属性模型是常见的方法，但这种方法常常忽视属性重叠，可能导致冲突。因此，我们提出了一种基于全概率法则和条件互信息最小化启发的新型组合策略，并将其应用于生成语言模型。该方法针对单属性控制场景进行了调整，由于其在属性强度与生成风格之间建立了理论联系，类似于艺术家调色板上混合颜色，因此被命名为“语言模型调色板”。此外，我们还提出了正相关性和属性增强作为理论特性，以指导合理组合策略的设计。我们在单控制和多控制设置下进行了实验，取得了超越现有方法的优异结果。


> Recent advancements in large language models have revolutionized text generation with their remarkable capabilities. These models can produce controlled texts that closely adhere to specific requirements when prompted appropriately. However, designing an optimal prompt to control multiple attributes simultaneously can be challenging. A common approach is to linearly combine single-attribute models, but this strategy often overlooks attribute overlaps and can lead to conflicts. Therefore, we propose a novel combination strategy inspired by the Law of Total Probability and Conditional Mutual Information Minimization on generative language models. This method has been adapted for single-attribute control scenario and is termed the Palette of Language Models due to its theoretical linkage between attribute strength and generation style, akin to blending colors on an artist's palette. Moreover, positive correlation and attribute enhancement are advanced as theoretical properties to guide a rational combination strategy design. We conduct experiments on both single control and multiple control settings, and achieve surpassing results.

[Arxiv](https://arxiv.org/abs/2503.11182)