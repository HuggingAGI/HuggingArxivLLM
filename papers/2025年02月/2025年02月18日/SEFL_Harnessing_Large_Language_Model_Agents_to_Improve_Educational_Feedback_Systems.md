# SEFL：驾驭大型语言模型代理，优化教育反馈系统

发布时间：2025年02月18日

`LLM应用` `反馈系统`

> SEFL: Harnessing Large Language Model Agents to Improve Educational Feedback Systems

# 摘要

> 高质量反馈对学生成绩至关重要，但受限于时间、成本和数据稀缺性。我们推出合成教育反馈循环（SEFL），一个无需依赖大量真实学生数据即可大规模即时提供反馈的创新框架。在SEFL中，两个大型语言模型（LLMs）分别扮演教师和学生角色，模拟作业完成和形成性反馈过程，生成大量学生作品与相应评价的合成配对。随后，我们利用这些合成配对对更小、计算效率更高的LLMs进行微调，使它们能够复制高质量、目标导向反馈的关键特征。与提供多轮个性化指导的个性化辅导方法不同，SEFL专注于模拟教师→学生反馈循环，适用于多种多样的作业。通过LLM作为评估者和人工评估，我们证明了SEFL微调模型在反馈质量、清晰度和及时性方面优于未经微调的模型。这些发现揭示了SEFL在高等教育及更广泛领域中变革反馈流程的潜力，为传统人工反馈循环提供了一个既道德又可扩展的替代方案。

> Providing high-quality feedback is crucial for student success but is constrained by time, cost, and limited data availability. We introduce Synthetic Educational Feedback Loops (SEFL), a novel framework designed to deliver immediate, on-demand feedback at scale without relying on extensive, real-world student data. In SEFL, two large language models (LLMs) operate in teacher--student roles to simulate assignment completion and formative feedback, generating abundant synthetic pairs of student work and corresponding critiques. We then fine-tune smaller, more computationally efficient LLMs on these synthetic pairs, enabling them to replicate key features of high-quality, goal-oriented feedback. Unlike personalized tutoring approaches that offer multi-turn, individualized instruction, SEFL specifically focuses on replicating the teacher-->student feedback loop for diverse assignments. Through both LLM-as-a-judge and human evaluations, we demonstrate that SEFL-tuned models outperform their non-tuned counterparts in feedback quality, clarity, and timeliness. These findings reveal SEFL's potential to transform feedback processes for higher education and beyond, offering an ethical and scalable alternative to conventional manual feedback cycles.

[Arxiv](https://arxiv.org/abs/2502.12927)