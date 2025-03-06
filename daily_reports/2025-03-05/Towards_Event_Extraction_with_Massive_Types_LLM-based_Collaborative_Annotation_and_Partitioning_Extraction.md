# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。
发布时间：2025年03月04日


> Towards Event Extraction with Massive Types: LLM-based Collaborative Annotation and Partitioning Extraction
>
> 开发一个能够提取大量类型事件的通用系统一直是事件抽取（EE）领域的终极目标。然而，这一目标的实现面临两大难题：首先，缺乏高效且有效的标注方法；其次，缺乏能够处理海量类型的强大提取方法。

针对第一个难题，我们提出了一种基于大型语言模型（LLMs）的协作标注方法。通过多个LLMs的协同工作，该方法首先从远监督数据中优化触发词的标注，随后完成论元的标注。接着，通过投票机制整合不同LLMs的标注偏好，最终构建了EEMT数据集——目前规模最大、包含超过20万样本、3,465种事件类型和6,297种角色类型的EE数据集。

为了解决第二个难题，我们开发了基于LLM的分块事件抽取方法（LLM-PEE）。该方法通过先召回候选事件类型，再将它们划分为多个块供LLMs进行抽取，巧妙地克服了LLMs上下文长度的限制。在有监督实验中，LLM-PEE的事件检测和论元抽取性能分别比现有最优方法高出5.4和6.1。在零样本设置下，其性能较主流LLMs提升了12.9，充分展现了其强大的泛化能力。
>
> https://arxiv.org/abs/2503.02628

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.02628](https://arxiv.org/abs/2503.02628)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)