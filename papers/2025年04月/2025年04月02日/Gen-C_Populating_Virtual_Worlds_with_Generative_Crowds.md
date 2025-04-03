# Gen-C：用生成型人群填充虚拟世界

发布时间：2025年04月02日

`LLM应用` `群体模拟` `虚拟环境`

> Gen-C: Populating Virtual Worlds with Generative Crowds

# 摘要

> 过去二十年，群体行为模拟研究取得了显著进展，但研究重点多局限于碰撞规避、路径跟随等低级任务。然而，创作引人入胜的群体场景不仅需要功能性动作，更需要捕捉代理、环境和彼此之间随时间的高层互动。为解决这一难题，我们推出Gen-C，一个生成模型，旨在自动化高层群体行为创作。Gen-C摒弃了传统繁琐的数据标注流程，转而利用大型语言模型（LLM）生成基础场景集，并通过模拟扩展和泛化，构建时间扩展图，精准建模虚拟代理的行为与互动。我们的方法采用两个变分图自编码器，由条件先验网络协同引导：一个专注于学习图结构的潜在空间（代理互动），另一个则负责节点特征（代理动作与导航）。这一创新设计使动态群体互动的生成更加灵活。训练完成的模型可基于自然语言进行条件化，赋予用户从文本描述中合成新颖群体行为的能力。我们在大学校园和火车站两个场景中验证了方法的有效性，充分展现了其在填充多样化虚拟环境方面的潜力，代理行为不仅丰富多样，更体现了复杂互动和高层决策模式。

> Over the past two decades, researchers have made significant advancements in simulating human crowds, yet these efforts largely focus on low-level tasks like collision avoidance and a narrow range of behaviors such as path following and flocking. However, creating compelling crowd scenes demands more than just functional movement-it requires capturing high-level interactions between agents, their environment, and each other over time. To address this issue, we introduce Gen-C, a generative model to automate the task of authoring high-level crowd behaviors. Gen-C bypasses the labor-intensive and challenging task of collecting and annotating real crowd video data by leveraging a large language model (LLM) to generate a limited set of crowd scenarios, which are subsequently expanded and generalized through simulations to construct time-expanded graphs that model the actions and interactions of virtual agents. Our method employs two Variational Graph Auto-Encoders guided by a condition prior network: one dedicated to learning a latent space for graph structures (agent interactions) and the other for node features (agent actions and navigation). This setup enables the flexible generation of dynamic crowd interactions. The trained model can be conditioned on natural language, empowering users to synthesize novel crowd behaviors from text descriptions. We demonstrate the effectiveness of our approach in two scenarios, a University Campus and a Train Station, showcasing its potential for populating diverse virtual environments with agents exhibiting varied and dynamic behaviors that reflect complex interactions and high-level decision-making patterns.

[Arxiv](https://arxiv.org/abs/2504.01924)