# 自我批判与精炼：构建忠实自然语言解释的方法

发布时间：2025年05月28日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）生成自然语言解释（NLEs）的忠实度问题，并提出了一种新的框架（SR-NLE），通过自我批评和优化过程来提高解释的忠实度。研究内容主要集中在模型自身的改进和优化，属于对LLM理论的探索和研究。` `人工智能`

> Self-Critique and Refinement for Faithful Natural Language Explanations

# 摘要

> 随着大型语言模型（LLMs）的快速发展，自然语言解释（NLEs）在理解模型预测方面变得越来越重要。然而，这些解释往往无法真实反映模型的实际推理过程。尽管现有研究表明LLMs可以自我批评并优化其在各种任务中的初始输出，但这一能力尚未被探索用于提高解释的忠实度。为了解决这一问题，我们提出了Self-critique and Refinement for Natural Language Explanations（SR-NLE），这是一种框架，使模型能够通过迭代的自我批评和优化过程（无需外部监督）提高自身解释的忠实度，特别是针对事后NLEs。我们的框架利用了不同的反馈机制来指导优化过程，包括自然语言自我反馈，以及一种基于特征归因的新颖反馈方法，该方法突出了重要的输入词汇。在三个数据集和四个最先进的LLMs上的实验表明，SR-NLE显著降低了不忠实率，我们的最佳方法实现了平均不忠实率为36.02%，而基线为54.81%，绝对降低了18.79%。这些发现表明，所研究的LLMs确实能够优化其解释，以更好地反映其实际推理过程，只需通过反馈提供适当的指导，而无需额外的训练或微调。

> With the rapid development of large language models (LLMs), natural language explanations (NLEs) have become increasingly important for understanding model predictions. However, these explanations often fail to faithfully represent the model's actual reasoning process. While existing work has demonstrated that LLMs can self-critique and refine their initial outputs for various tasks, this capability remains unexplored for improving explanation faithfulness. To address this gap, we introduce Self-critique and Refinement for Natural Language Explanations (SR-NLE), a framework that enables models to improve the faithfulness of their own explanations -- specifically, post-hoc NLEs -- through an iterative critique and refinement process without external supervision. Our framework leverages different feedback mechanisms to guide the refinement process, including natural language self-feedback and, notably, a novel feedback approach based on feature attribution that highlights important input words. Our experiments across three datasets and four state-of-the-art LLMs demonstrate that SR-NLE significantly reduces unfaithfulness rates, with our best method achieving an average unfaithfulness rate of 36.02%, compared to 54.81% for baseline -- an absolute reduction of 18.79%. These findings reveal that the investigated LLMs can indeed refine their explanations to better reflect their actual reasoning process, requiring only appropriate guidance through feedback without additional training or fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.22823)