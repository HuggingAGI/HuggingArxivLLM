# RECALL-MM：一个多模态消费者产品召回数据集，助力基于计算方法和大型语言模型的风险分析

发布时间：2025年03月29日

`LLM应用` `工程设计` `数据科学`

> RECALL-MM: A Multimodal Dataset of Consumer Product Recalls for Risk Analysis using Computational Methods and Large Language Models

# 摘要

> 产品召回为工程设计中的潜在风险提供了宝贵见解，但其潜力仍未被充分利用。我们从美国消费者产品安全委员会（CPSC）召回数据库中整理数据，构建了多模态数据集RECALL-MM，利用历史信息进行数据驱动的风险评估，并通过生成方法增强数据。数据集模式显示了改进安全措施的关键领域。我们通过交互式聚类图将所有召回嵌入共享潜在空间，基于召回描述和产品名称进行分析。利用这些工具，我们通过三个案例展示了数据集在识别风险和指导安全设计中的价值。

前两个案例展示了设计师如何通过可视化召回产品模式，将新产品定位在召回背景下，从而主动预见风险。第三个案例则通过仅使用产品图像，利用大型语言模型（LLM）预测潜在危害，展示了模型在视觉上下文中识别风险的能力，并与历史数据高度一致。然而，分析也指出了危害预测的挑战性，强调了设计过程中保持风险意识的重要性。

本研究旨在通过数据驱动方法弥合历史召回与未来安全之间的差距，为更安全的工程设计提供了可扩展的解决方案。


> Product recalls provide valuable insights into potential risks and hazards within the engineering design process, yet their full potential remains underutilized. In this study, we curate data from the United States Consumer Product Safety Commission (CPSC) recalls database to develop a multimodal dataset, RECALL-MM, that informs data-driven risk assessment using historical information, and augment it using generative methods. Patterns in the dataset highlight specific areas where improved safety measures could have significant impact. We extend our analysis by demonstrating interactive clustering maps that embed all recalls into a shared latent space based on recall descriptions and product names. Leveraging these data-driven tools, we explore three case studies to demonstrate the dataset's utility in identifying product risks and guiding safer design decisions. The first two case studies illustrate how designers can visualize patterns across recalled products and situate new product ideas within the broader recall landscape to proactively anticipate hazards. In the third case study, we extend our approach by employing a large language model (LLM) to predict potential hazards based solely on product images. This demonstrates the model's ability to leverage visual context to identify risk factors, revealing strong alignment with historical recall data across many hazard categories. However, the analysis also highlights areas where hazard prediction remains challenging, underscoring the importance of risk awareness throughout the design process. Collectively, this work aims to bridge the gap between historical recall data and future product safety, presenting a scalable, data-driven approach to safer engineering design.

[Arxiv](https://arxiv.org/abs/2503.23213)