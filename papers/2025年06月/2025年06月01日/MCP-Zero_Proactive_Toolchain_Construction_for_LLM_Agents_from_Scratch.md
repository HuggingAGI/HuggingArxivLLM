# MCP-Zero：从零开始主动构建LLM代理工具链

发布时间：2025年06月01日

`Agent` `工具链` `框架设计`

> MCP-Zero: Proactive Toolchain Construction for LLM Agents from Scratch

# 摘要

> 功能调用使大型语言模型（LLMs）能够作为使用工具的代理，但将数千个工具模式注入提示中成本高昂且容易出错。我们引入了MCP-Zero，这是一个主动代理框架，允许LLM自行决定何时以及检索哪些外部工具，从而从头开始构建特定任务的工具链。该框架基于三个核心组件：(1) 主动工具请求，其中模型会发出一个结构化的 $\left<\operatorname{tool\_assistant}ight>$ 块，明确指定所需的服务器和任务；(2) 层级向量路由，这是一种从粗到细的检索算法，首先选择候选服务器，然后根据语义相似性在每个服务器内对工具进行排序；(3) 迭代主动调用，支持多轮、跨域工具链构建，上下文开销极小，并允许模型在返回的工具不足时逐步修订其请求。我们整理了MCP-tools数据集，包含从官方Model-Context-Protocol存储库中提取的308个MCP服务器和2,797个工具，并将其统一规范化为JSON模式。实验结果表明，MCP-Zero在解决现有方法的上下文开销问题方面表现出色，能从近3,000个候选工具（248.1k个令牌）中准确选择正确的工具；在APIbank上将令牌消耗减少98%的同时保持高准确性；并且支持多轮工具调用，在各轮次中保持一致的准确性。代码和数据集即将发布。

> Function-calling has enabled large language models (LLMs) to act as tool-using agents, but injecting thousands of tool schemas into the prompt is costly and error-prone. We introduce MCP-Zero, a proactive agent framework that lets the LLM itself decide when and which external tools to retrieve, thereby assembling a task-specific toolchain from scratch. The framework is built upon three components: (1) Proactive Tool Request, where the model emits a structured $\left<\operatorname{tool\_assistant}\right>$ block that explicitly specifies the desired server and task; (2) Hierarchical Vector Routing, a coarse-to-fine retrieval algorithm that first selects candidate servers and then ranks tools within each server based on the semantic similarity; (3) Iterative Proactive Invocation, enabling multi-round, cross-domain toolchain construction with minimal context overhead, and allowing the model to iteratively revise its request when the returned tools are insufficient. To evaluate our approach we also compile MCP-tools, a retrieval dataset comprising 308 MCP servers and 2,797 tools extracted from the official Model-Context-Protocol repository and normalized into a unified JSON schema. Experiments show that MCP-Zero (i) effectively addresses the context overhead problem of existing methods and accurately selects the correct tool from a pool of nearly 3,000 candidates (248.1k tokens); (ii) reduces token consumption by 98\% on the APIbank while maintaining high accuracy; and (iii) supports multi-turn tool invocation with consistent accuracy across rounds. The code and dataset will be released soon.

[Arxiv](https://arxiv.org/abs/2506.01056)