# 基于 LLMs 和答案集合编程的可靠协作对话智能体系统

发布时间：2025年05月09日

`Agent` `餐饮服务`

> Reliable Collaborative Conversational Agent System Based on LLMs and Answer Set Programming

# 摘要

> 随着大型语言模型驱动（LLM-driven）的AI机器人逐渐流行，人们发现它们在任务导向对话（TOD）中潜力巨大。然而，单纯依赖LLM的机器人在知识准确性上并不可靠，能否为任务生成正确结果也无法保证。这些代理之间的协作仍然是一个挑战，因为需要传递的信息不明确，信息传递依赖于提示词——这不可靠，而且恶意知识容易被注入。借助逻辑编程工具，如答案集编程（Answer Set Programming，ASP），可以安全可靠地构建对话代理，同时使代理之间的沟通更加高效和安全。我们提出了一种管理员-助理双代理范式，其中两个由ASP驱动的机器人共享同一知识库并独立完成任务，同时信息可以通过协作规则集（CRS）进行传递。传递的知识和信息被封装且对用户不可见，确保了信息传输的安全性。我们构建了AutoManager，这是一个用于管理美国塔可钟（Taco Bell）等快餐店的 drive-through 窗口的双代理系统。在AutoManager中，助理机器人负责接收顾客的订单，而管理员机器人则管理菜单和食品供应。我们对AutoManager进行了评估，并将其与现实世界中的塔可钟 Drive-Thru AI 订单接收系统进行了比较，结果显示我们的方法更加可靠。

> As the Large-Language-Model-driven (LLM-driven) Artificial Intelligence (AI) bots became popular, people realized their strong potential in Task-Oriented Dialogue (TOD). However, bots relying wholly on LLMs are unreliable in their knowledge, and whether they can finally produce a correct result for the task is not guaranteed. The collaboration among these agents also remains a challenge, since the necessary information to convey is unclear, and the information transfer is by prompts -- unreliable, and malicious knowledge is easy to inject. With the help of logic programming tools such as Answer Set Programming (ASP), conversational agents can be built safely and reliably, and communication among the agents made more efficient and secure. We proposed an Administrator-Assistant Dual-Agent paradigm, where the two ASP-driven bots share the same knowledge base and complete their tasks independently, while the information can be passed by a Collaborative Rule Set (CRS). The knowledge and information conveyed are encapsulated and invisible to the users, ensuring the security of information transmission. We have constructed AutoManager, a dual-agent system for managing the drive-through window of a fast-food restaurant such as Taco Bell in the US. In AutoManager, the assistant bot takes the customer's order while the administrator bot manages the menu and food supply. We evaluated our AutoManager and compared it with the real-world Taco Bell Drive-Thru AI Order Taker, and the results show that our method is more reliable.

[Arxiv](https://arxiv.org/abs/2505.06438)