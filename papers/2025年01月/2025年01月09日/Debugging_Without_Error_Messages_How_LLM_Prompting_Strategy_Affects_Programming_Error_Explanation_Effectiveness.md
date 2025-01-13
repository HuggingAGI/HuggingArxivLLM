# 无错误信息调试：LLM 提示策略对编程错误解释效果的影响

发布时间：2025年01月09日

`LLM应用

**理由**：这篇论文主要探讨了如何利用大型语言模型（LLMs）生成对编程错误的解释，特别是针对初学者的场景。研究重点在于如何通过不同的提示策略和微调方法来提升LLMs在生成错误解释方面的效果。这属于LLM在实际应用中的使用，特别是教育领域的应用，因此归类为“LLM应用”。`

> Debugging Without Error Messages: How LLM Prompting Strategy Affects Programming Error Explanation Effectiveness

# 摘要

> # 摘要
编程中犯错是常态，即便是经验丰富的开发者也不例外，而初学者更是难免频繁出错。传统的编译器或解释器错误信息往往对初学者帮助有限，甚至可能带来困惑、误导或挫败感。最新研究表明，大型语言模型（LLMs）能够生成高质量的错误解释，但其效果高度依赖于是否提供了上下文——通常是出错的源代码。鉴于传统错误信息可能对初学者无益甚至有害，我们反其道而行之：仅提供错误的源代码（不包含编译器/解释器的原始错误信息），观察 GPT-3.5 如何生成错误解释。我们尝试了多种策略，如单次提示和微调，以提升解释效果。我们评估了这些解释在反馈中的基线表现，并探讨了不同提示策略对解释效果的提升。研究结果有助于教育工作者理解 LLMs 如何响应初学者的常见错误提示，从而推动生成式 AI 在课堂中的更有效应用。

> Making errors is part of the programming process -- even for the most seasoned professionals. Novices in particular are bound to make many errors while learning. It is well known that traditional (compiler/interpreter) programming error messages have been less than helpful for many novices and can have effects such as being frustrating, containing confusing jargon, and being downright misleading. Recent work has found that large language models (LLMs) can generate excellent error explanations, but that the effectiveness of these error messages heavily depends on whether the LLM has been provided with context -- typically the original source code where the problem occurred. Knowing that programming error messages can be misleading and/or contain that serves little-to-no use (particularly for novices) we explore the reverse: what happens when GPT-3.5 is prompted for error explanations on just the erroneous source code itself -- original compiler/interpreter produced error message excluded. We utilized various strategies to make more effective error explanations, including one-shot prompting and fine-tuning. We report the baseline results of how effective the error explanations are at providing feedback, as well as how various prompting strategies might improve the explanations' effectiveness. Our results can help educators by understanding how LLMs respond to such prompts that novices are bound to make, and hopefully lead to more effective use of Generative AI in the classroom.

[Arxiv](https://arxiv.org/abs/2501.05706)