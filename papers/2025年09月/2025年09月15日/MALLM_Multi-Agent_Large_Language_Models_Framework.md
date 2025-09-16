# MALLM：多智能体大型语言模型框架

发布时间：2025年09月15日

`Agent` `基础理论`

> MALLM: Multi-Agent Large Language Models Framework

# 摘要

> 多智能体辩论（MAD）已展现出通过扩展测试时计算资源和发挥专业优势来增强集体智能的能力。当前的多智能体辩论框架往往侧重于工具使用，缺乏集成评估，或者在智能体角色、响应生成器、讨论范式和决策协议方面的可配置性有限。为此，我们推出了MALLM（多智能体大型语言模型）——一个开源框架，可对MAD组件进行系统分析。MALLM提供了144种以上独特的MAD配置组合，包括（1）智能体角色（如专家、个性型）、（2）响应生成器（如批判性、推理型）、（3）讨论范式（如记忆型、接力型）和（4）决策协议（如投票、共识机制）。该框架通过简单的配置文件即可定义辩论流程，此外还可加载任何文本类Huggingface数据集（如MMLU-Pro、WinoGrande），并提供评估流程以方便比较不同MAD配置。MALLM专为研究人员打造，为洞察多智能体辩论的核心机制提供了窗口，有助于深入理解其组件及相互作用。

> Multi-agent debate (MAD) has demonstrated the ability to augment collective intelligence by scaling test-time compute and leveraging expertise. Current frameworks for multi-agent debate are often designed towards tool use, lack integrated evaluation, or provide limited configurability of agent personas, response generators, discussion paradigms, and decision protocols. We introduce MALLM (Multi-Agent Large Language Models), an open-source framework that enables systematic analysis of MAD components. MALLM offers more than 144 unique configurations of MAD, including (1) agent personas (e.g., Expert, Personality), (2) response generators (e.g., Critical, Reasoning), (3) discussion paradigms (e.g., Memory, Relay), and (4) decision protocols (e.g., Voting, Consensus). MALLM uses simple configuration files to define a debate. Furthermore, MALLM can load any textual Huggingface dataset (e.g., MMLU-Pro, WinoGrande) and provides an evaluation pipeline for easy comparison of MAD configurations. MALLM is tailored towards researchers and provides a window into the heart of multi-agent debate, facilitating the understanding of its components and their interplay.

[Arxiv](https://arxiv.org/abs/2509.11656)