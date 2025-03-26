# # 摘要
基于逻辑的动作验证，守护移动 GUI 代理的安全

发布时间：2025年03月24日

`Agent` `移动计算` `GUI代理`

> Safeguarding Mobile GUI Agent via Logic-based Action Verification

# 摘要

> 大型基础模型（LFMs）为人类与计算机交互带来了革新，尤其是在移动图形用户界面（GUI）代理领域的突破，这些代理能够解析GUI。通过让用户以自然语言指令来自动化复杂移动任务，这些代理有望彻底改变移动计算。然而，LFMs的内在概率性，加上移动任务的模糊性和上下文依赖性，使得基于LFMs的自动化可靠性不足且易出错。为解决这一难题，我们推出了VeriSafe Agent（VSA）：首个为移动GUI代理提供形式化验证保障的系统。VSA通过将自然语言指令转化为领域特定语言（DSL）中的形式化规范，确保代理行为百分之百符合用户意图。这一创新方法实现了运行时验证，能够实时检测并阻止错误操作。实验结果表明，VSA在验证准确率上比现有方法提升了20.4%-25.6%，将GUI代理的任务完成率提高了90%-130%。

> Large Foundation Models (LFMs) have unlocked new possibilities in human-computer interaction, particularly with the rise of mobile Graphical User Interface (GUI) Agents capable of interpreting GUIs. These agents promise to revolutionize mobile computing by allowing users to automate complex mobile tasks through simple natural language instructions. However, the inherent probabilistic nature of LFMs, coupled with the ambiguity and context-dependence of mobile tasks, makes LFM-based automation unreliable and prone to errors. To address this critical challenge, we introduce VeriSafe Agent (VSA): a formal verification system that serves as a logically grounded safeguard for Mobile GUI Agents. VSA is designed to deterministically ensure that an agent's actions strictly align with user intent before conducting an action. At its core, VSA introduces a novel autoformalization technique that translates natural language user instructions into a formally verifiable specification, expressed in our domain-specific language (DSL). This enables runtime, rule-based verification, allowing VSA to detect and prevent erroneous actions executing an action, either by providing corrective feedback or halting unsafe behavior. To the best of our knowledge, VSA is the first attempt to bring the rigor of formal verification to GUI agent. effectively bridging the gap between LFM-driven automation and formal software verification. We implement VSA using off-the-shelf LLM services (GPT-4o) and evaluate its performance on 300 user instructions across 18 widely used mobile apps. The results demonstrate that VSA achieves 94.3%-98.33% accuracy in verifying agent actions, representing a significant 20.4%-25.6% improvement over existing LLM-based verification methods, and consequently increases the GUI agent's task completion rate by 90%-130%.

[Arxiv](https://arxiv.org/abs/2503.18492)