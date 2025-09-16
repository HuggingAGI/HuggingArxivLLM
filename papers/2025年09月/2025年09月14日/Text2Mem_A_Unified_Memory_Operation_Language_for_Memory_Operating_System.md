# Text2Mem：面向内存操作系统的统一内存操作语言

发布时间：2025年09月14日

`Agent` `基础理论`

> Text2Mem: A Unified Memory Operation Language for Memory Operating System

# 摘要

> 大型语言模型智能体越来越依赖内存实现长程交互，现有框架却存在局限。多数框架仅提供编码、检索、删除等少数基础操作原语，而合并、提升优先级、降低优先级、拆分、锁定和过期等高阶操作则要么缺失，要么支持不一致。此外，内存命令缺乏正式且可执行的规范，使得范围和生命周期规则只能隐含表达，导致跨系统行为不可预测。为此，我们提出Text2Mem——一种统一的内存操作语言，为自然语言到可靠执行提供标准化路径。Text2Mem定义了一套简洁且富有表现力的操作集，涵盖编码、存储和检索核心环节。每条指令均表示为基于JSON的模式实例，包含必填字段和语义不变量，经解析器转换为带标准化参数的类型化操作对象。执行前由验证器确保指令正确性，适配器则负责将类型化对象映射至SQL原型后端或实际内存框架。需要时还会集成嵌入或摘要等模型服务，所有结果均通过统一执行契约返回。该设计确保了跨异构后端的安全性、确定性和可移植性。我们还规划了Text2Mem基准测试（Text2Mem Bench），它将模式生成与后端执行分离，支持系统性评估。这些组件共同构成了智能体内存控制的首个标准化基础。

> Large language model agents increasingly depend on memory to sustain long horizon interaction, but existing frameworks remain limited. Most expose only a few basic primitives such as encode, retrieve, and delete, while higher order operations like merge, promote, demote, split, lock, and expire are missing or inconsistently supported. Moreover, there is no formal and executable specification for memory commands, leaving scope and lifecycle rules implicit and causing unpredictable behavior across systems. We introduce Text2Mem, a unified memory operation language that provides a standardized pathway from natural language to reliable execution. Text2Mem defines a compact yet expressive operation set aligned with encoding, storage, and retrieval. Each instruction is represented as a JSON based schema instance with required fields and semantic invariants, which a parser transforms into typed operation objects with normalized parameters. A validator ensures correctness before execution, while adapters map typed objects either to a SQL prototype backend or to real memory frameworks. Model based services such as embeddings or summarization are integrated when required. All results are returned through a unified execution contract. This design ensures safety, determinism, and portability across heterogeneous backends. We also outline Text2Mem Bench, a planned benchmark that separates schema generation from backend execution to enable systematic evaluation. Together, these components establish the first standardized foundation for memory control in agents.

[Arxiv](https://arxiv.org/abs/2509.11145)