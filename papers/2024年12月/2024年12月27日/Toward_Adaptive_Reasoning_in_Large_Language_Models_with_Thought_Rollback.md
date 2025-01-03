# 迈向具备思维回滚能力的大型语言模型自适应推理

发布时间：2024年12月27日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的推理结构问题，并提出了一种新的推理框架“思维回滚”（Thought Rollback, TR），旨在改进LLMs在面对复杂任务或产生“幻觉”时的推理能力。论文的核心内容集中在LLMs的推理机制和理论改进上，属于对LLM理论的研究和扩展，因此应归类为LLM理论。` `人工智能` `推理系统`

> Toward Adaptive Reasoning in Large Language Models with Thought Rollback

# 摘要

> 大型语言模型（LLMs）通常通过逐步推理来解决各种任务，但其推理结构（如链式、树状或无环有向图）往往僵化且单向。这种不灵活的推理方式在面对复杂任务或LLM频繁产生“幻觉”时容易失效。为此，本文提出了一种名为“思维回滚”（Thought Rollback, TR）的新推理框架，允许LLMs在“幻觉”情况下自适应地构建思维结构，同时保持高效的问题解决能力。TR的核心机制是通过回滚思维，让LLMs能够分析错误并修正之前的错误推理。通过在提示中加入这种试错过程，每次回滚都能生成一条更可靠的推理路径。因此，即使从简单的无注释提示开始，带有TR的LLM也能逐步探索出正确的解决方案。在数学问题和多任务推理上的实验表明，TR在问题解决率和交互成本上均达到了最先进的水平。例如，在MATH数据集上，带有TR的GPT-4的解决率比当前最佳方法高出9%。

> Large language models (LLMs) have been routinely used to solve various tasks using step-by-step reasoning. However, the structure of intermediate reasoning steps, or thoughts, is rigid and unidirectional, such as chains, trees, or acyclic-directed graphs. Consequently, the resulting inflexible and forward-only reasoning may not address challenging tasks and fail when the LLM frequently gives false responses, i.e., ``hallucinations''. This paper proposes a new reasoning framework, called Thought Rollback (TR), allowing LLMs to adaptively build thought structure while maintaining effective reasoning toward problem-solving under ``hallucinations''. The core mechanism of TR is rolling back thoughts, which allows LLMs to perform error analysis on thoughts, and thus roll back to any previously mistaken thought for revision. Subsequently, by including such trial-and-error in the prompt to guide the LLM, each rollback leads to one more reliable reasoning path. Therefore, starting with a simple prompt without human annotations, LLM with TR adaptively and gradually explores thoughts for a correct solution. Comprehensive experiments on mathematical problems and multi-task reasoning demonstrate the state-of-the-art performance of TR in terms of problem-solving rate and interaction cost. For instance, the solving rate of GPT-4 with TR outperforms the current best by $9\%$ on the MATH dataset.

[Arxiv](https://arxiv.org/abs/2412.19707)