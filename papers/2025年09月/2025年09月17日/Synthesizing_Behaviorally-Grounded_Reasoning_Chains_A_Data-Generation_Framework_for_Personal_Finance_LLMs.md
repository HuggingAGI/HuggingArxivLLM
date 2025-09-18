# 构建基于行为的推理链：针对个人金融LLMs的数据生成框架

发布时间：2025年09月17日

`LLM应用` `金融科技`

> Synthesizing Behaviorally-Grounded Reasoning Chains: A Data-Generation Framework for Personal Finance LLMs

# 摘要

> 个性化财务建议需综合考量用户目标、约束条件、风险承受能力及管辖权。此前的LLM研究多聚焦于投资者与财务规划师的支持系统，而近期多项研究虽通过智能体管道探索预算制定、债务管理、退休及遗产规划等更广泛的个人财务任务，却因管道维护成本高昂，实际回报不足预期的25%。本研究提出一种新颖可复现的框架，整合相关财务背景与行为金融学研究，构建端到端顾问的监督数据。基于该框架，我们生成19k样本推理数据集，并对Qwen-3-8B模型完成全面微调。通过保留测试集与盲LLM评审实验发现：经精心数据整理与行为整合后，8B模型在事实准确性、流畅性及个性化指标上可媲美14-32B参数的大模型，成本却降低80%。

> Personalized financial advice requires consideration of user goals, constraints, risk tolerance, and jurisdiction. Prior LLM work has focused on support systems for investors and financial planners. Simultaneously, numerous recent studies examine broader personal finance tasks, including budgeting, debt management, retirement, and estate planning, through agentic pipelines that incur high maintenance costs, yielding less than 25% of their expected financial returns. In this study, we introduce a novel and reproducible framework that integrates relevant financial context with behavioral finance studies to construct supervision data for end-to-end advisors. Using this framework, we create a 19k sample reasoning dataset and conduct a comprehensive fine-tuning of the Qwen-3-8B model on the dataset. Through a held-out test split and a blind LLM-jury study, we demonstrate that through careful data curation and behavioral integration, our 8B model achieves performance comparable to significantly larger baselines (14-32B parameters) across factual accuracy, fluency, and personalization metrics while incurring 80% lower costs than the larger counterparts.

[Arxiv](https://arxiv.org/abs/2509.14180)