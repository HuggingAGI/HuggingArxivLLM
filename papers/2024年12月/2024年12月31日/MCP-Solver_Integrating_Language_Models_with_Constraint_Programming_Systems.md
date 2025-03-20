# MCP-Solver：结合语言模型与约束编程系统的解决方案

发布时间：2024年12月31日

`LLM应用` `约束编程`

> MCP-Solver: Integrating Language Models with Constraint Programming Systems

# 摘要

> 摘要：
尽管大型语言模型（LLMs）在自然语言任务中表现出色，但它们在精确形式推理和严格问题规范方面常常面临挑战。我们展示了MCP-Solver，这是模型上下文协议的一个原型实现，证明了LLMs与约束编程系统之间系统集成的潜力。我们的实现提供了创建、编辑和验证约束模型的接口。通过一种基于项目的编辑方法，结合集成验证，系统在每一步修改中确保模型一致性，并支持结构化迭代细化。系统处理并发求解会话，并维护一个持久的建模见解知识库。初步实验表明，这种集成可以有效地结合LLMs的自然语言理解和约束求解能力。我们的开源实现证明了通过标准化协议将形式推理系统与LLMs集成的概念。虽然还需要进一步研究来建立全面的形式保证，但这项工作是自然语言处理与基于约束的推理相结合的第一步。

> 
Abstract:While Large Language Models (LLMs) perform exceptionally well at natural language tasks, they often struggle with precise formal reasoning and the rigorous specification of problems. We present MCP-Solver, a prototype implementation of the Model Context Protocol that demonstrates the potential for systematic integration between LLMs and constraint programming systems. Our implementation provides interfaces for the creation, editing, and validation of a constraint model. Through an item-based editing approach with integrated validation, the system ensures model consistency at every modification step and enables structured iterative refinement. The system handles concurrent solving sessions and maintains a persistent knowledge base of modeling insights. Initial experiments suggest that this integration can effectively combine LLMs' natural language understanding with constraint-solving capabilities. Our open-source implementation is proof of concept for integrating formal reasoning systems with LLMs through standardized protocols. While further research is needed to establish comprehensive formal guarantees, this work takes a first step toward principled integration of natural language processing with constraint-based reasoning.
    

[Arxiv](https://arxiv.org/pdf/2501.00539)