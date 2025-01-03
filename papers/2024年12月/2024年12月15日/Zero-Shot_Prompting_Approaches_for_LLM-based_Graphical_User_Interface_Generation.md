# 基于LLM的图形用户界面生成的零-shot提示方法

发布时间：2024年12月15日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来生成高保真度的图形用户界面（GUI）原型。论文提出了几种基于LLM的方法（如RAGG、PDGG和SCGG）来优化GUI生成，并进行了实验验证。这些方法直接应用了LLM的能力来解决实际问题，属于LLM在实际应用中的研究，因此应归类为LLM应用。` `用户界面设计` `软件开发`

> Zero-Shot Prompting Approaches for LLM-based Graphical User Interface Generation

# 摘要

> # 摘要
图形用户界面（GUI）原型设计是当今无处不在的交互式系统开发中的关键环节。GUI原型不仅有助于需求获取，还能与用户和开发团队共同测试、评估和验证设计理念。然而，GUI原型的创建过程耗时且资源密集。尽管现有研究主要聚焦于资源密集型的LLMs训练和微调，以生成低保真度的GUI，但我们探索了零-shot（ZS）提示在高保真度GUI生成中的潜力与效果。我们提出了一种检索增强的GUI生成（RAGG）方法，结合了基于LLM的GUI检索重排序和过滤机制，依托于一个大规模的GUI库。此外，我们还引入了提示分解（PDGG）和自我批评（SCGG）技术来优化GUI生成。为了验证这些ZS提示方法的有效性，我们对生成的GUI原型的准确性和用户满意度进行了全面评估。基于100多名UI/UX专家的3000多个GUI注释，我们的研究表明，相较于PDGG和RAGG，SCGG能够更有效地生成GUI，并揭示了LLMs在生成GUI原型时可能存在的缺陷。

> Graphical user interface (GUI) prototyping represents an essential activity in the development of interactive systems, which are omnipresent today. GUI prototypes facilitate elicitation of requirements and help to test, evaluate, and validate ideas with users and the development team. However, creating GUI prototypes is a time-consuming process and often requires extensive resources. While existing research for automatic GUI generation focused largely on resource-intensive training and fine-tuning of LLMs, mainly for low-fidelity GUIs, we investigate the potential and effectiveness of Zero-Shot (ZS) prompting for high-fidelity GUI generation. We propose a Retrieval-Augmented GUI Generation (RAGG) approach, integrated with an LLM-based GUI retrieval re-ranking and filtering mechanism based on a large-scale GUI repository. In addition, we adapt Prompt Decomposition (PDGG) and Self-Critique (SCGG) for GUI generation. To evaluate the effectiveness of the proposed ZS prompting approaches for GUI generation, we extensively evaluated the accuracy and subjective satisfaction of the generated GUI prototypes. Our evaluation, which encompasses over 3,000 GUI annotations from over 100 crowd-workers with UI/UX experience, shows that SCGG, in contrast to PDGG and RAGG, can lead to more effective GUI generation, and provides valuable insights into the defects that are produced by the LLMs in the generated GUI prototypes.

[Arxiv](https://arxiv.org/abs/2412.11328)