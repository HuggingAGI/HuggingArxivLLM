# 关键词生成的核心算法：基于指令的LLM在俄语科学关键词生成中的应用

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在生成俄语科学摘要关键词任务上的应用。论文通过对比零-shot、少-shot提示方法、微调模型和无监督方法的性能，展示了LLMs在无需任务特定微调的情况下，仅通过文本提示即可取得显著成果。这属于LLM在实际任务中的应用研究，因此归类为LLM应用。`

> Key Algorithms for Keyphrase Generation: Instruction-Based LLMs for Russian Scientific Keyphrases

# 摘要

> 关键词选择是自然语言处理中一项既具挑战性又应用广泛的任务。然而，由于俄语形态复杂且训练数据集有限，现有的监督和无监督解决方案在俄语中的适应性面临诸多限制。最近的研究表明，大型语言模型（LLMs）在生成关键词任务上表现出色，无需任务特定微调，仅通过文本提示即可取得显著成果。本文评估了基于提示的方法在生成俄语科学摘要关键词上的表现。我们首先对比了零-shot、少-shot 提示方法、微调模型和无监督方法的性能，随后探讨了少-shot 设置下关键词示例的选择策略。通过人类评估和专家分析，我们展示了生成关键词的结果，并揭示了模型的优缺点。结果表明，即使使用简单的文本提示，基于提示的方法也能超越常见基线。

> Keyphrase selection is a challenging task in natural language processing that has a wide range of applications. Adapting existing supervised and unsupervised solutions for the Russian language faces several limitations due to the rich morphology of Russian and the limited number of training datasets available. Recent studies conducted on English texts show that large language models (LLMs) successfully address the task of generating keyphrases. LLMs allow achieving impressive results without task-specific fine-tuning, using text prompts instead. In this work, we access the performance of prompt-based methods for generating keyphrases for Russian scientific abstracts. First, we compare the performance of zero-shot and few-shot prompt-based methods, fine-tuned models, and unsupervised methods. Then we assess strategies for selecting keyphrase examples in a few-shot setting. We present the outcomes of human evaluation of the generated keyphrases and analyze the strengths and weaknesses of the models through expert assessment. Our results suggest that prompt-based methods can outperform common baselines even using simple text prompts.

[Arxiv](https://arxiv.org/abs/2410.18040)