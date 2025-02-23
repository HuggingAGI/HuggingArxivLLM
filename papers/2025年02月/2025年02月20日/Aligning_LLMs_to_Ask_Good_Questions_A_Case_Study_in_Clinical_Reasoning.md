# 让 LLMs 学会提出好问题：临床推理中的案例研究

发布时间：2025年02月20日

`LLM理论`

> Aligning LLMs to Ask Good Questions A Case Study in Clinical Reasoning

# 摘要

> 大型语言模型（LLMs）在不确定性场景下常常无法提出有效的问题，这使得它们在需要主动信息收集来辅助决策的关键领域中显得不可靠。为此，我们提出了一个名为ALFA的框架，通过以下三个步骤来提升LLMs的问题提出能力：首先，将"好"问题的概念分解为一组有理论依据的属性（如清晰度、相关性）；其次，可控地合成特定属性的问题变体；最后，通过基于偏好的优化对模型进行对齐，使其能够明确学习如何根据这些细粒度属性提出更好的问题。

以临床推理为例，我们引入了MediQ-AskDocs数据集，该数据集包含17,000个真实世界的临床互动，并补充了80,000个后续问题的特定属性偏好对。此外，我们还提出了一项由专家标注的新颖交互式医疗问答任务，用于评估问题提出能力。实验结果显示，与最先进的指令微调LLMs相比，采用ALFA框架对齐的模型在MediQ-AskDocs上的诊断错误减少了56.6%，问题级别的胜率达到了64.4%，并且具有很强的泛化能力。我们的研究结果表明，通过结构化、细粒度的属性来明确指导问题提出，为提升LLMs的能力，特别是在专家应用领域，提供了一条可扩展的路径。

> Large language models (LLMs) often fail to ask effective questions under uncertainty, making them unreliable in domains where proactive information-gathering is essential for decisionmaking. We present ALFA, a framework that improves LLM question-asking by (i) decomposing the notion of a "good" question into a set of theory-grounded attributes (e.g., clarity, relevance), (ii) controllably synthesizing attribute-specific question variations, and (iii) aligning models via preference-based optimization to explicitly learn to ask better questions along these fine-grained attributes. Focusing on clinical reasoning as a case study, we introduce the MediQ-AskDocs dataset, composed of 17k real-world clinical interactions augmented with 80k attribute-specific preference pairs of follow-up questions, as well as a novel expert-annotated interactive healthcare QA task to evaluate question-asking abilities. Models aligned with ALFA reduce diagnostic errors by 56.6% on MediQ-AskDocs compared to SOTA instruction-tuned LLMs, with a question-level win-rate of 64.4% and strong generalizability. Our findings suggest that explicitly guiding question-asking with structured, fine-grained attributes offers a scalable path to improve LLMs, especially in expert application domains.

[Arxiv](https://arxiv.org/abs/2502.14860)