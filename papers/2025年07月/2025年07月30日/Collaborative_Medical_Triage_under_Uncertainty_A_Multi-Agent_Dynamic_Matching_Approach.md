# 不确定性环境下协作医疗分诊的多智能体动态匹配方法研究

发布时间：2025年07月30日

`LLM应用` `智能分诊系统`

> Collaborative Medical Triage under Uncertainty: A Multi-Agent Dynamic Matching Approach

# 摘要

> 疫情后医疗需求激增叠加护理短缺，给急诊科分诊系统带来了前所未有的压力，亟需创新的AI解决方案。我们提出了一种多智能体交互式智能分诊系统，针对性解决当前AI分诊系统三大核心难题：医学专业性不足导致的误分类、医疗机构科室结构差异，以及低效问诊阻碍快速决策。我们的系统通过三个专门化智能体——接收者、询问者和科室智能体，借助结构化问诊机制和科室特定规则，将患者症状转化为精准科室推荐。为确保评估 robust，我们构建了一个包含3360个真实案例的中文医疗分诊数据集，涵盖9个主要科室和62个二级科室。通过大型语言模型进行系统性数据填补，有效解决了真实数据中病历不完整的问题。实验显示，四轮问诊后，系统在主要科室分类上达到89.2%的准确率，在二级科室分类上达到73.9%。基于模式匹配的引导机制使其能高效适应不同医院配置，同时保持高分诊准确率。我们的工作提供了一个可扩展框架，用于部署能够适应医疗机构异质性并确保临床决策合理的AI辅助分诊系统。

> The post-pandemic surge in healthcare demand, coupled with critical nursing shortages, has placed unprecedented pressure on emergency department triage systems, necessitating innovative AI-driven solutions. We present a multi-agent interactive intelligent system for medical triage that addresses three fundamental challenges in current AI-based triage systems: insufficient medical specialization leading to hallucination-induced misclassifications, heterogeneous department structures across healthcare institutions, and inefficient detail-oriented questioning that impedes rapid triage decisions. Our system employs three specialized agents - RecipientAgent, InquirerAgent, and DepartmentAgent - that collaborate through structured inquiry mechanisms and department-specific guidance rules to transform unstructured patient symptoms into accurate department recommendations. To ensure robust evaluation, we constructed a comprehensive Chinese medical triage dataset from a medical website, comprising 3,360 real-world cases spanning 9 primary departments and 62 secondary departments. Through systematic data imputation using large language models, we address the prevalent issue of incomplete medical records in real-world data. Experimental results demonstrate that our multi-agent system achieves 89.2% accuracy in primary department classification and 73.9% accuracy in secondary department classification after four rounds of patient interaction. The system's pattern-matching-based guidance mechanisms enable efficient adaptation to diverse hospital configurations while maintaining high triage accuracy. Our work provides a scalable framework for deploying AI-assisted triage systems that can accommodate the organizational heterogeneity of healthcare institutions while ensuring clinically sound decision-making.

[Arxiv](https://arxiv.org/abs/2507.22504)