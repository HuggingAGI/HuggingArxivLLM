# 走出泥潭：探究大型语言模型中的承诺升级现象

发布时间：2025年08月02日

`LLM应用` `决策系统` `人工智能`

> Getting out of the Big-Muddy: Escalation of Commitment in LLMs

# 摘要

> 大型语言模型（LLMs）正在越来越多的关键领域中被部署到自主决策角色中。然而，由于模型是基于人类生成的数据进行训练的，它们可能会继承系统性扭曲人类判断的认知偏见，包括承诺升级，即决策者由于前期投入而继续对失败的行动方案进行投资。理解LLMs何时表现出此类偏见是一个独特的挑战。虽然这些偏见在人类中已有充分记录，但尚不清楚它们是否会在LLMs中持续出现，或者是否需要特定的触发条件。

本文通过一个两阶段的投资任务，跨四个实验条件（模型作为投资者、模型作为顾问、多代理决策以及复合压力场景）来研究这一问题。在总共N=6,500次试验中，我们发现LLMs的偏见表现高度依赖于上下文。

在个体决策情境下（研究1-2，N=4,000），LLMs表现出强大的理性成本收益逻辑，承诺升级现象微乎其微。然而，多代理决策揭示了一个显著的层级效应（研究3，N=500）：虽然不对称层级结构显示出中等程度的升级率（46.2%），但对称的基于同侪的决策导致近乎普遍的升级（99.2%）。同样地，当面临组织和个人的复合压力时（研究4，N=2,000），模型表现出高度的承诺升级（平均分配68.95%的资源到失败的部门）。

这些发现表明，LLMs的偏见表现关键取决于社会和组织背景，而非与生俱来，这对多代理系统的部署和可能自然出现此类情境的无监督运行具有重要影响。

> Large Language Models (LLMs) are increasingly deployed in autonomous decision-making roles across high-stakes domains. However, since models are trained on human-generated data, they may inherit cognitive biases that systematically distort human judgment, including escalation of commitment, where decision-makers continue investing in failing courses of action due to prior investment. Understanding when LLMs exhibit such biases presents a unique challenge. While these biases are well-documented in humans, it remains unclear whether they manifest consistently in LLMs or require specific triggering conditions. This paper investigates this question using a two-stage investment task across four experimental conditions: model as investor, model as advisor, multi-agent deliberation, and compound pressure scenario. Across N = 6,500 trials, we find that bias manifestation in LLMs is highly context-dependent. In individual decision-making contexts (Studies 1-2, N = 4,000), LLMs demonstrate strong rational cost-benefit logic with minimal escalation of commitment. However, multi-agent deliberation reveals a striking hierarchy effect (Study 3, N = 500): while asymmetrical hierarchies show moderate escalation rates (46.2%), symmetrical peer-based decision-making produces near-universal escalation (99.2%). Similarly, when subjected to compound organizational and personal pressures (Study 4, N = 2,000), models exhibit high degrees of escalation of commitment (68.95% average allocation to failing divisions). These findings reveal that LLM bias manifestation depends critically on social and organizational context rather than being inherent, with significant implications for the deployment of multi-agent systems and unsupervised operations where such conditions may emerge naturally.

[Arxiv](https://arxiv.org/abs/2508.01545)