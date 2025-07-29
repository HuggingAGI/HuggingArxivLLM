# MemoCoder：基于 LLM 的智能体实现函数合成自动化

发布时间：2025年07月24日

`Agent` `代码生成`

> MemoCoder: Automated Function Synthesis using LLM-Supported Agents

# 摘要

> 随着 GitHub Copilot 和 ChatGPT 等大型语言模型 (LLMs) 的广泛应用，开发者越来越依赖 AI 辅助工具来支持代码生成。尽管 LLMs 能够为结构良好的编程任务生成语法正确的解决方案，但在需要迭代调试、错误处理或适应多样化问题结构的场景下，它们往往表现不佳。现有的方法，如微调或自修复策略，要么需要高昂的重新训练成本，要么缺乏积累和重用先前尝试知识的机制。

为了解决这些问题，我们提出了 MemoCoder，一个多智能体框架，支持协作解决问题和从过去修复中进行持续学习。MemoCoder 的核心是一个修复知识集，用于存储成功的修复并支持未来任务的检索。一个中央导师智能体通过识别重复的错误模式并优化高级修复策略来监督修复过程，提供了一种新颖的监督角色，指导自修复循环。我们在三个公共基准测试——MBPP、HumanEval 和 LiveCodeBench——上评估了 MemoCoder，涵盖了各种问题复杂度。实验结果表明，MemoCoder 在 Pass@10 和 Pass@50 方面始终优于零样本提示和自修复策略，改进幅度分别为 3.1% 到 12.1% 和 1.4% 到 14.5%，展示了其在迭代细化和知识引导的代码生成方面的有效性。

> With the widespread adoption of Large Language Models (LLMs) such as GitHub Copilot and ChatGPT, developers increasingly rely on AI-assisted tools to support code generation. While LLMs can generate syntactically correct solutions for well-structured programming tasks, they often struggle with challenges that require iterative debugging, error handling, or adaptation to diverse problem structures. Existing approaches such as fine-tuning or self-repair strategies either require costly retraining or lack mechanisms to accumulate and reuse knowledge from previous attempts.
  To address these limitations, we propose MemoCoder, a multi-agent framework that enables collaborative problem solving and persistent learning from past fixes. At the core of MemoCoder is a Fixing Knowledge Set, which stores successful repairs and supports retrieval for future tasks. A central Mentor Agent supervises the repair process by identifying recurring error patterns and refining high-level fixing strategies, providing a novel supervisory role that guides the self-repair loop. We evaluate MemoCoder across three public benchmarks -- MBPP, HumanEval, and LiveCodeBench -- spanning a range of problem complexities. Experimental results show that MemoCoder consistently outperforms both zero-shot prompting and a Self-Repair strategy, with improvements ranging from 3.1% to 12.1% in Pass@10 and from 1.4% to 14.5% in Pass@50, demonstrating its effectiveness in iterative refinement and knowledge-guided code generation.

[Arxiv](https://arxiv.org/abs/2507.18812)