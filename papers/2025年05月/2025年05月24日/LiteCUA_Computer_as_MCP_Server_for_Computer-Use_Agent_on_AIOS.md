# LiteCUA：让计算机成为AIOS平台上的MCP服务，助力计算机使用代理高效运行

发布时间：2025年05月24日

`Agent

理由：这篇论文主要探讨了如何通过环境上下文化提升计算机使用代理（CUA）的能力，提出了一种新的平台AIOS 1.0和模型上下文协议（MCP）服务器架构，以解决语言模型与计算机界面之间的语义断层问题。研究结果表明，这种上下文化表示方法能够显著提升代理的推理和交互能力。因此，这篇论文的核心内容属于代理技术的应用和改进，应归类为Agent。` `计算机界面` `计算机代理`

> LiteCUA: Computer as MCP Server for Computer-Use Agent on AIOS

# 摘要

> 我们推出 AIOS 1.0，这是一个通过环境上下文化提升计算机使用代理 (CUA) 能力的开创性平台。当前研究多聚焦于增强代理框架或优化模型，但我们发现一个关键问题：语言模型对世界的理解与计算机界面之间存在语义断层。AIOS 1.0 通过将计算机转变为语言模型能理解的上下文环境，并引入模型上下文协议 (MCP) 服务器架构，成功解决了这一难题。这种方法将界面复杂性和决策复杂性分离，使代理能更高效地推理计算环境。为了验证平台效果，我们开发了 LiteCUA，这是一个基于 AIOS 1.0 的轻量级计算机使用代理，在 OSWorld 基准测试中取得了 14.66% 的成功率，远超其他专门代理框架的表现，尽管其架构相对简单。我们的研究结果表明，为语言模型构建计算机环境的上下文化表示，是开发更强大的计算机使用代理和推动 AI 与数字系统交互能力发展的有前景方向。LiteCUA 的源代码可在 https://github.com/agiresearch/LiteCUA 获取，并已集成到 AIOS 主分支中，作为 AIOS 的一部分，地址为 https://github.com/agiresearch/AIOS。


> We present AIOS 1.0, a novel platform designed to advance computer-use agent (CUA) capabilities through environmental contextualization. While existing approaches primarily focus on building more powerful agent frameworks or enhancing agent models, we identify a fundamental limitation: the semantic disconnect between how language models understand the world and how computer interfaces are structured. AIOS 1.0 addresses this challenge by transforming computers into contextual environments that language models can natively comprehend, implementing a Model Context Protocol (MCP) server architecture to abstract computer states and actions. This approach effectively decouples interface complexity from decision complexity, enabling agents to reason more effectively about computing environments. To demonstrate our platform's effectiveness, we introduce LiteCUA, a lightweight computer-use agent built on AIOS 1.0 that achieves a 14.66% success rate on the OSWorld benchmark, outperforming several specialized agent frameworks despite its simple architecture. Our results suggest that contextualizing computer environments for language models represents a promising direction for developing more capable computer-use agents and advancing toward AI that can interact with digital systems. The source code of LiteCUA is available at https://github.com/agiresearch/LiteCUA, and it is also integrated into the AIOS main branch as part of AIOS at https://github.com/agiresearch/AIOS.

[Arxiv](https://arxiv.org/abs/2505.18829)