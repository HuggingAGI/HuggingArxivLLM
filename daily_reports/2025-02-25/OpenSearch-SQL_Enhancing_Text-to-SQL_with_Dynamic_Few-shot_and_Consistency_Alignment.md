# # 摘要  
    OpenSearch-SQL：通过动态少样本学习与一致性对齐提升文本到SQL能力  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。
发布时间：2025年02月19日

`代码编写`
> OpenSearch-SQL: Enhancing Text-to-SQL with Dynamic Few-shot and Consistency Alignment
>
> 尽管多智能体协作的大语言模型（LLMs）在Text-to-SQL任务中取得了显著突破，但其性能仍受限于多种因素，包括框架的不完善、未能遵循指令以及模型幻觉问题。为解决这些问题，我们提出了OpenSearch-SQL，该方法将Text-to-SQL任务分解为预处理、抽取、生成和优化四个主要模块，以及一个基于一致性对齐机制的对齐模块。通过Alignment模块对齐各智能体的输入和输出，减少了指令遵循失败和幻觉问题。此外，我们设计了一种中间语言SQL-Like，并基于SQL-Like优化了结构化CoT。同时，我们开发了一种以自我学习的Query-CoT-SQL形式呈现的动态少样本策略。这些方法显著提升了LLMs在Text-to-SQL任务中的性能。

在模型选择方面，我们直接应用基础LLMs，无需后训练，从而简化了任务链并增强了框架的可移植性。实验结果显示，OpenSearch-SQL在BIRD开发集上的执行准确率（EX）为69.3%，测试集为72.28%，基于奖励的有效性效率得分（R-VES）为69.36%，三项指标在提交时均排名第一。这些结果充分展示了所提方法在有效性和效率方面的综合优势。
>
> https://arxiv.org/abs/2502.14913

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.14913](https://arxiv.org/abs/2502.14913)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)