# 基于LLM的多智能体框架：智能辅导系统中的目标导向学习

发布时间：2025年01月26日

`Agent

理由：这篇论文提出了一个基于LLM的多代理框架GenMentor，旨在实现目标导向的个性化学习。该框架通过多个代理（如LLM、动态优化方法等）协同工作，精准映射学习者目标与所需技能，并规划高效学习路径。因此，这篇论文主要涉及多代理系统的设计和应用，属于Agent分类。` `个性化学习`

> LLM-powered Multi-agent Framework for Goal-oriented Learning in Intelligent Tutoring System

# 摘要

> 智能辅导系统（ITSs）通过个性化学习体验革新了教育。然而，随着目标导向学习在专业领域的重要性日益凸显，现有ITSs往往难以提供这种精准的学习体验。本文提出GenMentor，一个基于LLM的多代理框架，旨在ITS中实现目标导向的个性化学习。GenMentor首先利用在定制目标-技能数据集上微调的LLM，精准映射学习者目标与所需技能。识别技能差距后，它采用动态优化方法，基于学习者多维状态的全面档案，规划高效学习路径。此外，GenMentor通过探索-起草-整合机制，定制学习内容以满足个体需求。大量自动化和人工评估验证了GenMentor在学习指导和内容质量上的卓越表现。我们已将其部署并实现为应用程序，与专业学习者的实际研究进一步证实了其在目标对齐和资源精准投放上的优势，显著提升了个性化学习效果。更多资源请访问https://github.com/GeminiLight/gen-mentor。

> Intelligent Tutoring Systems (ITSs) have revolutionized education by offering personalized learning experiences. However, as goal-oriented learning, which emphasizes efficiently achieving specific objectives, becomes increasingly important in professional contexts, existing ITSs often struggle to deliver this type of targeted learning experience. In this paper, we propose GenMentor, an LLM-powered multi-agent framework designed to deliver goal-oriented, personalized learning within ITS. GenMentor begins by accurately mapping learners' goals to required skills using a fine-tuned LLM trained on a custom goal-to-skill dataset. After identifying the skill gap, it schedules an efficient learning path using an evolving optimization approach, driven by a comprehensive and dynamic profile of learners' multifaceted status. Additionally, GenMentor tailors learning content with an exploration-drafting-integration mechanism to align with individual learner needs. Extensive automated and human evaluations demonstrate GenMentor's effectiveness in learning guidance and content quality. Furthermore, we have deployed it in practice and also implemented it as an application. Practical human study with professional learners further highlights its effectiveness in goal alignment and resource targeting, leading to enhanced personalization. Supplementary resources are available at https://github.com/GeminiLight/gen-mentor.

[Arxiv](https://arxiv.org/abs/2501.15749)