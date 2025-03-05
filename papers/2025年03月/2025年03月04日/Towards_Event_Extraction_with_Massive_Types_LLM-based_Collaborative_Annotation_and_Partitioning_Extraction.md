# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月04日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来解决事件抽取（EE）中的两个关键问题：标注方法和提取方法。论文提出了基于LLMs的协作标注方法和分块事件抽取方法，展示了LLMs在事件抽取中的具体应用及其效果。因此，这篇论文属于LLM应用类别。` `人工智能`

> Towards Event Extraction with Massive Types: LLM-based Collaborative Annotation and Partitioning Extraction

# 摘要

> 开发一个能够提取大量类型事件的通用系统一直是事件抽取（EE）领域的终极目标。然而，这一目标的实现面临两大难题：首先，缺乏高效且有效的标注方法；其次，缺乏能够处理海量类型的强大提取方法。

针对第一个难题，我们提出了一种基于大型语言模型（LLMs）的协作标注方法。通过多个LLMs的协同工作，该方法首先从远监督数据中优化触发词的标注，随后完成论元的标注。接着，通过投票机制整合不同LLMs的标注偏好，最终构建了EEMT数据集——目前规模最大、包含超过20万样本、3,465种事件类型和6,297种角色类型的EE数据集。

为了解决第二个难题，我们开发了基于LLM的分块事件抽取方法（LLM-PEE）。该方法通过先召回候选事件类型，再将它们划分为多个块供LLMs进行抽取，巧妙地克服了LLMs上下文长度的限制。在有监督实验中，LLM-PEE的事件检测和论元抽取性能分别比现有最优方法高出5.4和6.1。在零样本设置下，其性能较主流LLMs提升了12.9，充分展现了其强大的泛化能力。

> Developing a general-purpose extraction system that can extract events with massive types is a long-standing target in Event Extraction (EE). In doing so, the challenge comes from two aspects: 1) The absence of an efficient and effective annotation method. 2) The absence of a powerful extraction method can handle massive types. For the first challenge, we propose a collaborative annotation method based on Large Language Models (LLMs). Through collaboration among multiple LLMs, it first refines annotations of trigger words from distant supervision and then carries out argument annotation. Next, a voting phase consolidates the annotation preferences across different LLMs. Finally, we create the EEMT dataset, the largest EE dataset to date, featuring over 200,000 samples, 3,465 event types, and 6,297 role types. For the second challenge, we propose an LLM-based Partitioning EE method called LLM-PEE. To overcome the limited context length of LLMs, LLM-PEE first recalls candidate event types and then splits them into multiple partitions for LLMs to extract events. The results in the supervised setting show that LLM-PEE outperforms the state-of-the-art methods by 5.4 in event detection and 6.1 in argument extraction. In the zero-shot setting, LLM-PEE achieves up to 12.9 improvement compared to mainstream LLMs, demonstrating its strong generalization capabilities.

[Arxiv](https://arxiv.org/abs/2503.02628)