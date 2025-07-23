# 深度研究员：测试时扩散方法的研究

发布时间：2025年07月21日

`Agent` `学术出版`

> Deep Researcher with Test-Time Diffusion

# 摘要

> 大型语言模型（LLMs）驱动的深度研究代理正在迅速发展，但在生成复杂长篇研究报告时，现有方法的表现往往趋于平稳。我们从人类研究的迭代本质中汲取灵感，提出了一种名为测试时扩散深度研究者（TTD-DR）的创新框架。该框架将研究报告生成视为一种扩散过程：从一个可更新的初步草稿开始，作为不断发展的基础来指导研究方向；随后通过一个“去噪”过程迭代优化，这一过程由动态检索机制驱动，在每一步中整合外部信息。此外，我们对智能体工作流的每个组件应用了自我进化算法，进一步增强了核心过程，确保生成高质量上下文。这种以草稿为中心的设计使报告编写过程更加及时和连贯，同时减少了信息丢失。实验结果表明，TTD-DR 在需要大量搜索和多跳推理的基准测试中显著超越了现有方法，展现了卓越的性能。

> Deep research agents, powered by Large Language Models (LLMs), are rapidly advancing; yet, their performance often plateaus when generating complex, long-form research reports using generic test-time scaling algorithms. Drawing inspiration from the iterative nature of human research, which involves cycles of searching, reasoning, and revision, we propose the Test-Time Diffusion Deep Researcher (TTD-DR). This novel framework conceptualizes research report generation as a diffusion process. TTD-DR initiates this process with a preliminary draft, an updatable skeleton that serves as an evolving foundation to guide the research direction. The draft is then iteratively refined through a "denoising" process, which is dynamically informed by a retrieval mechanism that incorporates external information at each step. The core process is further enhanced by a self-evolutionary algorithm applied to each component of the agentic workflow, ensuring the generation of high-quality context for the diffusion process. This draft-centric design makes the report writing process more timely and coherent while reducing information loss during the iterative search process. We demonstrate that our TTD-DR achieves state-of-the-art results on a wide array of benchmarks that require intensive search and multi-hop reasoning, significantly outperforming existing deep research agents.

[Arxiv](https://arxiv.org/abs/2507.16075)