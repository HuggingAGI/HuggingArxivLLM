# PT-MoE：高效整合专家混合到提示微调的微调框架

发布时间：2025年05月14日

`LLM理论`

> PT-MoE: An Efficient Finetuning Framework for Integrating Mixture-of-Experts into Prompt Tuning

# 摘要

> 参数高效微调（PEFT）方法在适应大型语言模型方面展现出巨大潜力，但现有方法也呈现出一些反直觉的现象：将路由机制引入提示调优（PT）能提升训练效率，却未能在所有场景下改善性能；通过矩阵分解减少参数数量，却能在特定领域提升性能。受这些观察结果和PT模块化特性的启发，我们提出了PT-MoE，这是一个将矩阵分解与专家混合（MoE）路由相结合的高效PT新框架。在17个数据集上的实验结果表明，PT-MoE在问答（QA）和数学问题解决任务中均达到当前最优性能，与PT相比，QA任务中的F1分数提升了1.49分，与LoRA相比提升了2.13分；同时，在数学任务中，准确率较PT提升了10.75分，较LoRA提升了0.44分。值得注意的是，PT-MoE的参数量仅为LoRA的四分之一。我们的分析表明，尽管PT方法在QA任务中通常表现优异，而基于LoRA的方法在数学数据集上表现更好，但PT-MoE中矩阵分解与MoE的结合却能产生互补优势：分解机制实现了专家间的高效参数共享，而MoE则提供了动态适应能力。这些特性共同赋予了PT-MoE跨任务一致性与泛化能力。这些发现，结合对路由机制和架构组件的消融研究，为未来PEFT方法的发展提供了重要启示。

> Parameter-efficient fine-tuning (PEFT) methods have shown promise in adapting large language models, yet existing approaches exhibit counter-intuitive phenomena: integrating router into prompt tuning (PT) increases training efficiency yet does not improve performance universally; parameter reduction through matrix decomposition can improve performance in specific domains. Motivated by these observations and the modular nature of PT, we propose PT-MoE, a novel framework that integrates matrix decomposition with mixture-of-experts (MoE) routing for efficient PT. Results across 17 datasets demonstrate that PT-MoE achieves state-of-the-art performance in both question answering (QA) and mathematical problem solving tasks, improving F1 score by 1.49 points over PT and 2.13 points over LoRA in QA tasks, while enhancing mathematical accuracy by 10.75 points over PT and 0.44 points over LoRA, all while using 25% fewer parameters than LoRA. Our analysis reveals that while PT methods generally excel in QA tasks and LoRA-based methods in math datasets, the integration of matrix decomposition and MoE in PT-MoE yields complementary benefits: decomposition enables efficient parameter sharing across experts while MoE provides dynamic adaptation, collectively enabling PT-MoE to demonstrate cross-task consistency and generalization abilities. These findings, along with ablation studies on routing mechanisms and architectural components, provide insights for future PEFT methods.

[Arxiv](https://arxiv.org/abs/2505.09519)