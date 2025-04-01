# # 让智能体陷入迷醉：自主智能体推荐系统中的记忆扰动研究

发布时间：2025年03月31日

`Agent` `推荐系统` `人工智能安全`

> Get the Agents Drunk: Memory Perturbations in Autonomous Agent-based Recommender Systems

# 摘要

> 基于大型语言模型的智能体（Agent4RSs）在推荐系统中被越来越多地用于实现个性化行为建模。具体而言，Agent4RSs引入了记忆机制，使智能体能够从现实世界的交互中自主学习和自我进化。然而，据我们所知，Agent4RSs的鲁棒性尚未得到充分研究。因此，在本文中，我们提出了首个针对Agent4RSs的攻击方法，通过扰动生成智能体的记忆，不仅揭示其局限性，还增强其安全性和鲁棒性，确保更安全可靠的AI智能体的发展。

考虑到安全性和隐私问题，在黑盒设置下发起攻击更具实际意义，因为在这种情况下，难以轻易获得受害者模型的准确信息。此外，实际攻击通常具有隐蔽性以最大化其影响。为此，我们提出了一种新型实用攻击框架，名为DrunkAgent。DrunkAgent由生成模块、策略模块和代理模块组成。生成模块旨在生成有效且连贯的对抗文本触发器，可用于实现攻击目标，如促进目标项目。策略模块旨在“让目标智能体喝醉”，使得它们无法在交互过程中有效更新记忆。因此，触发器可以发挥最佳作用。这两个模块都在代理模块上进行优化，以提高攻击的可迁移性和不可察觉性。通过识别和分析漏洞，我们的工作提供了关键见解，为构建更安全和更具韧性的Agent4RSs铺平了道路。在各种真实世界数据集上的广泛实验验证了DrunkAgent的有效性。

> Large language model-based agents are increasingly used in recommender systems (Agent4RSs) to achieve personalized behavior modeling. Specifically, Agent4RSs introduces memory mechanisms that enable the agents to autonomously learn and self-evolve from real-world interactions. However, to the best of our knowledge, how robust Agent4RSs are remains unexplored. As such, in this paper, we propose the first work to attack Agent4RSs by perturbing agents' memories, not only to uncover their limitations but also to enhance their security and robustness, ensuring the development of safer and more reliable AI agents.
  Given the security and privacy concerns, it is more practical to launch attacks under a black-box setting, where the accurate knowledge of the victim models cannot be easily obtained. Moreover, the practical attacks are often stealthy to maximize the impact. To this end, we propose a novel practical attack framework named DrunkAgent. DrunkAgent consists of a generation module, a strategy module, and a surrogate module. The generation module aims to produce effective and coherent adversarial textual triggers, which can be used to achieve attack objectives such as promoting the target items. The strategy module is designed to `get the target agents drunk' so that their memories cannot be effectively updated during the interaction process. As such, the triggers can play the best role. Both of the modules are optimized on the surrogate module to improve the transferability and imperceptibility of the attacks. By identifying and analyzing the vulnerabilities, our work provides critical insights that pave the way for building safer and more resilient Agent4RSs. Extensive experiments across various real-world datasets demonstrate the effectiveness of DrunkAgent.

[Arxiv](https://arxiv.org/abs/2503.23804)