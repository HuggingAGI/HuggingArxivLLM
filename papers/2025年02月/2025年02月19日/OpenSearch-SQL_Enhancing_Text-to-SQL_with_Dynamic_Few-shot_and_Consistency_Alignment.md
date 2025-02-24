# # 摘要  
    OpenSearch-SQL：通过动态少样本学习与一致性对齐提升文本到SQL能力  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年02月19日

`LLM应用` `数据库`

> OpenSearch-SQL: Enhancing Text-to-SQL with Dynamic Few-shot and Consistency Alignment

# 摘要

> 尽管多智能体协作的大语言模型（LLMs）在Text-to-SQL任务中取得了显著突破，但其性能仍受限于多种因素，包括框架的不完善、未能遵循指令以及模型幻觉问题。为解决这些问题，我们提出了OpenSearch-SQL，该方法将Text-to-SQL任务分解为预处理、抽取、生成和优化四个主要模块，以及一个基于一致性对齐机制的对齐模块。通过Alignment模块对齐各智能体的输入和输出，减少了指令遵循失败和幻觉问题。此外，我们设计了一种中间语言SQL-Like，并基于SQL-Like优化了结构化CoT。同时，我们开发了一种以自我学习的Query-CoT-SQL形式呈现的动态少样本策略。这些方法显著提升了LLMs在Text-to-SQL任务中的性能。

在模型选择方面，我们直接应用基础LLMs，无需后训练，从而简化了任务链并增强了框架的可移植性。实验结果显示，OpenSearch-SQL在BIRD开发集上的执行准确率（EX）为69.3%，测试集为72.28%，基于奖励的有效性效率得分（R-VES）为69.36%，三项指标在提交时均排名第一。这些结果充分展示了所提方法在有效性和效率方面的综合优势。

> Although multi-agent collaborative Large Language Models (LLMs) have achieved significant breakthroughs in the Text-to-SQL task, their performance is still constrained by various factors. These factors include the incompleteness of the framework, failure to follow instructions, and model hallucination problems. To address these problems, we propose OpenSearch-SQL, which divides the Text-to-SQL task into four main modules: Preprocessing, Extraction, Generation, and Refinement, along with an Alignment module based on a consistency alignment mechanism. This architecture aligns the inputs and outputs of agents through the Alignment module, reducing failures in instruction following and hallucination. Additionally, we designed an intermediate language called SQL-Like and optimized the structured CoT based on SQL-Like. Meanwhile, we developed a dynamic few-shot strategy in the form of self-taught Query-CoT-SQL. These methods have significantly improved the performance of LLMs in the Text-to-SQL task.
  In terms of model selection, we directly applied the base LLMs without any post-training, thereby simplifying the task chain and enhancing the framework's portability. Experimental results show that OpenSearch-SQL achieves an execution accuracy(EX) of 69.3% on the BIRD development set, 72.28% on the test set, and a reward-based validity efficiency score (R-VES) of 69.36%, with all three metrics ranking first at the time of submission. These results demonstrate the comprehensive advantages of the proposed method in both effectiveness and efficiency.

[Arxiv](https://arxiv.org/abs/2502.14913)