# 个体能否操纵多智能体的集体决策？

发布时间：2025年09月19日

`Agent` `基础理论`

> Can an Individual Manipulate the Collective Decisions of Multi-Agents?

# 摘要

> 个体大型语言模型（LLMs）已在医疗、法律等众多领域展现出卓越能力。近期研究还发现，协同多智能体系统通过协作能进一步提升决策与推理能力。然而，鉴于个体LLM存在脆弱性，且多智能体系统中难以获取所有智能体的信息，一个关键问题应运而生：若攻击者仅掌握单个智能体的信息，能否生成足以误导集体决策的对抗样本？为探究这一问题，我们将其建模为不完全信息博弈：攻击者仅知晓目标智能体，而对系统中其他智能体一无所知。基于这一建模，我们提出M-Spoiler框架，该框架通过模拟多智能体系统内的交互来生成对抗样本。这些样本可用于操纵目标系统中的目标智能体，进而干扰系统的协同决策。具体而言，M-Spoiler引入“固执智能体”，通过模拟目标系统中智能体可能的固执行为，主动协助优化对抗样本。这显著增强了对抗样本误导系统的效果。通过在多任务上的大量实验，我们证实了掌握多智能体系统中单个智能体信息的风险，并验证了所提框架的有效性。我们还测试了多种防御机制，结果显示所提攻击框架的性能仍优于基线方法，这凸显了深入研究防御策略的迫切性。

> Individual Large Language Models (LLMs) have demonstrated significant capabilities across various domains, such as healthcare and law. Recent studies also show that coordinated multi-agent systems exhibit enhanced decision-making and reasoning abilities through collaboration. However, due to the vulnerabilities of individual LLMs and the difficulty of accessing all agents in a multi-agent system, a key question arises: If attackers only know one agent, could they still generate adversarial samples capable of misleading the collective decision? To explore this question, we formulate it as a game with incomplete information, where attackers know only one target agent and lack knowledge of the other agents in the system. With this formulation, we propose M-Spoiler, a framework that simulates agent interactions within a multi-agent system to generate adversarial samples. These samples are then used to manipulate the target agent in the target system, misleading the system's collaborative decision-making process. More specifically, M-Spoiler introduces a stubborn agent that actively aids in optimizing adversarial samples by simulating potential stubborn responses from agents in the target system. This enhances the effectiveness of the generated adversarial samples in misleading the system. Through extensive experiments across various tasks, our findings confirm the risks posed by the knowledge of an individual agent in multi-agent systems and demonstrate the effectiveness of our framework. We also explore several defense mechanisms, showing that our proposed attack framework remains more potent than baselines, underscoring the need for further research into defensive strategies.

[Arxiv](https://arxiv.org/abs/2509.16494)