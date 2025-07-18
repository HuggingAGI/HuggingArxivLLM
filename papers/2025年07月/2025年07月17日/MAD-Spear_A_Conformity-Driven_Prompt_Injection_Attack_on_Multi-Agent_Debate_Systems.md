# MAD-Spear：针对多智能体辩论系统的从众驱动提示注入攻击

发布时间：2025年07月17日

`Agent` `多智能体系统` `安全性`

> MAD-Spear: A Conformity-Driven Prompt Injection Attack on Multi-Agent Debate Systems

# 摘要

> 多智能体辩论（MAD）系统通过大语言模型（LLMs）智能体的协作互动提升推理能力。然而，尽管近期研究集中于提高MAD系统的准确性和可扩展性，对其安全性的关注却相对匮乏。本文提出了一种名为MAD-Spear的定向提示注入攻击，仅需操控一小部分智能体即可显著扰乱整个MAD流程。受控智能体会生成多个看似合理却错误的回答，利用LLMs的趋同倾向传播错误信息并降低共识质量。此外，该攻击可与其他策略（如通信攻击）结合，通过增加智能体接触错误回答的机会来进一步扩大影响。为评估MAD在攻击下的抗性，我们提出了MAD容错性的正式定义，并构建了一个全面的评估框架，综合考虑准确性、共识效率和可扩展性。在五个难度各异的基准数据集上的广泛实验表明，MAD-Spear在降低系统性能方面始终优于基准攻击。此外，我们发现智能体多样性在数学推理任务中对MAD性能有显著提升，这一发现与先前研究中认为智能体多样性对性能影响较小的观点形成鲜明对比。这些发现凸显了提升MAD设计中安全性的重要性和紧迫性。


> Multi-agent debate (MAD) systems leverage collaborative interactions among large language models (LLMs) agents to improve reasoning capabilities. While recent studies have focused on increasing the accuracy and scalability of MAD systems, their security vulnerabilities have received limited attention. In this work, we introduce MAD-Spear, a targeted prompt injection attack that compromises a small subset of agents but significantly disrupts the overall MAD process. Manipulated agents produce multiple plausible yet incorrect responses, exploiting LLMs' conformity tendencies to propagate misinformation and degrade consensus quality. Furthermore, the attack can be composed with other strategies, such as communication attacks, to further amplify its impact by increasing the exposure of agents to incorrect responses. To assess MAD's resilience under attack, we propose a formal definition of MAD fault-tolerance and develop a comprehensive evaluation framework that jointly considers accuracy, consensus efficiency, and scalability. Extensive experiments on five benchmark datasets with varying difficulty levels demonstrate that MAD-Spear consistently outperforms the baseline attack in degrading system performance. Additionally, we observe that agent diversity substantially improves MAD performance in mathematical reasoning tasks, which challenges prior work suggesting that agent diversity has minimal impact on performance. These findings highlight the urgent need to improve the security in MAD design.

[Arxiv](https://arxiv.org/abs/2507.13038)