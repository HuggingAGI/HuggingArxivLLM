# LLM-attacker：基于大型语言模型的自动驾驶闭环对抗场景生成优化

发布时间：2025年01月27日

`Agent

理由：这篇论文描述了一个基于大型语言模型（LLMs）的闭环对抗性场景生成框架，称为LLM-attacker。该框架通过设计并协调多个LLM代理来识别最佳攻击者，并优化其轨迹以生成对抗性场景。这些场景根据自动驾驶系统（ADS）的表现进行迭代优化，形成一个反馈循环以改进ADS。由于论文的核心是使用多个LLM代理来完成任务，并且这些代理在系统中扮演了关键角色，因此将其分类为Agent是合适的。` `自动驾驶` `安全测试`

> LLM-attacker: Enhancing Closed-loop Adversarial Scenario Generation for Autonomous Driving with Large Language Models

# 摘要

> 确保和提高自动驾驶系统（ADS）的安全性对于高度自动化车辆的部署至关重要，尤其是在安全关键事件中。为了解决稀有性问题，开发了对抗性场景生成方法，通过操纵交通参与者的行为来引发安全关键事件。然而，现有方法仍面临两个挑战：一是对抗性参与者的识别直接影响生成效果，但现实场景的复杂性使得识别困难；二是生成的安全关键场景在持续提升ADS性能方面的潜力尚未充分挖掘。为此，我们提出了LLM-attacker：一个基于大型语言模型（LLMs）的闭环对抗性场景生成框架。具体来说，我们设计并协调多个LLM代理来识别最佳攻击者，并优化其轨迹以生成对抗性场景。这些场景根据ADS的表现进行迭代优化，形成一个反馈循环以改进ADS。实验结果表明，LLM-attacker能够生成比其他方法更危险的场景，且使用它训练的ADS碰撞率仅为正常场景训练的一半。这表明LLM-attacker能够有效测试和提升ADS的安全性和鲁棒性。视频演示请访问：https://drive.google.com/file/d/1Zv4V3iG7825oyiKbUwS2Y-rR0DQIE1ZA/view。

> Ensuring and improving the safety of autonomous driving systems (ADS) is crucial for the deployment of highly automated vehicles, especially in safety-critical events. To address the rarity issue, adversarial scenario generation methods are developed, in which behaviors of traffic participants are manipulated to induce safety-critical events. However, existing methods still face two limitations. First, identification of the adversarial participant directly impacts the effectiveness of the generation. However, the complexity of real-world scenarios, with numerous participants and diverse behaviors, makes identification challenging. Second, the potential of generated safety-critical scenarios to continuously improve ADS performance remains underexplored. To address these issues, we propose LLM-attacker: a closed-loop adversarial scenario generation framework leveraging large language models (LLMs). Specifically, multiple LLM agents are designed and coordinated to identify optimal attackers. Then, the trajectories of the attackers are optimized to generate adversarial scenarios. These scenarios are iteratively refined based on the performance of ADS, forming a feedback loop to improve ADS. Experimental results show that LLM-attacker can create more dangerous scenarios than other methods, and the ADS trained with it achieves a collision rate half that of training with normal scenarios. This indicates the ability of LLM-attacker to test and enhance the safety and robustness of ADS. Video demonstrations are provided at: https://drive.google.com/file/d/1Zv4V3iG7825oyiKbUwS2Y-rR0DQIE1ZA/view.

[Arxiv](https://arxiv.org/abs/2501.15850)