# 生成对抗评论：当LLM化身评论家

发布时间：2024年12月09日

`Agent

理由：这篇论文描述了一个利用大型语言模型（LLM）赋能的代理（GAR）来模拟同行评审的过程。该代理具备记忆能力，并且通过基于图的稿件表示和外部知识来评估论文的创新性和质量。论文的核心是设计了一个代理系统，用于模拟人类评审员的行为，因此属于Agent类别。` `学术出版` `同行评审`

> Generative Adversarial Reviews: When LLMs Become the Critic

# 摘要

> 同行评审是科学进步的基石，决定了哪些论文能够达到出版标准。然而，学术产出的激增和知识领域的日益细分，使得传统科学反馈机制不堪重负。为此，我们推出了生成式代理评审员（GAR），利用LLM赋能的代理来模拟真实的同行评审。为了实现这一目标，我们设计了一种架构，扩展了具备记忆能力的大型语言模型，并为代理配备了基于历史数据的评审员角色。该架构的核心是基于图的稿件表示，它浓缩内容并逻辑地组织信息，将观点与证据和技术细节紧密关联。GAR的评审过程首先利用外部知识评估论文的创新性，随后通过图表示和多轮评估进行详细分析。最后，元评审员汇总各评审意见，预测论文的最终命运。实验表明，GAR在提供详细反馈和预测论文结果方面与人类评审员旗鼓相当。除了性能对比，我们还进行了深入实验，如评估评审员专业知识的影响和评审的公平性。通过提供通常仅限于少数研究人员的早期专家级反馈，GAR让透明且深入的评审变得触手可及。

> The peer review process is fundamental to scientific progress, determining which papers meet the quality standards for publication. Yet, the rapid growth of scholarly production and increasing specialization in knowledge areas strain traditional scientific feedback mechanisms. In light of this, we introduce Generative Agent Reviewers (GAR), leveraging LLM-empowered agents to simulate faithful peer reviewers. To enable generative reviewers, we design an architecture that extends a large language model with memory capabilities and equips agents with reviewer personas derived from historical data. Central to this approach is a graph-based representation of manuscripts, condensing content and logically organizing information - linking ideas with evidence and technical details. GAR's review process leverages external knowledge to evaluate paper novelty, followed by detailed assessment using the graph representation and multi-round assessment. Finally, a meta-reviewer aggregates individual reviews to predict the acceptance decision. Our experiments demonstrate that GAR performs comparably to human reviewers in providing detailed feedback and predicting paper outcomes. Beyond mere performance comparison, we conduct insightful experiments, such as evaluating the impact of reviewer expertise and examining fairness in reviews. By offering early expert-level feedback, typically restricted to a limited group of researchers, GAR democratizes access to transparent and in-depth evaluation.

[Arxiv](https://arxiv.org/abs/2412.10415)