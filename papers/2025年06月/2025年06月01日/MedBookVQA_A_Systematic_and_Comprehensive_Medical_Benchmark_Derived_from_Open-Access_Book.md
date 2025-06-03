# # 摘要
MedBookVQA：源自开放获取书籍的系统性医学问答基准。

发布时间：2025年06月01日

`LLM应用` `医学教育`

> MedBookVQA: A Systematic and Comprehensive Medical Benchmark Derived from Open-Access Book

# 摘要

> 多模态大型语言模型（MLLMs）驱动的通用医疗人工智能（GMAI）正快速发展，为解决医疗领域长期存在的难题（如人力短缺和成本攀升）带来变革性机遇。与此同时，系统化评估基准的开发成为关键，以支持性能评估和技术指导。然而，医学教科书作为宝贵的知识来源，其在基准开发中的潜力尚未得到充分利用。为此，我们推出了MedBookVQA——一个基于开源医学教科书构建的系统化、全面的多模态基准。通过标准化的数据管道，我们从教科书中自动提取医学图表，并将其与相关医学叙述进行语境对齐。基于此，我们生成了5,000个临床相关问题，涵盖模态识别、疾病分类、解剖部位识别、症状诊断和手术流程等主题。借助多层级标注系统，我们根据医学影像模态（42类）、身体解剖部位（125种结构）和临床专科（31个科室）的分类对问题进行分级，从而实现对医学子领域的细致分析。我们评估了多种MLLMs，包括专有模型、开源模型、医学模型和推理模型，揭示了不同任务类型和模型类别之间的显著性能差异。研究发现凸显了当前GMAI系统的能力缺口，同时确立了基于教科书的多模态基准作为重要评估工具。MedBookVQA不仅揭示了GMAI系统的局限性，还提供了跨专科的结构化性能指标，确立了基于教科书的基准测试作为推动临床AI发展的重要范式。

> The accelerating development of general medical artificial intelligence (GMAI), powered by multimodal large language models (MLLMs), offers transformative potential for addressing persistent healthcare challenges, including workforce deficits and escalating costs. The parallel development of systematic evaluation benchmarks emerges as a critical imperative to enable performance assessment and provide technological guidance. Meanwhile, as an invaluable knowledge source, the potential of medical textbooks for benchmark development remains underexploited. Here, we present MedBookVQA, a systematic and comprehensive multimodal benchmark derived from open-access medical textbooks. To curate this benchmark, we propose a standardized pipeline for automated extraction of medical figures while contextually aligning them with corresponding medical narratives. Based on this curated data, we generate 5,000 clinically relevant questions spanning modality recognition, disease classification, anatomical identification, symptom diagnosis, and surgical procedures. A multi-tier annotation system categorizes queries through hierarchical taxonomies encompassing medical imaging modalities (42 categories), body anatomies (125 structures), and clinical specialties (31 departments), enabling nuanced analysis across medical subdomains. We evaluate a wide array of MLLMs, including proprietary, open-sourced, medical, and reasoning models, revealing significant performance disparities across task types and model categories. Our findings highlight critical capability gaps in current GMAI systems while establishing textbook-derived multimodal benchmarks as essential evaluation tools. MedBookVQA establishes textbook-derived benchmarking as a critical paradigm for advancing clinical AI, exposing limitations in GMAI systems while providing anatomically structured performance metrics across specialties.

[Arxiv](https://arxiv.org/abs/2506.00855)