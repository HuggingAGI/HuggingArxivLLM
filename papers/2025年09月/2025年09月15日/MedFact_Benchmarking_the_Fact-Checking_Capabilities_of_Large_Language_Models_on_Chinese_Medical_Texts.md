# MedFact：大型语言模型在中文医学文本上的事实核查能力基准测试

发布时间：2025年09月15日

`LLM应用` `医疗健康`

> MedFact: Benchmarking the Fact-Checking Capabilities of Large Language Models on Chinese Medical Texts

# 摘要

> 随着大型语言模型（LLMs）在医疗领域的应用日益广泛，对其事实可靠性的严格评估变得至关重要。然而，现有基准常受限于数据领域狭窄，难以涵盖现实医疗信息的复杂性。为此，我们推出MedFact——一个全新的中文医疗事实核查挑战基准。该基准包含2116个专家标注实例，精选自多样化的真实文本，覆盖13个医学专科、8种细粒度错误类型、4种写作风格及多个难度等级。其构建采用AI-人类混合框架：通过专家迭代反馈，不断优化AI驱动的多标准过滤流程，确保数据质量与难度双高。我们对20个主流LLMs展开全面评估，在真实性分类和错误定位任务上与人类专家基线对比。结果显示：尽管模型通常能判断文本是否存在错误，但精确定位错误仍是巨大挑战，即便是顶尖模型也远不及人类水平。更值得注意的是，我们发现了普遍的“过度批评”现象——模型易将正确信息误判为错误，而多智能体协作、推理时扩展等高级推理技术会进一步加剧这一问题。MedFact通过揭示LLMs在医疗应用中的核心挑战，为开发更可靠、更懂医疗的模型提供了坚实资源。

> The increasing deployment of Large Language Models (LLMs) in healthcare necessitates a rigorous evaluation of their factual reliability. However, existing benchmarks are often limited by narrow domains of data, failing to capture the complexity of real-world medical information. To address this critical gap, we introduce MedFact, a new and challenging benchmark for Chinese medical fact-checking. MedFact comprises 2,116 expert-annotated instances curated from diverse real-world texts, spanning 13 medical specialties, 8 fine-grained error types, 4 writing styles, and multiple difficulty levels. Its construction employs a hybrid AI-human framework where iterative expert feedback refines an AI-driven, multi-criteria filtering process, ensuring both high data quality and difficulty. We conduct a comprehensive evaluation of 20 leading LLMs, benchmarking their performance on veracity classification and error localization against a human expert baseline. Our results reveal that while models can often determine if a text contains an error, precisely localizing it remains a substantial challenge, with even top-performing models falling short of human performance. Furthermore, our analysis uncovers a frequent ``over-criticism'' phenomenon, a tendency for models to misidentify correct information as erroneous, which is exacerbated by advanced reasoning techniques such as multi-agent collaboration and inference-time scaling. By highlighting these critical challenges for deploying LLMs in medical applications, MedFact provides a robust resource to drive the development of more factually reliable and medically aware models.

[Arxiv](https://arxiv.org/abs/2509.12440)