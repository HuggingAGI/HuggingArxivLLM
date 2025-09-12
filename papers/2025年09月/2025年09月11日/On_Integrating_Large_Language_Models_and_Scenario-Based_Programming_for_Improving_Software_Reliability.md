# 融合大型语言模型与基于场景的编程以提升软件可靠性

发布时间：2025年09月11日

`LLM应用` `基础理论`

> On Integrating Large Language Models and Scenario-Based Programming for Improving Software Reliability

# 摘要

> 大型语言模型（LLMs）正迅速成为软件开发的得力助手，辅助甚至与开发者协作编写复杂程序。其优势显而易见——能大幅缩短开发时间、生成条理清晰的易懂代码，偶尔还能迸发开发者未曾想到的创新灵感。但不容忽视的是，LLMs 也常自信满满地输出错误代码，埋下严重隐患，可能误导开发者采纳有缺陷的方案。
  为让 LLMs 更可靠地赋能软件开发，我们提出一种结构化方法：将其与“传统”软件工程技术深度融合，旨在简化开发流程、减少错误，让用户能更安心地验证关键程序属性。我们特别聚焦基于场景的编程（SBP）范式——这种事件驱动的场景化软件工程方法，既能让开发者将专业知识“注入”LLM，又能有效审查和验证其输出。
  为检验该方法，我们开展了一项重要案例研究：设计并实现 Connect4 游戏。结果显示，LLMs 与 SBP 的结合催生了高性能智能体，足以击败多款现有强手；部分场景下，我们甚至能对智能体的正确性进行形式化验证。此外，实践还揭示了该方法在易用性上的有趣发现。本案例研究的完整代码将随论文终稿一同公开。

> Large Language Models (LLMs) are fast becoming indispensable tools for software developers, assisting or even partnering with them in crafting complex programs. The advantages are evident -- LLMs can significantly reduce development time, generate well-organized and comprehensible code, and occasionally suggest innovative ideas that developers might not conceive on their own. However, despite their strengths, LLMs will often introduce significant errors and present incorrect code with persuasive confidence, potentially misleading developers into accepting flawed solutions.
  In order to bring LLMs into the software development cycle in a more reliable manner, we propose a methodology for combining them with ``traditional'' software engineering techniques in a structured way, with the goal of streamlining the development process, reducing errors, and enabling users to verify crucial program properties with increased confidence. Specifically, we focus on the Scenario-Based Programming (SBP) paradigm -- an event-driven, scenario-based approach for software engineering -- to allow human developers to pour their expert knowledge into the LLM, as well as to inspect and verify its outputs.
  To evaluate our methodology, we conducted a significant case study, and used it to design and implement the Connect4 game. By combining LLMs and SBP we were able to create a highly-capable agent, which could defeat various strong existing agents. Further, in some cases, we were able to formally verify the correctness of our agent. Finally, our experience reveals interesting insights regarding the ease-of-use of our proposed approach. The full code of our case-study will be made publicly available with the final version of this paper.

[Arxiv](https://arxiv.org/abs/2509.09194)