# # SimuGen：多模态智能体框架，助力打造基于块图的仿真模型

发布时间：2025年05月27日

`Agent`

> SimuGen: Multi-modal Agentic Framework for Constructing Block Diagram-Based Simulation Models

# 摘要

> 大型语言模型（LLMs）在数学推理和代码生成领域取得了令人瞩目的成就。然而，在仿真领域，尤其是生成Simulink模型方面，LLMs仍面临挑战。Simulink模型作为工程和科学研究中的重要工具，其生成质量直接影响着研究的效率和结果。我们的初步实验发现，现有LLM代理在处理纯文本输入时，往往难以生成可靠且完整的Simulink仿真代码，这可能源于其预训练数据中缺乏Simulink特定的数据支持。为应对这一挑战，我们开发了SimuGen，一个创新的多模态代理框架。SimuGen通过整合视觉化的Simulink图和专业知识，能够自动产出准确的Simulink仿真代码。该框架由多个协同工作的专门代理组成，包括调查员、单元测试审查员、代码生成器、执行器、调试定位器和报告编写器，所有代理均依托于专业的领域知识库。这种协作式和模块化的架构设计，不仅提升了Simulink仿真生成的可解释性和可靠性，还确保了生成过程的可重复性。我们的开源代码现已在GitHub上公开，欢迎访问：https://github.com/renxinxing123/SimuGen_beta，了解更多细节。

> Recent advances in large language models (LLMs) have shown impressive performance in mathematical reasoning and code generation. However, LLMs still struggle in the simulation domain, particularly in generating Simulink models, which are essential tools in engineering and scientific research. Our preliminary experiments indicate that LLM agents often fail to produce reliable and complete Simulink simulation code from text-only inputs, likely due to the lack of Simulink-specific data in their pretraining. To address this challenge, we propose SimuGen, a multimodal agent-based framework that automatically generates accurate Simulink simulation code by leveraging both the visual Simulink diagram and domain knowledge. SimuGen coordinates several specialized agents, including an investigator, unit test reviewer, code generator, executor, debug locator, and report writer, supported by a domain-specific knowledge base. This collaborative and modular design enables interpretable, robust, and reproducible Simulink simulation generation. Our source code is publicly available at https://github.com/renxinxing123/SimuGen_beta.

[Arxiv](https://arxiv.org/abs/2506.15695)