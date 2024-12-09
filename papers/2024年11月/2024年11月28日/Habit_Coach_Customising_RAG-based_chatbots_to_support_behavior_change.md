# 习惯教练：定制基于 RAG 的聊天机器人来支持行为转变

发布时间：2024年11月28日

`RAG` `聊天机器人`

> Habit Coach: Customising RAG-based chatbots to support behavior change

# 摘要

> 本文展示了习惯教练的迭代开发过程，这是一款基于 GPT 的聊天机器人，旨在通过个性化互动助力用户改变习惯。我们运用以用户为中心的设计方法，借助检索增强生成（RAG）系统开发了此聊天机器人，它无需重新训练基础语言模型（GPT-4）就能实现行为个性化。该系统借助文档检索和特定提示来定制交互，汲取了认知行为疗法（CBT）和叙事治疗的技术。开发中一个关键难题是将陈述性知识转化为有效的交互行为颇为困难。初始阶段，通过参考教科书和高级对话目标为聊天机器人提供了有关 CBT 的陈述性知识。然而，这种方式致使行为不精准且低效，因为 GPT 模型难以将静态信息转化为动态且契合上下文的交互。这凸显了仅依赖陈述性知识指导聊天机器人行为的局限性，尤其是在微妙的治疗性对话里。历经四次迭代，我们通过逐步转向程序性知识、优化聊天机器人的交互策略以及提升其整体有效性来解决此问题。在最终评估中，5 名参与者连续五天与聊天机器人交流，接受个性化的 CBT 干预。采用自我报告习惯指数（SRHI）衡量干预前后的习惯强度，结果表明干预后习惯强度降低。这些结果突显了程序性知识在基于 RAG 系统中推动有效、个性化行为改变支持的重要性。

> This paper presents the iterative development of Habit Coach, a GPT-based chatbot designed to support users in habit change through personalized interaction. Employing a user-centered design approach, we developed the chatbot using a Retrieval-Augmented Generation (RAG) system, which enables behavior personalization without retraining the underlying language model (GPT-4). The system leverages document retrieval and specialized prompts to tailor interactions, drawing from Cognitive Behavioral Therapy (CBT) and narrative therapy techniques. A key challenge in the development process was the difficulty of translating declarative knowledge into effective interaction behaviors. In the initial phase, the chatbot was provided with declarative knowledge about CBT via reference textbooks and high-level conversational goals. However, this approach resulted in imprecise and inefficient behavior, as the GPT model struggled to convert static information into dynamic and contextually appropriate interactions. This highlighted the limitations of relying solely on declarative knowledge to guide chatbot behavior, particularly in nuanced, therapeutic conversations. Over four iterations, we addressed this issue by gradually transitioning towards procedural knowledge, refining the chatbot's interaction strategies, and improving its overall effectiveness. In the final evaluation, 5 participants engaged with the chatbot over five consecutive days, receiving individualized CBT interventions. The Self-Report Habit Index (SRHI) was used to measure habit strength before and after the intervention, revealing a reduction in habit strength post-intervention. These results underscore the importance of procedural knowledge in driving effective, personalized behavior change support in RAG-based systems.

[Arxiv](https://arxiv.org/abs/2411.19229)