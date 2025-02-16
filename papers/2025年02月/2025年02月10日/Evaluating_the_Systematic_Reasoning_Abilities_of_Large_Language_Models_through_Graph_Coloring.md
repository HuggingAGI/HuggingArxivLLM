# 通过图着色深入评估大型语言模型的系统推理能力

发布时间：2025年02月10日

`LLM理论` `大型语言模型` `系统性推理`

> Evaluating the Systematic Reasoning Abilities of Large Language Models through Graph Coloring

# 摘要

> 当代大型语言模型虽然强大，但在推理能力上仍有待提升。我们通过图着色问题评估模型的系统性推理与可能性探索能力，并研究语义框架的影响。在$2 \leq k \leq 4$颜色数和$4 \leq n \leq 8$顶点数的$k$-着色问题上，测试了Claude 3.5 Sonnet、Llama 3.1 405B、Gemini 1.5 Pro、GPT-4o、o1-mini和DeepSeek-R1等模型，并通过部分算法求解器按难度分类问题。结果显示，除o1-mini和R1外，其他模型在困难问题上的错误率均超过60%（o1-mini为15%以上，R1为10%以上），甚至在简单的2色4顶点图问题中，所有模型都无法达到完美准确率。这表明大型语言模型在系统性推理方面虽有显著进步，但可靠性仍有限，尤其是随着计算成本的增加。未来，更复杂的图着色问题以及任意复杂度推理问题的程序化生成，将为模型基准测试提供新的研究方向。

> Contemporary large language models are powerful problem-solving tools, but they exhibit weaknesses in their reasoning abilities which ongoing research seeks to mitigate. We investigate graph coloring as a means of evaluating an LLM's capacities for systematic step-by-step reasoning and possibility space exploration, as well as effects of semantic problem framing. We test Claude 3.5 Sonnet, Llama 3.1 405B, Gemini 1.5 Pro, GPT-4o, o1-mini, and DeepSeek-R1 on a dataset of $k$-coloring problems with $2 \leq k \leq 4$ and vertex count $4 \leq n \leq 8$, using partial algorithmic solvers to further categorize problems by difficulty. In addition to substantial but varying framing effects, we find that all models except o1-mini and R1 exhibit $>60\%$ error rates on difficult problem types in all frames ($>15\%$ for o1-mini and $>10\%$ for R1), and no model achieves perfect accuracy even in the simple domain of 2-coloring 4-vertex graphs. Our results highlight both the considerable recent progress in LLM systematic reasoning and the limits of its reliability, especially in relation to increasing computational costs. We expect that more complex graph coloring problems, and procedural generation of arbitrary-complexity reasoning problems more broadly, offer further untapped potential for LLM benchmarking.

[Arxiv](https://arxiv.org/abs/2502.07087)