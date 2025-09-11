# 组件化：将单体LLM响应分解为可操控的语义单元

发布时间：2025年09月09日

`Agent` `基础理论`

> Componentization: Decomposing Monolithic LLM Responses into Manipulable Semantic Units

# 摘要

> 大型语言模型（LLMs）生成的文本往往是整体块状的，难以局部编辑，这会拖慢协作流程。为此，我们提出了组件化方法——将模型输出分解为模块化、可独立编辑的单元，同时保留上下文关联。我们提出了模块化自适应输出分解（MAOD），它能将响应分割为连贯组件并维持组件间的关联；同时，我们将基于组件的响应架构（CBRA）作为实现这一理念的一种方案进行了概述。我们的参考原型MAODchat采用微服务架构，配备基于状态机的分解代理、跨供应商兼容的模型适配器，以及支持实时组件操作与重组的功能。
  在一项包含学术、工程和产品领域四名参与者的探索性研究中，我们发现组件级编辑与多种常见工作流相契合，能够实现迭代优化和选择性复用。参与者还提到了潜在的团队协作流程。我们的贡献包括：（1）组件化的定义——即将整体输出转化为可操作单元；（2）CBRA架构及原型系统MAODchat；（3）小型用户研究的初步发现；（4）MAOD作为语义分割的算法框架；（5）自动分解的智能体间通信协议示例。我们认为，组件化有望成为将被动文本阅读转变为更主动的组件级协作的重要方向。

> Large Language Models (LLMs) often produce monolithic text that is hard to edit in parts, which can slow down collaborative workflows. We present componentization, an approach that decomposes model outputs into modular, independently editable units while preserving context. We describe Modular and Adaptable Output Decomposition (MAOD), which segments responses into coherent components and maintains links among them, and we outline the Component-Based Response Architecture (CBRA) as one way to implement this idea. Our reference prototype, MAODchat, uses a microservices design with state-machine-based decomposition agents, vendor-agnostic model adapters, and real-time component manipulation with recomposition.
  In an exploratory study with four participants from academic, engineering, and product roles, we observed that component-level editing aligned with several common workflows and enabled iterative refinement and selective reuse. Participants also mentioned possible team workflows. Our contributions are: (1) a definition of componentization for transforming monolithic outputs into manipulable units, (2) CBRA and MAODchat as a prototype architecture, (3) preliminary observations from a small user study, (4) MAOD as an algorithmic sketch for semantic segmentation, and (5) example Agent-to-Agent protocols for automated decomposition. We view componentization as a promising direction for turning passive text consumption into more active, component-level collaboration.

[Arxiv](https://arxiv.org/abs/2509.08203)