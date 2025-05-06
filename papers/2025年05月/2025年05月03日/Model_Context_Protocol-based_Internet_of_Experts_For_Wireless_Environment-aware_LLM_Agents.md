# 专家网络：基于模型上下文协议的无线环境感知大语言模型智能体

发布时间：2025年05月03日

`LLM应用` `无线通信` `物联网`

> Model Context Protocol-based Internet of Experts For Wireless Environment-aware LLM Agents

# 摘要

> 大型语言模型（LLMs）具备强大的通用推理能力，但受限于缺乏原生传感器输入和领域特定的先验知识，无法获取无线环境信息。此前，将LLMs应用于无线系统的主要方法是依赖特定网络数据进行再训练，这会削弱语言的通用性，或是依赖手动编写的接口，这限制了可扩展性。为克服这些局限，我们提出了一种基于模型上下文协议（MCP）的专家物联网（IoX）框架，赋予LLMs无线环境感知推理能力。该框架整合了一组轻量级专家模型，每个模型专为解决无线通信中的特定确定性任务而设计，例如检测视距传播、多普勒效应或衰落条件等特定无线属性。通过MCP，LLM可在推理过程中选择性地查询和解读专家输出，而无需修改自身参数。这种架构实现了对无线环境的模块化、可扩展和可解释推理。在多种主流LLMs上的评估表明，与仅使用LLM的基准模型相比，所提出的无线环境感知LLM代理在分类任务上实现了40%-50%的性能提升。更广泛地说，基于MCP的设计为未来LLMs继承结构化的无线网络管理能力提供了一个可行的范式。

> Large Language Models (LLMs) exhibit strong general-purpose reasoning abilities but lack access to wireless environment information due to the absence of native sensory input and domain-specific priors. Previous attempts to apply LLMs in wireless systems either depend on retraining with network-specific data, which compromises language generalization, or rely on manually scripted interfaces, which hinder scalability. To overcome these limitations, we propose a Model Context Protocol (MCP)-based Internet of Experts (IoX) framework that equips LLMs with wireless environment-aware reasoning capabilities. The framework incorporates a set of lightweight expert models, each trained to solve a specific deterministic task in wireless communications, such as detecting a specific wireless attribute, e.g., line-of-sight propagation, Doppler effects, or fading conditions. Through MCP, the LLM can selectively query and interpret expert outputs at inference time, without modifying its own parameters. This architecture enables modular, extensible, and interpretable reasoning over wireless contexts. Evaluated across multiple mainstream LLMs, the proposed wireless environment-aware LLM agents achieve 40%-50% improvements in classification tasks over LLM-only baselines. More broadly, the MCP-based design offers a viable paradigm for future LLMs to inherit structured wireless network management capabilities.

[Arxiv](https://arxiv.org/abs/2505.01834)