# XGrammar：大型语言模型的灵活高效结构化生成引擎

发布时间：2024年11月22日

`LLM应用` `语言模型` `推理引擎`

> XGrammar: Flexible and Efficient Structured Generation Engine for Large Language Models

# 摘要

> LLM 智能体的应用愈发复杂多样，对能解析为代码、结构化函数调用及具身智能体命令的结构化输出需求甚高。这些情况使得 LLM 推理中的结构化生成需求大增。上下文无关语法是通过约束解码实现结构化生成的灵活手段。但执行上下文无关语法时，运行期间需遍历词汇表中所有标记的多个栈状态，给结构化生成带来了不容忽视的开销。本文中，我们提出 XGrammar，这是大型语言模型的一款灵活高效的结构生成引擎。XGrammar 把词汇表分为可预先检查的上下文无关标记和运行时需解释的上下文相关标记，以此加速上下文无关语法的执行。我们还进一步构建转换来拓展语法上下文，减少上下文无关标记的数量。另外，我们构建了高效的持久栈来加快上下文相关标记的检查。最后，我们将语法引擎与 LLM 推理引擎协同设计，让语法计算与 GPU 执行相重叠。评估结果显示，XGrammar 比现有方案快达 100 倍。与 LLM 推理引擎结合，能在端到端的低 LLM 服务中实现近乎零开销的结构生成。

> The applications of LLM Agents are becoming increasingly complex and diverse, leading to a high demand for structured outputs that can be parsed into code, structured function calls, and embodied agent commands. These developments bring significant demands for structured generation in LLM inference. Context-free grammar is a flexible approach to enable structured generation via constrained decoding. However, executing context-free grammar requires going through several stack states over all tokens in vocabulary during runtime, bringing non-negligible overhead for structured generation. In this paper, we propose XGrammar, a flexible and efficient structure generation engine for large language models. XGrammar accelerates context-free grammar execution by dividing the vocabulary into context-independent tokens that can be prechecked and context-dependent tokens that need to be interpreted during runtime. We further build transformations to expand the grammar context and reduce the number of context-independent tokens. Additionally, we build an efficient persistent stack to accelerate the context-dependent token checks. Finally, we co-design the grammar engine with LLM inference engine to overlap grammar computation with GPU executions. Evaluation results show that XGrammar can achieve up to 100x speedup over existing solutions. Combined with an LLM inference engine, it can generate near-zero overhead structure generation in end-to-end low-LLM serving.

[Arxiv](https://arxiv.org/abs/2411.15100)