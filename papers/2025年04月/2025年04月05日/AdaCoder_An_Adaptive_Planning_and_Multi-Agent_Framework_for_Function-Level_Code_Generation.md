# AdaCoder: 自适应规划与多智能体框架，专为函数级代码生成而设计

发布时间：2025年04月05日

`LLM应用` `软件开发` `人工智能`

> AdaCoder: An Adaptive Planning and Multi-Agent Framework for Function-Level Code Generation

# 摘要

> 最近，研究人员提出了许多用于函数级代码生成的多智能体框架，旨在通过根据任务描述自动生成函数级源代码来提高软件开发的生产力。一个典型的多智能体框架由负责任务规划、代码生成、测试、调试等的基于大型语言模型（LLM）的智能体组成。研究表明，现有的多智能体代码生成框架在 ChatGPT 上表现良好。然而，它们在其他基础 LLM 上的通用性尚未得到系统性探索。本文报告了一项关于四个最先进多智能体代码生成框架在六种参数规模、架构和性能水平各异的开源 LLM 上的通用性实证研究。我们的研究揭示了现有框架在多样化基础 LLM 上的不稳定通用性。基于实证研究的发现，我们提出了 AdaCoder，一种新颖的自适应规划多智能体框架，用于函数级代码生成。AdaCoder 包含两个阶段。第一阶段是在无规划的情况下进行初始代码生成，利用基于 LLM 的编码智能体和基于脚本的测试智能体，释放 LLM 的原生能力，识别超出 LLM 能力范围的案例，并确定阻碍执行的错误。第二阶段引入基于规则的调试智能体和基于 LLM 的规划智能体，通过有规划的迭代代码生成来优化结果。我们的评估表明，AdaCoder 在多样化 LLM 上实现了更高的通用性。与最佳基线 MapCoder 相比，AdaCoder 的 Pass@1 平均高出 27.69%，推理速度提升 16 倍，令牌消耗减少 12 倍。

> Recently, researchers have proposed many multi-agent frameworks for function-level code generation, which aim to improve software development productivity by automatically generating function-level source code based on task descriptions. A typical multi-agent framework consists of Large Language Model (LLM)-based agents that are responsible for task planning, code generation, testing, debugging, etc. Studies have shown that existing multi-agent code generation frameworks perform well on ChatGPT. However, their generalizability across other foundation LLMs remains unexplored systematically. In this paper, we report an empirical study on the generalizability of four state-of-the-art multi-agent code generation frameworks across six open-source LLMs with varying parameter sizes, architectures, and performance levels. Our study reveals the unstable generalizability of existing frameworks on diverse foundation LLMs. Based on the findings obtained from the empirical study, we propose AdaCoder, a novel adaptive planning, multi-agent framework for function-level code generation. AdaCoder has two phases. Phase-1 is an initial code generation step without planning, which uses an LLM-based coding agent and a script-based testing agent to unleash LLM's native power, identify cases beyond LLM's power, and determine the errors hindering execution. Phase-2 adds a rule-based debugging agent and an LLM-based planning agent for iterative code generation with planning. Our evaluation shows that AdaCoder achieves higher generalizability on diverse LLMs. Compared to the best baseline MapCoder, AdaCoder is on average 27.69% higher in Pass@1, 16 times faster in inference, and 12 times lower in token consumption.

[Arxiv](https://arxiv.org/abs/2504.04220)