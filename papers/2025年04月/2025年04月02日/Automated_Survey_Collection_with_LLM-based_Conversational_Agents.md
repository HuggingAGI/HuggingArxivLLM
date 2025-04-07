# 基于LLM的对话代理助力自动化调查收集

发布时间：2025年04月02日

`LLM应用` `电话调查`

> Automated Survey Collection with LLM-based Conversational Agents

# 摘要

> 目标：传统电话调查是收集生物医学和健康数据的重要手段，但成本高、耗时长且难以大规模应用。为解决这些问题，我们提出了一种基于对话大型语言模型（LLMs）的端到端调查框架。

材料与方法：我们的框架包括：负责设计调查的研究人员；一个基于LLM的智能电话代理，用于联系参与者并执行调查；一个用于分析对话记录的GPT-4o模型；以及存储数据的数据库。我们招募了8名参与者（5名母语者和3名非母语者），完成了40次调查测试，评估了对话记录的准确性和参与者体验。

结果：尽管对话记录平均每行有7.7%的错误，GPT-4o仍以98%的准确率提取了调查回答。参与者指出，虽然LLM代理偶尔会出错，但总体表现良好，能够清晰传达调查意图并保持有趣互动。

结论：本研究证明了LLM代理在 healthcare 领域进行电话调查的潜力。该方法不仅降低了人工成本，还为未来开发基于AI的端到端电话调查系统提供了可行方案。

> Objective: Traditional phone-based surveys are among the most accessible and widely used methods to collect biomedical and healthcare data, however, they are often costly, labor intensive, and difficult to scale effectively. To overcome these limitations, we propose an end-to-end survey collection framework driven by conversational Large Language Models (LLMs).
  Materials and Methods: Our framework consists of a researcher responsible for designing the survey and recruiting participants, a conversational phone agent powered by an LLM that calls participants and administers the survey, a second LLM (GPT-4o) that analyzes the conversation transcripts generated during the surveys, and a database for storing and organizing the results. To test our framework, we recruited 8 participants consisting of 5 native and 3 non-native english speakers and administered 40 surveys. We evaluated the correctness of LLM-generated conversation transcripts, accuracy of survey responses inferred by GPT-4o and overall participant experience.
  Results: Survey responses were successfully extracted by GPT-4o from conversation transcripts with an average accuracy of 98% despite transcripts exhibiting an average per-line word error rate of 7.7%. While participants noted occasional errors made by the conversational LLM agent, they reported that the agent effectively conveyed the purpose of the survey, demonstrated good comprehension, and maintained an engaging interaction.
  Conclusions: Our study highlights the potential of LLM agents in conducting and analyzing phone surveys for healthcare applications. By reducing the workload on human interviewers and offering a scalable solution, this approach paves the way for real-world, end-to-end AI-powered phone survey collection systems.

[Arxiv](https://arxiv.org/abs/2504.02891)