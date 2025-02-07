# ChartCitor: 细粒度图表视觉归因的多智能体框架

发布时间：2025年02月02日

`Agent

理由：这篇论文介绍了一个名为ChartCitor的多代理框架，该框架通过协调多个LLM代理来执行图表问答任务。这些代理分别负责不同的子任务，如图表到表格提取、答案重构、证据检索等。因此，这篇论文主要关注的是多代理系统的设计和应用，属于Agent分类。` `数据可视化` `问答系统`

> ChartCitor: Multi-Agent Framework for Fine-Grained Chart Visual Attribution

# 摘要

> 大型语言模型（LLMs）虽能执行图表问答任务，但常生成未经核实的幻觉回答。现有答案归因方法因视觉语义上下文有限、视觉文本对齐复杂及复杂布局中边界框预测困难，难以将回答与源图表关联。我们推出ChartCitor，一个多代理框架，通过识别图表图像中的支持证据，提供细粒度边界框引用。该系统协调LLM代理执行图表到表格提取、答案重构、表格增强、预过滤和重排序的证据检索及表格到图表映射。ChartCitor在各类图表上表现优于现有基线。定性用户研究显示，ChartCitor通过增强LLM辅助图表问答的可解释性，提升用户对生成式AI的信任，并提高专业人员效率。

> Large Language Models (LLMs) can perform chart question-answering tasks but often generate unverified hallucinated responses. Existing answer attribution methods struggle to ground responses in source charts due to limited visual-semantic context, complex visual-text alignment requirements, and difficulties in bounding box prediction across complex layouts. We present ChartCitor, a multi-agent framework that provides fine-grained bounding box citations by identifying supporting evidence within chart images. The system orchestrates LLM agents to perform chart-to-table extraction, answer reformulation, table augmentation, evidence retrieval through pre-filtering and re-ranking, and table-to-chart mapping. ChartCitor outperforms existing baselines across different chart types. Qualitative user studies show that ChartCitor helps increase user trust in Generative AI by providing enhanced explainability for LLM-assisted chart QA and enables professionals to be more productive.

[Arxiv](https://arxiv.org/abs/2502.00989)