# 模块化更优：模块化提示设计助力高效代码生成

发布时间：2025年03月16日

`LLM应用` `软件开发` `代码生成`

> Modularization is Better: Effective Code Generation with Modular Prompting

# 摘要

> 大型语言模型正在通过自动代码生成重塑软件开发领域。现有的提示技术如思维链（CoT）采用逐步提示任务并遵循线性推理结构，这在解决复杂编程问题（尤其是需要分层解决方案的问题）时存在局限性。受软件开发中模块化原则的启发，我们提出了一种名为MoT（Module-of-Thought）的新提示技术，旨在提升大型语言模型的代码生成能力。MoT通过模块化方法将复杂编程问题分解为更小、独立的推理步骤，构建出更结构化且易理解的问题解决过程。这种分层结构显著增强了模型对复杂编程问题的理解能力。此外，MoT通过多级推理图（MLR Graph）对推理过程进行结构化处理，以分层方式组织推理步骤。这种方法不仅提升了模块化理解能力，还确保了推理步骤与生成代码之间的高度对齐，从而显著提升了代码生成性能。我们在GPT-4o-mini和DeepSeek-R1等两个先进大型语言模型上进行了实验，将MoT与六种基线提示技术在HumanEval、HumanEval-ET、HumanEval+、MBPP、MBPP-ET和MBPP+等六个常用数据集上进行对比。实验结果显示，MoT显著优于现有基线（如CoT和SCoT），通过率（Pass@1）从58.1%提升至95.1%。实验结果充分证明，MoT显著提升了基于大型语言模型的代码生成性能。

> Large Language Models are transforming software development by automatically generating code. Current prompting techniques such as Chain-of-Thought (CoT) suggest tasks step by step and the reasoning process follows a linear structure, which hampers the understanding of complex programming problems, particularly those requiring hierarchical solutions. Inspired by the principle of modularization in software development, in this work, we propose a novel prompting technique, called MoT, to enhance the code generation performance of LLMs. At first, MoT exploits modularization principles to decompose complex programming problems into smaller, independent reasoning steps, enabling a more structured and interpretable problem-solving process. This hierarchical structure improves the LLM's ability to comprehend complex programming problems. Then, it structures the reasoning process using an MLR Graph (Multi-Level Reasoning Graph), which hierarchically organizes reasoning steps. This approach enhances modular understanding and ensures better alignment between reasoning steps and the generated code, significantly improving code generation performance. Our experiments on two advanced LLMs (GPT-4o-mini and DeepSeek-R1), comparing MoT to six baseline prompting techniques across six widely used datasets, HumanEval, HumanEval-ET, HumanEval+, MBPP, MBPP-ET, and MBPP+, demonstrate that MoT significantly outperforms existing baselines (e.g., CoT and SCoT), achieving Pass@1 scores ranging from 58.1% to 95.1%. The experimental results confirm that MoT significantly enhances the performance of LLM-based code generation.

[Arxiv](https://arxiv.org/abs/2503.12483)