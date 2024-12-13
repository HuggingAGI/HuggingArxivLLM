# 用于材料研究的基础大型语言模型

发布时间：2024年12月12日

`LLM应用` `材料科学` `人工智能`

> Foundational Large Language Models for Materials Research

# 摘要

> 材料的发现与开发对于应对全球挑战意义重大。然而，材料科学文献的指数式增长，其中包含海量文本数据，这在知识提取、整合及科学推理方面造成了严重瓶颈。大型语言模型（LLMs）为加速材料研究带来了前所未有的机遇，可通过自动分析和预测来达成。但它们的有效运用需要针对特定领域进行适配，以理解和解决领域相关任务。在此，我们推出 LLaMat，这是一系列用于材料科学的基础模型，是在大量材料文献和晶体学数据的语料库上对 LLaMA 模型持续预训练所得。通过系统评估，我们证实 LLaMat 在材料专属的自然语言处理和结构化信息提取方面表现卓越，同时具备一般语言能力。专门的 LLaMat-CIF 变体在晶体结构生成方面展现出空前的能力，能够预测周期表中高覆盖率的稳定晶体。有趣的是，尽管 LLaMA-3 比 LLaMA-2 性能更出色，但我们发现 LLaMat-2 在各类材料科学任务中，包括从文本和表格中提取结构化信息，尤其是在晶体结构生成方面，呈现出意外增强的特定领域性能，这或许是过度训练的 LLMs 中存在的一种潜在适应僵化。总之，本项工作证明了领域适配对于开发可实际应用于材料研究的 LLM 协作者的有效性。除材料科学外，我们的研究成果揭示了 LLMs 领域适配的重要考量因素，如模型选择、训练方法和特定领域性能，这可能会对专业科学人工智能系统的发展产生影响。

> Materials discovery and development are critical for addressing global challenges. Yet, the exponential growth in materials science literature comprising vast amounts of textual data has created significant bottlenecks in knowledge extraction, synthesis, and scientific reasoning. Large Language Models (LLMs) offer unprecedented opportunities to accelerate materials research through automated analysis and prediction. Still, their effective deployment requires domain-specific adaptation for understanding and solving domain-relevant tasks. Here, we present LLaMat, a family of foundational models for materials science developed through continued pretraining of LLaMA models on an extensive corpus of materials literature and crystallographic data. Through systematic evaluation, we demonstrate that LLaMat excels in materials-specific NLP and structured information extraction while maintaining general linguistic capabilities. The specialized LLaMat-CIF variant demonstrates unprecedented capabilities in crystal structure generation, predicting stable crystals with high coverage across the periodic table. Intriguingly, despite LLaMA-3's superior performance in comparison to LLaMA-2, we observe that LLaMat-2 demonstrates unexpectedly enhanced domain-specific performance across diverse materials science tasks, including structured information extraction from text and tables, more particularly in crystal structure generation, a potential adaptation rigidity in overtrained LLMs. Altogether, the present work demonstrates the effectiveness of domain adaptation towards developing practically deployable LLM copilots for materials research. Beyond materials science, our findings reveal important considerations for domain adaptation of LLMs, such as model selection, training methodology, and domain-specific performance, which may influence the development of specialized scientific AI systems.

[Arxiv](https://arxiv.org/abs/2412.09560)