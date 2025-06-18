# ImpReSS：支持对话的隐式推荐系统

发布时间：2025年06月17日

`LLM应用

摘要讨论了大型语言模型（LLMs）在聊天机器人中的应用，特别是在客户服务中的隐式推荐系统ImpReSS。该系统利用LLMs来推荐解决方案，提升服务质量，属于LLM的实际应用案例。` `客户服务` `推荐系统`

> ImpReSS: Implicit Recommender System for Support Conversations

# 摘要

> 基于大型语言模型（LLMs）的最新进展，聊天机器人已通过自动化交互流程彻底改变了客户服务领域，提供了一致且可扩展的服务体验。尽管基于LLMs的对话推荐系统（CRSs）因其提升推荐质量的能力而备受关注，但目前尚无研究深入探讨如何将推荐隐式整合到客户服务交互中。在本研究中，我们推出了ImpReSS，一个专为客服对话设计的隐式推荐系统。ImpReSS与现有客服聊天机器人协同工作，用户在此过程中报告问题，而聊天机器人则提供解决方案。基于客服对话内容，ImpReSS能够识别推荐相关解决方案产品类别（SPCs）的机会，这些推荐不仅有助于解决问题，还能防止问题再次发生，从而支持业务增长。与传统CRS不同，ImpReSS完全以隐式方式运作，无需依赖用户购买意图的任何假设。我们的实证评估显示，ImpReSS在推荐相关SPCs以帮助解决支持对话中提出问题方面表现优异，包括在一般问题解决中MRR@1（和recall@3）为0.72（0.89），信息安全部门支持中为0.82（0.83），以及网络安全故障排除中为0.85（0.67）。为了支持未来研究，我们的数据和代码将在请求时共享。

> Following recent advancements in large language models (LLMs), LLM-based chatbots have transformed customer support by automating interactions and providing consistent, scalable service. While LLM-based conversational recommender systems (CRSs) have attracted attention for their ability to enhance the quality of recommendations, limited research has addressed the implicit integration of recommendations within customer support interactions. In this work, we introduce ImpReSS, an implicit recommender system designed for customer support conversations. ImpReSS operates alongside existing support chatbots, where users report issues and chatbots provide solutions. Based on a customer support conversation, ImpReSS identifies opportunities to recommend relevant solution product categories (SPCs) that help resolve the issue or prevent its recurrence -- thereby also supporting business growth. Unlike traditional CRSs, ImpReSS functions entirely implicitly and does not rely on any assumption of a user's purchasing intent. Our empirical evaluation of ImpReSS's ability to recommend relevant SPCs that can help address issues raised in support conversations shows promising results, including an MRR@1 (and recall@3) of 0.72 (0.89) for general problem solving, 0.82 (0.83) for information security support, and 0.85 (0.67) for cybersecurity troubleshooting. To support future research, our data and code will be shared upon request.

[Arxiv](https://arxiv.org/abs/2506.14231)