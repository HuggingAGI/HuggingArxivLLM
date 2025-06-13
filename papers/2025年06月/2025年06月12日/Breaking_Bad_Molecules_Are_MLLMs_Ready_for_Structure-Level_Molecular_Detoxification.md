# # 标题
有害分子分解：分子大语言模型是否已准备好进行结构级分子解毒？

发布时间：2025年06月12日

`LLM应用

理由：这篇论文探讨了大型语言模型在分子毒性修复任务中的应用，提出了一个多模态基准任务和评估框架，属于LLM的实际应用研究。` `药物开发` `人工智能`

> Breaking Bad Molecules: Are MLLMs Ready for Structure-Level Molecular Detoxification?

# 摘要

> 毒性仍是早期药物开发失败的主要原因。尽管分子设计和性质预测技术不断进步，但分子毒性修复任务——即生成结构有效且毒性更低的分子替代品——尚未得到系统定义或基准化。为填补这一空白，我们推出了首个专注于分子毒性修复的通用多模态大型语言模型（MLLMs）基准任务ToxiMol。我们的标准化数据集涵盖11个主要任务和560种具有代表性的有毒分子，涉及多样化的机制和粒度。我们设计了一个基于专家毒理学知识的机制感知和任务自适应提示注释管道。同时，我们提出了自动化评估框架ToxiEval，它将毒性终点预测、合成可行性、药物相似性和结构相似性整合到一个高通量的评估链中，用于修复成功的评估。我们系统评估了近30种主流的通用MLLMs，并设计了多个消融实验来分析关键因素，包括评估标准、候选多样性及失败归因。实验结果表明，尽管当前MLLMs在这一任务上仍面临重大挑战，但它们开始展现出在毒性理解、语义约束遵守以及结构感知分子编辑方面的潜力。

> Toxicity remains a leading cause of early-stage drug development failure. Despite advances in molecular design and property prediction, the task of molecular toxicity repair - generating structurally valid molecular alternatives with reduced toxicity - has not yet been systematically defined or benchmarked. To fill this gap, we introduce ToxiMol, the first benchmark task for general-purpose Multimodal Large Language Models (MLLMs) focused on molecular toxicity repair. We construct a standardized dataset covering 11 primary tasks and 560 representative toxic molecules spanning diverse mechanisms and granularities. We design a prompt annotation pipeline with mechanism-aware and task-adaptive capabilities, informed by expert toxicological knowledge. In parallel, we propose an automated evaluation framework, ToxiEval, which integrates toxicity endpoint prediction, synthetic accessibility, drug-likeness, and structural similarity into a high-throughput evaluation chain for repair success. We systematically assess nearly 30 mainstream general-purpose MLLMs and design multiple ablation studies to analyze key factors such as evaluation criteria, candidate diversity, and failure attribution. Experimental results show that although current MLLMs still face significant challenges on this task, they begin to demonstrate promising capabilities in toxicity understanding, semantic constraint adherence, and structure-aware molecule editing.

[Arxiv](https://arxiv.org/abs/2506.10912)