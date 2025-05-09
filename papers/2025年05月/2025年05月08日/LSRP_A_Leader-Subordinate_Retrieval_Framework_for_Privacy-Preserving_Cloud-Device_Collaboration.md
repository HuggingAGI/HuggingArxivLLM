# LSRP：面向隐私保护的云-端协作主从检索框架

发布时间：2025年05月08日

`RAG` `云计算`

> LSRP: A Leader-Subordinate Retrieval Framework for Privacy-Preserving Cloud-Device Collaboration

# 摘要

> 云设备协作巧妙结合云端大型语言模型（LLMs）处理公共查询与设备端小型语言模型（SLMs）处理私密数据，构建了一个强大且保护隐私的解决方案。然而，现有方法未能充分利用云端LLMs的可扩展问题解决能力，同时也未能充分发挥设备端SLMs在处理个性化数据方面的优势。这导致了两个相互关联的问题：1）云端LLMs的能力未得到充分运用，难以满足用户的个性化需求；2）设备端SLMs的响应未能充分整合用户数据，导致用户上下文信息的不匹配。
    本文提出了一种名为LSRP（领导-从属检索框架）的创新解决方案，通过以下方式弥合上述差距：1）通过动态选择任务特定的领导策略（U-U-RAG）来增强云端LLM对设备端SLM的指导；2）通过SMFB-DPO整合设备端SLMs的数据优势，实现云端LLM与设备端SLM的协同一致。实验结果表明，LSRP显著优于现有基线方法，大幅提升了问答的相关性和个性化，同时通过高效的设备端检索保护了用户隐私。我们的代码可在以下链接获取：https://github.com/Zhang-Yingyi/LSRP.

> Cloud-device collaboration leverages on-cloud Large Language Models (LLMs) for handling public user queries and on-device Small Language Models (SLMs) for processing private user data, collectively forming a powerful and privacy-preserving solution. However, existing approaches often fail to fully leverage the scalable problem-solving capabilities of on-cloud LLMs while underutilizing the advantage of on-device SLMs in accessing and processing personalized data. This leads to two interconnected issues: 1) Limited utilization of the problem-solving capabilities of on-cloud LLMs, which fail to align with personalized user-task needs, and 2) Inadequate integration of user data into on-device SLM responses, resulting in mismatches in contextual user information.
  In this paper, we propose a Leader-Subordinate Retrieval framework for Privacy-preserving cloud-device collaboration (LSRP), a novel solution that bridges these gaps by: 1) enhancing on-cloud LLM guidance to on-device SLM through a dynamic selection of task-specific leader strategies named as user-to-user retrieval-augmented generation (U-U-RAG), and 2) integrating the data advantages of on-device SLMs through small model feedback Direct Preference Optimization (SMFB-DPO) for aligning the on-cloud LLM with the on-device SLM. Experiments on two datasets demonstrate that LSRP consistently outperforms state-of-the-art baselines, significantly improving question-answer relevance and personalization, while preserving user privacy through efficient on-device retrieval. Our code is available at: https://github.com/Zhang-Yingyi/LSRP.

[Arxiv](https://arxiv.org/abs/2505.05031)