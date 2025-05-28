# RefTool：参考引导工具创建，增强模型推理能力

发布时间：2025年05月27日

`LLM应用` `科学教育` `教育技术`

> RefTool: Enhancing Model Reasoning with Reference-Guided Tool Creation

# 摘要

> # 工具增强大型语言模型的推理能力
工具能够提升大型语言模型（LLMs）在复杂问题解决任务中的推理能力，但并非所有任务都具备可用的工具。在没有预定义工具的情况下，以往的研究尝试指导LLMs自动生成工具。然而，这类方法严重依赖模型内部的知识储备，一旦超出LLMs的知识范围，就会失效。为了解决这一局限性，我们提出了RefTool，这是一个基于参考的自动工具创建框架，利用结构化的外部材料，如教科书。RefTool包含两个模块：(1) 工具创建，LLMs从参考内容中生成可执行工具，通过示例进行验证，并将它们以层级结构组织到工具箱中；(2) 工具利用，LLMs通过导航工具箱结构，选择并应用合适的工具来解决问题。在因果关系、物理和化学基准测试上的实验表明，RefTool在平均准确率上比现有的工具创建和领域特定推理方法高出11.3%，同时具有成本效益和广泛的适用性。分析表明，基于参考创建工具能够生成准确且可靠的工具，层级结构则有助于有效选择工具。RefTool使LLMs能够克服知识限制，证明了基于外部参考创建工具的价值，从而实现增强和通用化的推理能力。

> Tools enhance the reasoning capabilities of large language models (LLMs) in complex problem-solving tasks, but not all tasks have available tools. In the absence of predefined tools, prior works have explored instructing LLMs to generate tools on their own. However, such approaches rely heavily on the models' internal knowledge and would fail in domains beyond the LLMs' knowledge scope. To address this limitation, we propose RefTool, a reference-guided framework for automatic tool creation that leverages structured external materials such as textbooks. RefTool consists of two modules: (1) tool creation, where LLMs generate executable tools from reference content, validate them using illustrative examples, and organize them hierarchically into a toolbox; and (2) tool utilization, where LLMs navigate the toolbox structure to select and apply the appropriate tools to solve problems. Experiments on causality, physics, and chemistry benchmarks demonstrate that RefTool outperforms existing tool-creation and domain-specific reasoning methods by 11.3% on average accuracy, while being cost-efficient and broadly generalizable. Analyses reveal that grounding tool creation in references produces accurate and faithful tools, and that the hierarchical structure facilitates effective tool selection. RefTool enables LLMs to overcome knowledge limitations, demonstrating the value of grounding tool creation in external references for enhanced and generalizable reasoning.

[Arxiv](https://arxiv.org/abs/2505.21413)