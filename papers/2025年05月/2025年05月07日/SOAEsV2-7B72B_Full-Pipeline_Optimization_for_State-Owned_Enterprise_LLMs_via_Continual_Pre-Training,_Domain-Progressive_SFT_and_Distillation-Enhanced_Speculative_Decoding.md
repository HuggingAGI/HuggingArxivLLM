# SOAEsV2-7B/72B：国有企业大型语言模型的全流程优化方案，采用持续预训练、领域渐进式SFT与蒸馏增强推测解码技术

发布时间：2025年05月07日

`LLM应用

摘要中讨论了开发专用大型语言模型（LLMs）的方法，针对特定领域（SOAEs）进行优化，属于应用层面的改进。` `国有资产`

> SOAEsV2-7B/72B: Full-Pipeline Optimization for State-Owned Enterprise LLMs via Continual Pre-Training, Domain-Progressive SFT and Distillation-Enhanced Speculative Decoding

# 摘要

> 本研究聚焦于为中国国有资产和企业（SOAEs）开发专用大型语言模型（LLMs）的关键挑战。当前方法存在三大局限：模型容量受限影响知识整合与跨任务适应性；过度依赖领域特定数据忽视通用语言模式；处理长上下文时推理效率低下。为此，我们提出SOAEsV2-7B/72B，通过三阶段框架打造专用LLM系列：1) 持续预训练整合领域知识，同时保留基础能力；2) 领域渐进式微调采用课程学习策略，从弱相关对话数据过渡到专家标注数据，优化领域任务；3) 增强型推测解码通过模型蒸馏加速推理，速度提升1.39-1.52倍，且不损失质量。实验显示，领域预训练保持99.8%通用语言能力，同时将Rouge-1和BLEU-4分数分别提升1.08和1.17倍。消融实验表明，渐进式微调优于单阶段训练，Rouge-1和BLEU-4分数分别提升1.02和1.06倍。本研究提供了一种全面的端到端方法，优化SOAEs LLMs，成功弥合通用语言能力和领域专业知识的鸿沟。

> This study addresses key challenges in developing domain-specific large language models (LLMs) for Chinese state-owned assets and enterprises (SOAEs), where current approaches face three limitations: 1) constrained model capacity that limits knowledge integration and cross-task adaptability; 2) excessive reliance on domain-specific supervised fine-tuning (SFT) data, which neglects the broader applicability of general language patterns; and 3) inefficient inference acceleration for large models processing long contexts. In this work, we propose SOAEsV2-7B/72B, a specialized LLM series developed via a three-phase framework: 1) continual pre-training integrates domain knowledge while retaining base capabilities; 2) domain-progressive SFT employs curriculum-based learning strategy, transitioning from weakly relevant conversational data to expert-annotated SOAEs datasets to optimize domain-specific tasks; 3) distillation-enhanced speculative decoding accelerates inference via logit distillation between 72B target and 7B draft models, achieving 1.39-1.52$\times$ speedup without quality loss. Experimental results demonstrate that our domain-specific pre-training phase maintains 99.8% of original general language capabilities while significantly improving domain performance, resulting in a 1.08$\times$ improvement in Rouge-1 score and a 1.17$\times$ enhancement in BLEU-4 score. Ablation studies further show that domain-progressive SFT outperforms single-stage training, achieving 1.02$\times$ improvement in Rouge-1 and 1.06$\times$ in BLEU-4. Our work introduces a comprehensive, full-pipeline approach for optimizing SOAEs LLMs, bridging the gap between general language capabilities and domain-specific expertise.

[Arxiv](https://arxiv.org/abs/2505.04723)