# HASHIRU: 分层智能体系统实现混合智能资源利用

发布时间：2025年06月01日

`Agent` `人工智能` `多智能体系统`

> HASHIRU: Hierarchical Agent System for Hybrid Intelligent Resource Utilization

# 摘要

> 大型语言模型（LLM）的快速发展正在推动多智能体系统（MAS）向更自主的方向发展。然而，现有框架在灵活性、资源感知能力、模型多样性和自主工具创建方面存在明显不足。本文提出了一种名为HASHIRU（层级智能资源利用系统）的新型MAS框架，旨在全面提升系统的灵活性、资源效率和适应性。HASHIRU配备了一个动态管理各类'员工'智能体的'CEO'智能体，这些'员工'智能体根据具体任务需求和资源限制（如成本、内存）进行实例化。其混合智能系统优先采用本地小型LLM（通过Ollama实现），同时在必要时灵活调用外部API和大型模型。通过引入包含招聘/解雇成本的经济模型，HASHIRU有效提升了团队稳定性和资源分配效率。系统还集成了自主API工具创建和记忆功能。在学术论文评审（成功率58%）、安全评估（JailbreakBench子集100%通过）以及复杂推理任务（GSM8K上超越Gemini 2.0 Flash：96% vs. 61%；JEEBench：80% vs. 68.3%；SVAMP：92% vs. 84%）上的评估结果，充分展示了HASHIRU的强大能力。案例研究则进一步展示了其通过自主成本模型生成、工具集成和预算管理实现自我优化的潜力。HASHIRU通过动态层级控制、资源感知的混合智能以及自主功能扩展，为构建更强大、高效和适应性的MAS提供了一种极具前景的方法。HASHIRU的源代码和基准测试分别托管在https://github.com/HASHIRU-AI/HASHIRU和https://github.com/HASHIRU-AI/HASHIRUBench，用户可申请访问实时演示版本https://hashiruagentx-hashiruai.hf.space。


> Rapid Large Language Model (LLM) advancements are fueling autonomous Multi-Agent System (MAS) development. However, current frameworks often lack flexibility, resource awareness, model diversity, and autonomous tool creation. This paper introduces HASHIRU (Hierarchical Agent System for Hybrid Intelligent Resource Utilization), a novel MAS framework enhancing flexibility, resource efficiency, and adaptability. HASHIRU features a "CEO" agent dynamically managing specialized "employee" agents, instantiated based on task needs and resource constraints (cost, memory). Its hybrid intelligence prioritizes smaller, local LLMs (via Ollama) while flexibly using external APIs and larger models when necessary. An economic model with hiring/firing costs promotes team stability and efficient resource allocation. The system also includes autonomous API tool creation and a memory function. Evaluations on tasks like academic paper review (58% success), safety assessments (100% on a JailbreakBench subset), and complex reasoning (outperforming Gemini 2.0 Flash on GSM8K: 96% vs. 61%; JEEBench: 80% vs. 68.3%; SVAMP: 92% vs. 84%) demonstrate HASHIRU's capabilities. Case studies illustrate its self-improvement via autonomous cost model generation, tool integration, and budget management. HASHIRU offers a promising approach for more robust, efficient, and adaptable MAS through dynamic hierarchical control, resource-aware hybrid intelligence, and autonomous functional extension. Source code and benchmarks are available at https://github.com/HASHIRU-AI/HASHIRU and https://github.com/HASHIRU-AI/HASHIRUBench respectively, and a live demo is available at https://hashiruagentx-hashiruai.hf.space upon request.

[Arxiv](https://arxiv.org/abs/2506.04255)