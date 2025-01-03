# LLMs 能够通过智能体协同进化模拟标准化患者

发布时间：2024年12月16日

`Agent

理由：这篇论文提出了一个名为EvoPatient的模拟病人框架，其中病人和医生代理通过多轮对话模拟诊断过程。这种框架涉及到代理（Agent）的设计和实现，特别是通过多轮对话来模拟真实世界的交互。虽然论文中提到了大型语言模型（LLM），但主要关注的是代理的行为和学习过程，而不是LLM的理论或应用。因此，这篇论文更适合归类为Agent。` `教育培训`

> LLMs Can Simulate Standardized Patients via Agent Coevolution

# 摘要

> # 摘要
使用标准化病人（SPs）培训医务人员仍面临复杂挑战，需深厚的领域知识和角色实践。现有基于大型语言模型（LLM）的模拟病人研究多聚焦于提升数据检索精度或通过人类反馈优化提示，却忽视了病人代理学习标准化呈现模式的关键需求——通过无监督模拟将数据转化为类人反应。为此，我们提出EvoPatient，一种创新模拟病人框架，病人与医生代理通过多轮对话模拟诊断过程，积累经验提升问答质量，助力人类医生培训。大量案例实验显示，仅需提供总体SP要求，EvoPatient在要求对齐和人类偏好上较现有方法提升超10%，且在10小时内进化200余案例后，实现资源消耗与泛化能力的最佳平衡。代码开源地址：https://github.com/ZJUMAI/EvoPatient。

> Training medical personnel using standardized patients (SPs) remains a complex challenge, requiring extensive domain expertise and role-specific practice. Most research on Large Language Model (LLM)-based simulated patients focuses on improving data retrieval accuracy or adjusting prompts through human feedback. However, this focus has overlooked the critical need for patient agents to learn a standardized presentation pattern that transforms data into human-like patient responses through unsupervised simulations. To address this gap, we propose EvoPatient, a novel simulated patient framework in which a patient agent and doctor agents simulate the diagnostic process through multi-turn dialogues, simultaneously gathering experience to improve the quality of both questions and answers, ultimately enabling human doctor training. Extensive experiments on various cases demonstrate that, by providing only overall SP requirements, our framework improves over existing reasoning methods by more than 10% in requirement alignment and better human preference, while achieving an optimal balance of resource consumption after evolving over 200 cases for 10 hours, with excellent generalizability. The code will be available at https://github.com/ZJUMAI/EvoPatient.

[Arxiv](https://arxiv.org/abs/2412.11716)