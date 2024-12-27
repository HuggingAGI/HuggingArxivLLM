# 生成式代理：人类行为的互动式拟像

发布时间：2023年04月07日

`Agent` `交互式应用` `模拟环境`

> Generative Agents: Interactive Simulacra of Human Behavior

# 摘要

> 摘要：人类行为的可信代理能够为各类交互式应用提供助力，涵盖从沉浸式环境到人际交流的演练空间，再到原型工具等领域。在本文中，我们引入了生成式代理——能够模拟可信人类行为的计算软件代理。生成式代理会起床、做早餐然后去上班；艺术家作画，作家写作；他们形成看法，留意彼此，并开启对话；他们铭记并反思过往的日子，同时规划次日的安排。为实现生成式代理，我们描述了一种架构，其拓展了大型语言模型，以自然语言存储代理的全部经历记录，随时间将这些记忆整合成更高级的思考，并动态检索以规划行为。我们实例化生成式代理来填充一个受《模拟人生》启发的交互式沙盒环境，最终用户能够使用自然语言与由 25 个代理构成的小镇进行互动。在一次评估中，这些生成式代理展现出了可信的个体及新兴的社会行为：比如，仅从用户指定的一个代理想要举办情人节派对这一概念出发，代理们在接下来的两天里自主传播派对邀请，结识新友，互相邀约参加派对，并协调好在恰当的时间一同赴会。通过消融实验，我们证明了代理架构的组件——观察、规划和反思——均对代理行为的可信度有着至关重要的作用。通过将大型语言模型与计算、交互式代理相融合，此项工作引入了实现人类行为可信模拟的架构和交互模式。

> 
Abstract:Believable proxies of human behavior can empower interactive applications ranging from immersive environments to rehearsal spaces for interpersonal communication to prototyping tools. In this paper, we introduce generative agents--computational software agents that simulate believable human behavior. Generative agents wake up, cook breakfast, and head to work; artists paint, while authors write; they form opinions, notice each other, and initiate conversations; they remember and reflect on days past as they plan the next day. To enable generative agents, we describe an architecture that extends a large language model to store a complete record of the agent's experiences using natural language, synthesize those memories over time into higher-level reflections, and retrieve them dynamically to plan behavior. We instantiate generative agents to populate an interactive sandbox environment inspired by The Sims, where end users can interact with a small town of twenty five agents using natural language. In an evaluation, these generative agents produce believable individual and emergent social behaviors: for example, starting with only a single user-specified notion that one agent wants to throw a Valentine's Day party, the agents autonomously spread invitations to the party over the next two days, make new acquaintances, ask each other out on dates to the party, and coordinate to show up for the party together at the right time. We demonstrate through ablation that the components of our agent architecture--observation, planning, and reflection--each contribute critically to the believability of agent behavior. By fusing large language models with computational, interactive agents, this work introduces architectural and interaction patterns for enabling believable simulations of human behavior.
    

[Arxiv](https://arxiv.org/pdf/2304.03442)