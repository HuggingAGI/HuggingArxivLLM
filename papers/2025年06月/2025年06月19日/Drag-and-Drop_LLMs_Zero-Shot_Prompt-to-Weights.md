# 拖放LLMs：零样本提示到权重转换

发布时间：2025年06月19日

`LLM应用

摘要中讨论了如何通过参数生成器优化大型语言模型的微调过程，属于应用层面的创新，因此归类为LLM应用。` `机器学习`

> Drag-and-Drop LLMs: Zero-Shot Prompt-to-Weights

# 摘要

> 现代参数高效微调方法（如低秩适配LoRA）降低了定制大型语言模型的成本，但依然需要为每个下游数据集单独优化。我们推出	extbf{拖放式LLMs（	extit{DnD）}}，一种基于提示的参数生成器，通过将少量无标签任务提示直接映射到LoRA权重更新，从而避免了按任务训练的需求。轻量级文本编码器将每个提示批次转化为条件嵌入，随后通过级联超卷积解码器生成完整的LoRA矩阵。在多样化提示-检查点对集合中训练后，DnD可在数秒内生成任务特定参数，带来以下优势：i）相比完整微调，开销降低多达	extbf{12,000倍}；ii）在常识推理、数学、编码和多模态等未见过的基准测试中，性能平均提升高达	extbf{30\%}，超越最强的训练LoRAs；iii）即使从未接触过目标数据或标签，仍能实现强大的跨领域泛化。我们的研究证明，基于提示的参数生成是基于梯度适应的高效替代方案，能够快速专业化LLMs。项目详情请访问\href{https://jerryliang24.github.io/DnD}{https://jerryliang24.github.io/DnD}。

> Modern Parameter-Efficient Fine-Tuning (PEFT) methods such as low-rank adaptation (LoRA) reduce the cost of customizing large language models (LLMs), yet still require a separate optimization run for every downstream dataset. We introduce \textbf{Drag-and-Drop LLMs (\textit{DnD})}, a prompt-conditioned parameter generator that eliminates per-task training by mapping a handful of unlabeled task prompts directly to LoRA weight updates. A lightweight text encoder distills each prompt batch into condition embeddings, which are then transformed by a cascaded hyper-convolutional decoder into the full set of LoRA matrices. Once trained in a diverse collection of prompt-checkpoint pairs, DnD produces task-specific parameters in seconds, yielding i) up to \textbf{12,000$\times$} lower overhead than full fine-tuning, ii) average gains up to \textbf{30\%} in performance over the strongest training LoRAs on unseen common-sense reasoning, math, coding, and multimodal benchmarks, and iii) robust cross-domain generalization despite never seeing the target data or labels. Our results demonstrate that prompt-conditioned parameter generation is a viable alternative to gradient-based adaptation for rapidly specializing LLMs. Our project is available at \href{https://jerryliang24.github.io/DnD}{https://jerryliang24.github.io/DnD}.

[Arxiv](https://arxiv.org/abs/2506.16406)