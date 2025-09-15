# 当评审者是大型语言模型（LLM）时：同行评审中的偏见、分歧与提示词注入风险

发布时间：2025年09月11日

`LLM应用` `基础理论`

> When Your Reviewer is an LLM: Biases, Divergence, and Prompt Injection Risks in Peer Review

# 摘要

> 同行评审是学术出版的基石，然而随着投稿量攀升、审稿人不堪重负以及专业匹配度不足，这一流程正愈发捉襟见肘。如今大型语言模型（LLMs）被用作“审稿辅助工具”，但这也引发了对其公平性、一致性，以及抵御间接提示注入攻击能力的担忧。本文系统性评估了LLMs作为学术审稿人的表现。研究团队基于ICLR 2023和NeurIPS 2022的1441篇论文构建数据集，从评分、优势、劣势三方面对比GPT-5-mini与人类审稿人的差异，并通过参考论文校准的结构化提示、主题建模及相似性分析来比对评审内容。研究还将隐蔽指令嵌入PDF投稿文件，以测试LLMs对提示注入的脆弱性。结果显示，LLMs对质量欠佳的论文往往给出虚高评分，但对优质成果的评价则与人类判断更为吻合。此外，尽管总体性恶意提示仅轻微改变评审的主题焦点，但针对性的领域特定指令却能成功操控LLM评审中的特定内容。这项研究揭示了LLMs融入同行评审的潜力与隐患，同时强调设计保障机制以维护未来评审流程的公正性和可信度至关重要。

> Peer review is the cornerstone of academic publishing, yet the process is increasingly strained by rising submission volumes, reviewer overload, and expertise mismatches. Large language models (LLMs) are now being used as "reviewer aids," raising concerns about their fairness, consistency, and robustness against indirect prompt injection attacks. This paper presents a systematic evaluation of LLMs as academic reviewers. Using a curated dataset of 1,441 papers from ICLR 2023 and NeurIPS 2022, we evaluate GPT-5-mini against human reviewers across ratings, strengths, and weaknesses. The evaluation employs structured prompting with reference paper calibration, topic modeling, and similarity analysis to compare review content. We further embed covert instructions into PDF submissions to assess LLMs' susceptibility to prompt injection. Our findings show that LLMs consistently inflate ratings for weaker papers while aligning more closely with human judgments on stronger contributions. Moreover, while overarching malicious prompts induce only minor shifts in topical focus, explicitly field-specific instructions successfully manipulate specific aspects of LLM-generated reviews. This study underscores both the promises and perils of integrating LLMs into peer review and points to the importance of designing safeguards that ensure integrity and trust in future review processes.

[Arxiv](https://arxiv.org/abs/2509.09912)