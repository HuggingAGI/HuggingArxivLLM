# VisualPuzzles：将多模态推理评估与领域知识解耦

发布时间：2025年04月14日

`LLM应用` `视觉推理` `多模态技术`

> VisualPuzzles: Decoupling Multimodal Reasoning Evaluation from Domain Knowledge

# 摘要

> 当前多模态基准测试常将推理与领域知识混为一谈，导致在非专家环境中难以分离和评估通用推理能力。为解决这一问题，我们推出了VisualPuzzles——一个专注于视觉推理的基准测试，刻意减少了对专业知识的依赖。该基准包含五个类别的多样化问题：算法推理、类比推理、演绎推理、归纳推理和空间推理。其中一个问题来源是手动翻译的中国公务员考试逻辑推理题。

实验表明，与MMMU等基准相比，VisualPuzzles需要显著减少的领域特定知识，同时需要更复杂的推理，使我们能够更好地评估真正的多模态推理能力。评估显示，最先进的多模态大型语言模型在VisualPuzzles上始终落后于人类表现，并且在知识密集型基准上表现出色并不一定意味着在以推理为重点、知识较轻的任务上也能取得成功。

此外，推理增强方法（如增加推理计算量（使用“思考”模式）在不同模型和任务类型上带来的收益并不一致，我们也没有观察到模型大小与性能之间的明显相关性。我们还发现，与更强调知识的基准相比，模型在VisualPuzzles上表现出不同的推理和回答模式。VisualPuzzles为我们提供了一个更清晰的视角，用于评估超越事实记忆和领域知识的推理能力。

> Current multimodal benchmarks often conflate reasoning with domain-specific knowledge, making it difficult to isolate and evaluate general reasoning abilities in non-expert settings. To address this, we introduce VisualPuzzles, a benchmark that targets visual reasoning while deliberately minimizing reliance on specialized knowledge. VisualPuzzles consists of diverse questions spanning five categories: algorithmic, analogical, deductive, inductive, and spatial reasoning. One major source of our questions is manually translated logical reasoning questions from the Chinese Civil Service Examination. Experiments show that VisualPuzzles requires significantly less intensive domain-specific knowledge and more complex reasoning compared to benchmarks like MMMU, enabling us to better evaluate genuine multimodal reasoning. Evaluations show that state-of-the-art multimodal large language models consistently lag behind human performance on VisualPuzzles, and that strong performance on knowledge-intensive benchmarks does not necessarily translate to success on reasoning-focused, knowledge-light tasks. Additionally, reasoning enhancements such as scaling up inference compute (with "thinking" modes) yield inconsistent gains across models and task types, and we observe no clear correlation between model size and performance. We also found that models exhibit different reasoning and answering patterns on VisualPuzzles compared to benchmarks with heavier emphasis on knowledge. VisualPuzzles offers a clearer lens through which to evaluate reasoning capabilities beyond factual recall and domain knowledge.

[Arxiv](https://arxiv.org/abs/2504.10342)