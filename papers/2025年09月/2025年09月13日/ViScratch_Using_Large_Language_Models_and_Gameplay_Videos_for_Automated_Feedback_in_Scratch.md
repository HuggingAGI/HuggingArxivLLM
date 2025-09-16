# ViScratch：基于大型语言模型与游戏视频的Scratch自动化反馈

发布时间：2025年09月13日

`LLM应用` `教育科技`

> ViScratch: Using Large Language Models and Gameplay Videos for Automated Feedback in Scratch

# 摘要

> 像Scratch这样的积木式编程环境在编程教育中日益普及，尤其受到青少年学习者的青睐。尽管积木能有效避免语法错误，语义错误却依然频繁出现，且调试难度大。现有的Scratch调试工具大多依赖预定义规则或用户手动输入，而关键问题在于，它们完全忽略了平台本身的视觉属性。
  为此，我们提出ViScratch——首个面向Scratch的多模态反馈生成系统，它同时利用项目的积木代码和生成的游戏视频来诊断并修复错误。ViScratch采用两阶段处理流程：首先，视觉-语言模型将视觉异常与代码结构对齐，定位出单个关键问题；接着，系统生成最小化的抽象语法树级修复方案，并通过Scratch虚拟机执行来验证修复效果。
  我们在真实的Scratch项目集上对ViScratch进行了评估，并与最先进的基于LLM的工具及人类测试者展开对比。结果显示，游戏视频是调试的关键线索：ViScratch在错误识别和修复质量上大幅超越现有工具，即便在没有项目描述或目标的情况下依然表现出色。这项研究证明，视频可成为视觉编程环境中的"一等规范"，为基于LLM的调试技术开辟了超越纯符号代码的全新路径。

> Block-based programming environments such as Scratch are increasingly popular in programming education, in particular for young learners. While the use of blocks helps prevent syntax errors, semantic bugs remain common and difficult to debug. Existing tools for Scratch debugging rely heavily on predefined rules or user manual inputs, and crucially, they ignore the platform's inherently visual nature.
  We introduce ViScratch, the first multimodal feedback generation system for Scratch that leverages both the project's block code and its generated gameplay video to diagnose and repair bugs. ViScratch uses a two-stage pipeline: a vision-language model first aligns visual symptoms with code structure to identify a single critical issue, then proposes minimal, abstract syntax tree level repairs that are verified via execution in the Scratch virtual machine.
  We evaluate ViScratch on a set of real-world Scratch projects against state-of-the-art LLM-based tools and human testers. Results show that gameplay video is a crucial debugging signal: ViScratch substantially outperforms prior tools in both bug identification and repair quality, even without access to project descriptions or goals. This work demonstrates that video can serve as a first-class specification in visual programming environments, opening new directions for LLM-based debugging beyond symbolic code alone.

[Arxiv](https://arxiv.org/abs/2509.11065)