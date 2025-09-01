# CataractSurg-80K：面向眼科手术规划中结构化推理的知识驱动基准

发布时间：2025年08月27日

`Agent` `医疗健康`

> CataractSurg-80K: Knowledge-Driven Benchmarking for Structured Reasoning in Ophthalmic Surgery Planning

# 摘要

> 白内障手术至今仍是应用最广、效果最佳的视力恢复手术之一。要制定有效的手术方案，需整合各类临床检查数据，完成患者评估、人工晶状体（IOL）选型及风险评估。大型语言模型（LLMs）在辅助临床决策上已崭露头角，但现有模型常因缺乏领域专长，难以解读复杂异构的眼科数据，更无法生成切实可行的手术方案。

为此，我们提出知识驱动的多智能体系统（MAS）：每个智能体模拟专科眼科医生的推理逻辑，在训练与部署阶段将原始临床数据转化为结构化、可落地的诊疗总结，大幅提升模型对异构眼科报告的解读能力。基于MAS，我们构建了首个融合结构化临床推理的大规模白内障手术规划基准——CataractSurg-80K，数据集的每个病例均包含诊断问题、专家推理链及结构化手术建议标注。

我们还开发了领域专用模型Qwen-CSP：基于Qwen-4B，通过专为手术规划设计的多阶段微调而成。实验结果显示，Qwen-CSP在多项指标上均超越了性能强劲的通用LLMs。本研究贡献了高质量数据集、标准化基准及领域适配LLM，为医疗AI推理与决策支持领域的未来研究奠定了基础。

> Cataract surgery remains one of the most widely performed and effective procedures for vision restoration. Effective surgical planning requires integrating diverse clinical examinations for patient assessment, intraocular lens (IOL) selection, and risk evaluation. Large language models (LLMs) have shown promise in supporting clinical decision-making. However, existing LLMs often lack the domain-specific expertise to interpret heterogeneous ophthalmic data and provide actionable surgical plans. To enhance the model's ability to interpret heterogeneous ophthalmic reports, we propose a knowledge-driven Multi-Agent System (MAS), where each agent simulates the reasoning process of specialist ophthalmologists, converting raw clinical inputs into structured, actionable summaries in both training and deployment stages. Building on MAS, we introduce CataractSurg-80K, the first large-scale benchmark for cataract surgery planning that incorporates structured clinical reasoning. Each case is annotated with diagnostic questions, expert reasoning chains, and structured surgical recommendations. We further introduce Qwen-CSP, a domain-specialized model built on Qwen-4B, fine-tuned through a multi-stage process tailored for surgical planning. Comprehensive experiments show that Qwen-CSP outperforms strong general-purpose LLMs across multiple metrics. Our work delivers a high-quality dataset, a rigorous benchmark, and a domain-adapted LLM to facilitate future research in medical AI reasoning and decision support.

[Arxiv](https://arxiv.org/abs/2508.20014)