# # 分类不可靠叙述者与大型语言模型
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月11日

`LLM应用` `文本分析` `叙述学`

> Classifying Unreliable Narrators with Large Language Models

# 摘要

> 当我们阅读第一人称叙述的事件时，常常会思考叙述者是否可靠。本文提出了一种计算方法，用于识别那些无意中曲解信息的不可靠叙述者。我们借鉴叙事学中的文学理论，根据多种文本现象定义了不同类型的不可靠叙述者，并提出了TUNa数据集，这是一个由人类标注的多领域叙述数据集，包括博客文章、subreddit帖子、酒店评论和文学作品。我们定义了叙述内部、叙述之间和文本之间的不可靠性分类任务，并分析了开源和专有LLMs在这些任务中的表现。我们建议从文学中汲取灵感，对现实世界文本数据进行不可靠叙述者分类。为此，我们尝试了少样本学习、微调和课程学习等方法。结果显示，这一任务极具挑战性，但利用LLMs识别不可靠叙述者具有潜力。我们发布了专家标注的数据集和代码，并期待未来研究者在这一领域继续探索。

> Often when we interact with a first-person account of events, we consider whether or not the narrator, the primary speaker of the text, is reliable. In this paper, we propose using computational methods to identify unreliable narrators, i.e. those who unintentionally misrepresent information. Borrowing literary theory from narratology to define different types of unreliable narrators based on a variety of textual phenomena, we present TUNa, a human-annotated dataset of narratives from multiple domains, including blog posts, subreddit posts, hotel reviews, and works of literature. We define classification tasks for intra-narrational, inter-narrational, and inter-textual unreliabilities and analyze the performance of popular open-weight and proprietary LLMs for each. We propose learning from literature to perform unreliable narrator classification on real-world text data. To this end, we experiment with few-shot, fine-tuning, and curriculum learning settings. Our results show that this task is very challenging, and there is potential for using LLMs to identify unreliable narrators. We release our expert-annotated dataset and code and invite future research in this area.

[Arxiv](https://arxiv.org/abs/2506.10231)