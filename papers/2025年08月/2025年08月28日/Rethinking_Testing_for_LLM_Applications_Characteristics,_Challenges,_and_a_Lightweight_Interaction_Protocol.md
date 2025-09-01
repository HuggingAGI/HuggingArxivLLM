# # LLM应用测试的再思考：特性、挑战与轻量级交互协议

发布时间：2025年08月28日

`LLM应用` `基础理论`

> Rethinking Testing for LLM Applications: Characteristics, Challenges, and a Lightweight Interaction Protocol

# 摘要

> 大型语言模型（LLMs）的应用已从简单的文本生成工具演变为集成检索增强、工具调用和多轮交互的复杂软件系统。其固有的非确定性、动态性和上下文依赖性给质量保证带来了根本性挑战。本文将LLM应用拆解为三层架构：	extbf{	extit{系统外壳层}}、	extbf{	extit{提示编排层}}和	extbf{	extit{LLM推理核心}}。随后，我们评估了传统软件测试方法在各层的适用性：外壳层可直接应用，编排层需进行语义重新解读，而推理核心则需要范式转变。通过比较分析软件工程领域的AI测试方法与AI领域的安全分析技术，我们发现测试单元抽象、评估指标及生命周期管理存在结构性脱节。我们明确了构成六大核心挑战的四个根本差异。为应对这些挑战，我们提出四种协作策略（\emph{保留}、\emph{转换}、\emph{集成}和\emph{运行时}），并探索一种结合部署前验证与运行时监控的闭环、可信质量保证框架。基于这些策略，我们提供实用指导与协议提案，助力LLM应用测试的标准化和工具化发展。我们提出	extbf{	extit{智能体交互通信语言}}（AICL）协议，用于AI智能体间的通信。AICL具备面向测试的特性，可轻松集成到现有的智能体框架中。

> Applications of Large Language Models~(LLMs) have evolved from simple text generators into complex software systems that integrate retrieval augmentation, tool invocation, and multi-turn interactions. Their inherent non-determinism, dynamism, and context dependence pose fundamental challenges for quality assurance. This paper decomposes LLM applications into a three-layer architecture: \textbf{\textit{System Shell Layer}}, \textbf{\textit{Prompt Orchestration Layer}}, and \textbf{\textit{LLM Inference Core}}. We then assess the applicability of traditional software testing methods in each layer: directly applicable at the shell layer, requiring semantic reinterpretation at the orchestration layer, and necessitating paradigm shifts at the inference core. A comparative analysis of Testing AI methods from the software engineering community and safety analysis techniques from the AI community reveals structural disconnects in testing unit abstraction, evaluation metrics, and lifecycle management. We identify four fundamental differences that underlie 6 core challenges. To address these, we propose four types of collaborative strategies (\emph{Retain}, \emph{Translate}, \emph{Integrate}, and \emph{Runtime}) and explore a closed-loop, trustworthy quality assurance framework that combines pre-deployment validation with runtime monitoring. Based on these strategies, we offer practical guidance and a protocol proposal to support the standardization and tooling of LLM application testing. We propose a protocol \textbf{\textit{Agent Interaction Communication Language}} (AICL) that is used to communicate between AI agents. AICL has the test-oriented features and is easily integrated in the current agent framework.

[Arxiv](https://arxiv.org/abs/2508.20737)