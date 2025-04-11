# 合成高质量编程任务：基于LLM的专家与学习者智能体

发布时间：2025年04月10日

`LLM应用

理由：这篇论文探讨了生成式AI在教育中的应用，特别是在编程任务生成方面的潜力。它提出了一种新的合成技术PyTaskSyn，用于生成和评估编程任务的质量，以帮助学习者。虽然它没有深入探讨LLM的理论或架构，但展示了生成式AI在教育中的实际应用和效果，因此属于LLM应用类别。` `计算机教育` `编程任务`

> Synthesizing High-Quality Programming Tasks with LLM-based Expert and Student Agents

# 摘要

> 生成式AI正在重新定义计算机教育，通过自动生成个性化内容和反馈为学习者提供全新体验。我们深入探究了其在为学生提供高质量编程任务方面的潜力。尽管任务生成技术取得了显著进步，AI生成的任务与专家设计的任务之间仍存在显著的质量差距。AI生成的任务可能无法精准匹配目标编程概念，可能令学生难以理解，甚至可能包含测试错误等关键问题。现有解决方案通常需要人工教师的额外验证。为解决这些挑战，我们推出了PyTaskSyn——一种创新的合成技术，它不仅能够生成编程任务，还能智能评估任务质量，确保其适合学生使用。PyTaskSyn的核心理念是将任务生成与质量评估分离，通过强生成模型模拟专家代理，弱生成模型模拟学生代理，分阶段完成任务的生成与验证。经过全面评估，我们发现PyTaskSyn生成的任务质量远超传统方法，充分展现了其验证流水线中各代理类型的独特价值。此外，我们通过公开的网络应用程序开展用户研究，结果表明PyTaskSyn不仅能够生成媲美专家设计的高质量编程任务，还能显著降低工作量和成本，同时为学生提供更具吸引力的学习体验，超越现有在线资源。

> Generative AI is transforming computing education by enabling the automatic generation of personalized content and feedback. We investigate its capabilities in providing high-quality programming tasks to students. Despite promising advancements in task generation, a quality gap remains between AI-generated and expert-created tasks. The AI-generated tasks may not align with target programming concepts, could be incomprehensible for students to solve, or may contain critical issues such as incorrect tests. Existing works often require interventions from human teachers for validation. We address these challenges by introducing PyTaskSyn, a novel synthesis technique that first generates a programming task and then decides whether it meets certain quality criteria to be given to students. The key idea is to break this process into multiple stages performed by expert and student agents simulated using both strong and weaker generative models. Through extensive evaluation, we show that PyTaskSyn significantly improves task quality compared to baseline techniques and showcases the importance of each specialized agent type in our validation pipeline. Additionally, we conducted user studies using our publicly available web application and show that PyTaskSyn can deliver high-quality programming tasks comparable to expert-designed ones while reducing workload and costs, and being more engaging than programming tasks that are available in online resources.

[Arxiv](https://arxiv.org/abs/2504.07655)