# 代码图模型 (CGM)：一款专为仓库级别软件工程任务设计的图增强大型语言模型

发布时间：2025年05月22日

`LLM应用` `软件工程`

> Code Graph Model (CGM): A Graph-Integrated Large Language Model for Repository-Level Software Engineering Tasks

# 摘要

> 大型语言模型 (LLMs) 在函数级代码生成方面展现出潜力，但仓库级软件工程任务仍具挑战性。当前解决方案主要依赖专有 LLM 代理，这不仅引入了不可预测性，还限制了访问性，引发数据隐私和模型定制化的担忧。本文探讨开源 LLM 是否能有效处理仓库级任务，无需依赖基于代理的方法。我们通过使 LLM 理解代码库中函数和文件的语义信息和结构依赖关系，证明了这一可能性。为此，我们引入代码图模型 (CGMs)，将仓库代码图结构融入 LLM 的注意力机制，并通过专用适配器将节点属性映射到 LLM 的输入空间。结合无代理的图 RAG 框架，我们的方法在 SWE-bench Lite 基准测试中使用开源的 Qwen2.5-72B 模型实现了 43.00% 的解决率。这一性能在开源权重模型中排名第一，在开源系统方法中排名第二，总体排名第八，超过了之前最佳的开源模型方法 12.33%。

> Recent advances in Large Language Models (LLMs) have shown promise in function-level code generation, yet repository-level software engineering tasks remain challenging. Current solutions predominantly rely on proprietary LLM agents, which introduce unpredictability and limit accessibility, raising concerns about data privacy and model customization. This paper investigates whether open-source LLMs can effectively address repository-level tasks without requiring agent-based approaches. We demonstrate this is possible by enabling LLMs to comprehend functions and files within codebases through their semantic information and structural dependencies. To this end, we introduce Code Graph Models (CGMs), which integrate repository code graph structures into the LLM's attention mechanism and map node attributes to the LLM's input space using a specialized adapter. When combined with an agentless graph RAG framework, our approach achieves a 43.00% resolution rate on the SWE-bench Lite benchmark using the open-source Qwen2.5-72B model. This performance ranks first among open weight models, second among methods with open-source systems, and eighth overall, surpassing the previous best open-source model-based method by 12.33%.

[Arxiv](https://arxiv.org/abs/2505.16901)