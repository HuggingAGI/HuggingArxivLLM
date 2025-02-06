# PICBench: 光子集成电路设计的LLMs基准测试

发布时间：2025年02月05日

`LLM应用

**理由**：这篇论文主要讨论了大型语言模型（LLMs）在光子集成电路（PICs）设计自动化中的应用，并提出了一个专门的基准评估框架PICBench。论文的重点在于如何利用LLMs来优化和自动化PIC设计，这属于LLM在实际工程问题中的应用，因此分类为“LLM应用”。` `集成电路` `自动化设计`

> PICBench: Benchmarking LLMs for Photonic Integrated Circuits Design

# 摘要

> 尽管大型语言模型（LLMs）在数字芯片设计自动化方面表现出色，但光子集成电路（PICs）这一前沿领域仍未被充分探索。PICs设计因代码量大且重复性高，耗时且易出错。本文推出PICBench，首个专为LLMs自动化PIC设计而生的基准评估框架，输出为网表形式。PICBench包含数十个精心设计的PIC问题，涵盖从基础器件到复杂电路的设计。通过开源仿真器，自动对比仿真结果与专家方案，评估生成设计的语法和功能。我们不仅评估了多种现有LLMs，还测试了不同提示工程技术以提升LLMs在PIC设计中的表现。研究揭示了LLMs在PIC设计中的挑战与潜力，为未来优化自动化提供了方向。PICBench及评估代码已开源，详见https://github.com/PICDA/PICBench。

> While large language models (LLMs) have shown remarkable potential in automating various tasks in digital chip design, the field of Photonic Integrated Circuits (PICs)-a promising solution to advanced chip designs-remains relatively unexplored in this context. The design of PICs is time-consuming and prone to errors due to the extensive and repetitive nature of code involved in photonic chip design. In this paper, we introduce PICBench, the first benchmarking and evaluation framework specifically designed to automate PIC design generation using LLMs, where the generated output takes the form of a netlist. Our benchmark consists of dozens of meticulously crafted PIC design problems, spanning from fundamental device designs to more complex circuit-level designs. It automatically evaluates both the syntax and functionality of generated PIC designs by comparing simulation outputs with expert-written solutions, leveraging an open-source simulator. We evaluate a range of existing LLMs, while also conducting comparative tests on various prompt engineering techniques to enhance LLM performance in automated PIC design. The results reveal the challenges and potential of LLMs in the PIC design domain, offering insights into the key areas that require further research and development to optimize automation in this field. Our benchmark and evaluation code is available at https://github.com/PICDA/PICBench.

[Arxiv](https://arxiv.org/abs/2502.03159)