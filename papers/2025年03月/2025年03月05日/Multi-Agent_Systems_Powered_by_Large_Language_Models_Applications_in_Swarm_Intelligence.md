# 大型语言模型赋能的多智能体系统：群体智能中的应用探索

发布时间：2025年03月05日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在多智能体仿真环境中的应用，特别是通过提示机制来驱动智能体的行为。虽然涉及多智能体，但核心是LLM的应用，因此归类为LLM应用。` `群智能` `多智能体系统`

> Multi-Agent Systems Powered by Large Language Models: Applications in Swarm Intelligence

# 摘要

> 本研究聚焦于大型语言模型（LLMs）与多智能体仿真环境的融合创新，通过LLM驱动的提示替代传统智能体的硬编码程序。我们选取了群智能领域的两大经典案例——蚁群觅食与鸟群飞行，生动展示了这一创新方法的实际应用。研究的核心是一个集成工具链，它成功实现了LLMs与NetLogo仿真平台的无缝对接，借助Python扩展模块，通过OpenAI API与GPT-4o建立高效通信。这一工具链支持基于提示的行为生成机制，赋予智能体根据环境数据做出动态响应的能力。针对上述两个案例，我们分别采用了结构化规则提示与自主知识驱动提示两种方案。研究结果表明，这一工具链不仅能够赋能LLMs深入研究自组织过程，更能有效诱发多智能体环境中的涌现行为，为探索智能系统及基于自然现象的群智能建模提供了全新视角。所有相关代码、仿真文件及数据均可在GitHub仓库（https://github.com/crjimene/swarm_gpt）中获取。

> This work examines the integration of large language models (LLMs) into multi-agent simulations by replacing the hard-coded programs of agents with LLM-driven prompts. The proposed approach is showcased in the context of two examples of complex systems from the field of swarm intelligence: ant colony foraging and bird flocking. Central to this study is a toolchain that integrates LLMs with the NetLogo simulation platform, leveraging its Python extension to enable communication with GPT-4o via the OpenAI API. This toolchain facilitates prompt-driven behavior generation, allowing agents to respond adaptively to environmental data. For both example applications mentioned above, we employ both structured, rule-based prompts and autonomous, knowledge-driven prompts. Our work demonstrates how this toolchain enables LLMs to study self-organizing processes and induce emergent behaviors within multi-agent environments, paving the way for new approaches to exploring intelligent systems and modeling swarm intelligence inspired by natural phenomena. We provide the code, including simulation files and data at https://github.com/crjimene/swarm_gpt.

[Arxiv](https://arxiv.org/abs/2503.03800)