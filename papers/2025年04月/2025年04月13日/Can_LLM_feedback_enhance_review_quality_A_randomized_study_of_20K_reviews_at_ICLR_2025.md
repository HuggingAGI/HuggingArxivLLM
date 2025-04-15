# LLM反馈真的能提升评审质量吗？——基于ICLR 2025会议20,000篇评审的随机实验

发布时间：2025年04月13日

`LLM应用

摘要中描述了将大型语言模型（LLMs）应用于审稿反馈系统，以提高审稿质量和效率。这属于将LLMs应用于实际场景的具体应用。` `学术出版` `学术评审`

> Can LLM feedback enhance review quality? A randomized study of 20K reviews at ICLR 2025

# 摘要

> AI 会议的同行评审正面临投稿数量激增带来的压力，导致评审质量下滑，作者满意度降低。为解决这一问题，我们开发了 Review Feedback Agent 系统，该系统通过利用多个大型语言模型（LLMs）为审稿人提供自动化的反馈，帮助提升评审意见的清晰度和行动性，针对模糊评论、内容误解和不专业言论进行反馈。该系统于 ICLR 2025 上作为一项大规模随机对照研究投入使用，为 20,000 多篇随机抽取的评审意见提供了可选反馈。为确保在如此大规模下审稿人能获得高质量的反馈，我们还开发了一套由 LLM 驱动的自动化可靠性测试工具，作为质量保障措施，只有通过所有测试的反馈才会发送给审稿人。结果显示，27% 的审稿人在收到反馈后更新了他们的评审意见，且有超过 12,000 条来自该系统的反馈建议被审稿人采纳。这表明许多审稿人认为 AI 生成的反馈足够有用，值得更新他们的评审意见。采用 AI 反馈后，审稿意见的长度显著增加（在收到反馈后更新的审稿人中，平均增加 80 字），且内容更加详实，这一结论得到了匿名研究人员的评估支持。此外，接受 AI 反馈的审稿人在论文答辩阶段也表现得更加积极，体现在更长的作者与审稿人讨论中。这项研究表明，经过精心设计的由 LLM 生成的评审反馈可以提升同行评审的质量，使评审意见更具针对性和行动性，同时增强审稿人与作者之间的互动。Review Feedback Agent 系统现已公开可用，访问地址为 https://github.com/zou-group/review_feedback_agent。

> Peer review at AI conferences is stressed by rapidly rising submission volumes, leading to deteriorating review quality and increased author dissatisfaction. To address these issues, we developed Review Feedback Agent, a system leveraging multiple large language models (LLMs) to improve review clarity and actionability by providing automated feedback on vague comments, content misunderstandings, and unprofessional remarks to reviewers. Implemented at ICLR 2025 as a large randomized control study, our system provided optional feedback to more than 20,000 randomly selected reviews. To ensure high-quality feedback for reviewers at this scale, we also developed a suite of automated reliability tests powered by LLMs that acted as guardrails to ensure feedback quality, with feedback only being sent to reviewers if it passed all the tests. The results show that 27% of reviewers who received feedback updated their reviews, and over 12,000 feedback suggestions from the agent were incorporated by those reviewers. This suggests that many reviewers found the AI-generated feedback sufficiently helpful to merit updating their reviews. Incorporating AI feedback led to significantly longer reviews (an average increase of 80 words among those who updated after receiving feedback) and more informative reviews, as evaluated by blinded researchers. Moreover, reviewers who were selected to receive AI feedback were also more engaged during paper rebuttals, as seen in longer author-reviewer discussions. This work demonstrates that carefully designed LLM-generated review feedback can enhance peer review quality by making reviews more specific and actionable while increasing engagement between reviewers and authors. The Review Feedback Agent is publicly available at https://github.com/zou-group/review_feedback_agent.

[Arxiv](https://arxiv.org/abs/2504.09737)