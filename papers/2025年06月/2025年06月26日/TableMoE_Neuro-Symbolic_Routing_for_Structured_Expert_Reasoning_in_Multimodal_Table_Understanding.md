# TableMoE：多模态表格理解中结构化专家推理的神经符号路由方案

发布时间：2025年06月26日

`LLM应用`

> TableMoE: Neuro-Symbolic Routing for Structured Expert Reasoning in Multimodal Table Understanding

# 摘要

> 多模态在现实场景下的表格理解面临诸多挑战，包括复杂的结构、密集的符号以及视觉退化问题（如模糊、倾斜、水印、不完整结构或字体、多跨或层次嵌套布局等）。现有的多模态大语言模型（MLLMs）在应对WildStruct条件时表现吃力，导致性能受限和泛化能力差。为了解决这些挑战，我们提出了TableMoE，这是一种专门用于多模态表格数据的健壮结构化推理的神经符号混合连接专家（MoCE）架构。TableMoE的创新之处在于其神经符号路由机制，能够预测潜在的语义标记角色（如表头、数据单元格、轴、公式），并根据符号推理图提供的置信度感知门控策略，动态将表格元素路由到专门的专家（如Table-to-HTML、Table-to-JSON、Table-to-Code）。为了促进有效的对齐驱动预训练，我们引入了大规模的TableMoE-Align数据集，包含来自金融、科学、生物医学和工业领域的120万个表格-HTML-JSON-代码四元组，专用于模型预训练。在评估方面，我们整理并发布了四个具有挑战性的WildStruct基准测试：WMMFinQA、WMMTatQA、WMMTabDialog和WMMFinanceMath，这些基准专门设计用于在现实世界的多模态退化和结构复杂性下对模型进行压力测试。实验结果表明，TableMoE显著超越现有的最先进模型。广泛的消融研究验证了每个核心组件，强调了神经符号路由和结构专家对齐的关键作用。通过定性分析，我们进一步展示了TableMoE的可解释性和增强的鲁棒性，突显了将神经符号推理整合到多模态表格理解中的有效性。

> Multimodal understanding of tables in real-world contexts is challenging due to the complexity of structure, symbolic density, and visual degradation (blur, skew, watermarking, incomplete structures or fonts, multi-span or hierarchically nested layouts). Existing multimodal large language models (MLLMs) struggle with such WildStruct conditions, resulting in limited performance and poor generalization. To address these challenges, we propose TableMoE, a neuro-symbolic Mixture-of-Connector-Experts (MoCE) architecture specifically designed for robust, structured reasoning over multimodal table data. TableMoE features an innovative Neuro-Symbolic Routing mechanism, which predicts latent semantic token roles (e.g., header, data cell, axis, formula) and dynamically routes table elements to specialized experts (Table-to-HTML, Table-to-JSON, Table-to-Code) using a confidence-aware gating strategy informed by symbolic reasoning graphs. To facilitate effective alignment-driven pretraining, we introduce the large-scale TableMoE-Align dataset, consisting of 1.2M table-HTML-JSON-code quadruples across finance, science, biomedicine and industry, utilized exclusively for model pretraining. For evaluation, we curate and release four challenging WildStruct benchmarks: WMMFinQA, WMMTatQA, WMMTabDialog, and WMMFinanceMath, designed specifically to stress-test models under real-world multimodal degradation and structural complexity. Experimental results demonstrate that TableMoE significantly surpasses existing state-of-the-art models. Extensive ablation studies validate each core component, emphasizing the critical role of Neuro-Symbolic Routing and structured expert alignment. Through qualitative analyses, we further showcase TableMoE's interpretability and enhanced robustness, underscoring the effectiveness of integrating neuro-symbolic reasoning for multimodal table understanding.

[Arxiv](https://arxiv.org/abs/2506.21393)