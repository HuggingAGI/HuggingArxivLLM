# 思考抽象：硬件设计中LLM推理的中间表达形式

发布时间：2025年05月21日

`LLM应用` `硬件设计`

> Abstraction-of-Thought: Intermediate Representations for LLM Reasoning in Hardware Design

# 摘要

> 大型语言模型（LLMs）在逻辑和编程任务中表现卓越，常可比肩专家水平。然而，从自然语言生成功能正确的硬件描述语言（HDL）代码依然充满挑战，尤其在数据稀缺领域。因此，我们提出思路抽象（AoT）——一个无需训练、仅用于推理的提示框架，通过在提示过程中的任务相关抽象，有效缓解LLMs在理解和推理中的误区，助力硬件从高层次到低层次表示的转换。AoT包含三个阶段：(1) 基于LLMs的硬件设计模式分类，(2) 结构化的中间表示（IR），分离功能分解与代码语法，(3) 逐行伪代码解决方案，实现与最终Verilog代码的直接映射。实验结果表明，AoT在大型非推理模型（如GPT-4o）中表现优异，超越所有基线技术（包括1-shot、链式推理和树状推理），且生成的tokens较树状推理方法减少1.8-5.2倍。

> Large language models (LLMs) have achieved impressive proficiency on logic and programming tasks, often rivaling expert-level performance. However, generating functionally correct hardware description language (HDL) code from natural language specifications remains challenging, primarily in data-scarce domains.
  Therefore, we present Abstraction-of-Thought (AoT) - a training-free, inference-only prompting framework to mitigate misinterpretations and reasoning pitfalls of LLMs through a series of task-based abstractions within the prompting procedure, assisting in the transition from high-level to low-level representations of hardware. Furthermore, AoT consists of the following stages: (1) an LLM-based classification of hardware design patterns, (2) a structured intermediate representation (IR) to separate functional decomposition from code syntax, and (3) a line-by-line pseudocode solution enabling a more direct mapping to the final Verilog implementation. Experimental results on the VerilogEval benchmark depict that AoT demonstrates improvements in functionality when applied to large non-reasoning models (such as GPT-4o), outperforming all baseline techniques (including 1-shot, Chain-of-Thought, and Tree-of-Thought) while significantly reducing the generated tokens by 1.8-5.2x compared to popular Tree-of-Thought prompting.

[Arxiv](https://arxiv.org/abs/2505.15873)