# LLM智能体群在假设驱动药物发现中的应用

发布时间：2025年04月24日

`Agent` `药物研发`

> LLM Agent Swarm for Hypothesis-Driven Drug Discovery

# 摘要

> 药物研发面临巨大挑战：90%以上的候选分子临床失败，研发成本常超10亿美元。基因组学、转录组学、化学库和临床数据相互割裂，阻碍了机制理解与研发进程。大型语言模型虽擅长推理与工具整合，但缺乏模块化专业性和迭代记忆，难以支持受监管的假设驱动工作流程。我们推出PharmaSwarm，一个统一的多智能体框架，协调专业LLM“智能体”提出、验证和优化新型药物靶点与先导化合物的假设。每个智能体拥有专属功能：自动化基因组分析、生物医学知识图谱、通路模拟与可解释结合亲和力预测。中央评估器LLM持续根据生物合理性、新颖性、体内外有效性和安全性对提案排名。共享记忆层捕获验证见解，随时间微调子模型，形成自我改进系统。PharmaSwarm支持低代码平台或Kubernetes微服务部署，助力文献驱动发现、组学靶点识别与药物重定位。我们建立了四层级验证流程，包括回顾性测试、独立实验、实验证测和专家研究，确保透明、可重复与实际影响。作为AI协作者，PharmaSwarm加速转化研究，比传统流程更高效地交付高信心假设。

> Drug discovery remains a formidable challenge: more than 90 percent of candidate molecules fail in clinical evaluation, and development costs often exceed one billion dollars per approved therapy. Disparate data streams, from genomics and transcriptomics to chemical libraries and clinical records, hinder coherent mechanistic insight and slow progress. Meanwhile, large language models excel at reasoning and tool integration but lack the modular specialization and iterative memory required for regulated, hypothesis-driven workflows. We introduce PharmaSwarm, a unified multi-agent framework that orchestrates specialized LLM "agents" to propose, validate, and refine hypotheses for novel drug targets and lead compounds. Each agent accesses dedicated functionality--automated genomic and expression analysis; a curated biomedical knowledge graph; pathway enrichment and network simulation; interpretable binding affinity prediction--while a central Evaluator LLM continuously ranks proposals by biological plausibility, novelty, in silico efficacy, and safety. A shared memory layer captures validated insights and fine-tunes underlying submodels over time, yielding a self-improving system. Deployable on low-code platforms or Kubernetes-based microservices, PharmaSwarm supports literature-driven discovery, omics-guided target identification, and market-informed repurposing. We also describe a rigorous four-tier validation pipeline spanning retrospective benchmarking, independent computational assays, experimental testing, and expert user studies to ensure transparency, reproducibility, and real-world impact. By acting as an AI copilot, PharmaSwarm can accelerate translational research and deliver high-confidence hypotheses more efficiently than traditional pipelines.

[Arxiv](https://arxiv.org/abs/2504.17967)