# LLM智能体的可靠弱至强监控

发布时间：2025年08月26日

`Agent` `基础理论`

> Reliable Weak-to-Strong Monitoring of LLM Agents

# 摘要

> 我们对用于检测自主LLM智能体隐蔽不当行为（如秘密泄露隐私信息）的监控系统开展压力测试。为此，我们构建了一套系统化的监控红队（MRT）工作流程，其中包括：（1）智能体与监控器的情境感知水平梯度变化；（2）多样的监控规避对抗策略（如提示注入）；（3）两类数据集与环境——工具调用智能体适用的SHADE-Arena，以及新构建的CUA-SHADE-Arena（扩展自TheAgentCompany平台，适用于计算机使用智能体）。我们在现有LLM监控框架（用于编排LLM并解析智能体轨迹）和本研究提出的新型混合层次序列框架上均执行了MRT。实证结果揭示三个关键发现：其一，智能体感知主导监控器感知——当智能体知晓自身被监控时，监控器的可靠性大幅下降；相比之下，为监控器提供更多智能体相关信息的帮助远不及预期。其二，监控框架的重要性超过监控感知能力——混合框架的性能始终优于基准监控框架，甚至能让较弱的模型实现对较强智能体的可靠监控，呈现出“弱监控强智能体”的缩放效应。其三，在人机协作场景下（人类与LLM监控器共同讨论并更新对智能体行为的判断），针对性的人工监督效果最佳；仅将预先标记的可疑案例提交人工审核，在假阳性率（FPR）=0.01时，真阳性率（TPR）提升了约15%。本研究构建了MRT的标准化工作流程，揭示了LLM与人类在监控检测智能体不当行为时对抗鲁棒性的薄弱环节，并发布代码、数据及日志以推动后续研究。

> We stress test monitoring systems for detecting covert misbehavior in autonomous LLM agents (e.g., secretly sharing private information). To this end, we systematize a monitor red teaming (MRT) workflow that incorporates: (1) varying levels of agent and monitor situational awareness; (2) distinct adversarial strategies to evade the monitor, such as prompt injection; and (3) two datasets and environments -- SHADE-Arena for tool-calling agents and our new CUA-SHADE-Arena, which extends TheAgentCompany, for computer-use agents. We run MRT on existing LLM monitor scaffoldings, which orchestrate LLMs and parse agent trajectories, alongside a new hybrid hierarchical-sequential scaffolding proposed in this work. Our empirical results yield three key findings. First, agent awareness dominates monitor awareness: an agent's knowledge that it is being monitored substantially degrades the monitor's reliability. On the contrary, providing the monitor with more information about the agent is less helpful than expected. Second, monitor scaffolding matters more than monitor awareness: the hybrid scaffolding consistently outperforms baseline monitor scaffolding, and can enable weaker models to reliably monitor stronger agents -- a weak-to-strong scaling effect. Third, in a human-in-the-loop setting where humans discuss with the LLM monitor to get an updated judgment for the agent's behavior, targeted human oversight is most effective; escalating only pre-flagged cases to human reviewers improved the TPR by approximately 15% at FPR = 0.01. Our work establishes a standard workflow for MRT, highlighting the lack of adversarial robustness for LLMs and humans when monitoring and detecting agent misbehavior. We release code, data, and logs to spur further research.

[Arxiv](https://arxiv.org/abs/2508.19461)