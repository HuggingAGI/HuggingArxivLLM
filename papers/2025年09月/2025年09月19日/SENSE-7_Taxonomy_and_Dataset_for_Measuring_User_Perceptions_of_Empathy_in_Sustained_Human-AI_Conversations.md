# SENSE-7：面向持续人机对话中用户共情感知测量的分类体系与数据集

发布时间：2025年09月19日

`LLM应用` `基础理论`

> SENSE-7: Taxonomy and Dataset for Measuring User Perceptions of Empathy in Sustained Human-AI Conversations

# 摘要

> 共情在人机交互中日益成为关键因素，但传统“数字共情”方法常专注于模拟人类的内在情感状态，却忽略了用户感知中共情固有的主观性、情境性与关系性特征。本研究提出以人为中心的分类框架，聚焦可观察的共情行为，并构建新数据集Sense-7——该数据集涵盖信息工作者与大型语言模型（LLMs）的真实对话，包含用户每轮共情标注、用户特征及情境细节，从而提供更贴合用户视角的共情表征。通过分析109名参与者的695次对话发现：共情判断具有高度个性化和情境敏感性，当对话连续性中断或用户期望未满足时，共情感知极易受影响。为推动后续研究，我们公开672个匿名对话子集，并开展探索性分类分析。结果显示，基于LLM的分类器可识别5级共情水平，在该数据集上平均Spearman【数学公式】=0.369、准确率达0.487，表现值得期待。综上，本研究强调AI设计需动态适配用户情境与目标来调整共情行为，为未来开发具有社会适应性的以人为中心的人工智能体提供了研究路线图与实践方向。

> Empathy is increasingly recognized as a key factor in human-AI communication, yet conventional approaches to "digital empathy" often focus on simulating internal, human-like emotional states while overlooking the inherently subjective, contextual, and relational facets of empathy as perceived by users. In this work, we propose a human-centered taxonomy that emphasizes observable empathic behaviors and introduce a new dataset, Sense-7, of real-world conversations between information workers and Large Language Models (LLMs), which includes per-turn empathy annotations directly from the users, along with user characteristics, and contextual details, offering a more user-grounded representation of empathy. Analysis of 695 conversations from 109 participants reveals that empathy judgments are highly individualized, context-sensitive, and vulnerable to disruption when conversational continuity fails or user expectations go unmet. To promote further research, we provide a subset of 672 anonymized conversation and provide exploratory classification analysis, showing that an LLM-based classifier can recognize 5 levels of empathy with an encouraging average Spearman $ρ$=0.369 and Accuracy=0.487 over this set. Overall, our findings underscore the need for AI designs that dynamically tailor empathic behaviors to user contexts and goals, offering a roadmap for future research and practical development of socially attuned, human-centered artificial agents.

[Arxiv](https://arxiv.org/abs/2509.16437)