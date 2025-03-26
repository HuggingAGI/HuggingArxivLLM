# KSHSeek: 利用数据驱动的方法解决生成模型中的知识捷径幻觉问题

发布时间：2025年03月25日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在生成任务中出现的幻觉问题，特别是从知识捷径的角度分析了其成因，并提出了解决方法。研究重点在于模型的内在机制和理论分析，属于LLM理论范畴。` `问答系统`

> KSHSeek: Data-Driven Approaches to Mitigating and Detecting Knowledge-Shortcut Hallucinations in Generative Models

# 摘要

> 大型语言模型 (LLMs) 的出现极大地推动了自然语言处理 (NLP) 的发展，尤其是在问答等文本生成任务中。然而，模型幻觉仍然是一个重大挑战，其复杂的原因使其在自然语言生成 (NLG) 任务中难以应对。我们从知识捷径的角度系统地探讨了事实性幻觉的成因，揭示了即使基于正确且无缺陷的数据，知识捷径幻觉在生成模型中仍然普遍存在。为了解决这一问题，我们在数据预处理层面提出了一种高相似度剪枝算法，有效减少了数据中的虚假关联。此外，我们设计了一种专门针对知识捷径幻觉的检测方法，以评估缓解策略的效果。实验结果表明，我们的方法在微调任务中显著减少了知识捷径幻觉，同时在问答任务中并未对模型性能产生负面影响。这项工作为缓解生成模型中的特定幻觉问题提供了新思路，增强了其在实际应用中的健壮性和可靠性。

> The emergence of large language models (LLMs) has significantly advanced the development of natural language processing (NLP), especially in text generation tasks like question answering. However, model hallucinations remain a major challenge in natural language generation (NLG) tasks due to their complex causes. We systematically expand on the causes of factual hallucinations from the perspective of knowledge shortcuts, analyzing hallucinations arising from correct and defect-free data and demonstrating that knowledge-shortcut hallucinations are prevalent in generative models. To mitigate this issue, we propose a high similarity pruning algorithm at the data preprocessing level to reduce spurious correlations in the data. Additionally, we design a specific detection method for knowledge-shortcut hallucinations to evaluate the effectiveness of our mitigation strategy. Experimental results show that our approach effectively reduces knowledge-shortcut hallucinations, particularly in fine-tuning tasks, without negatively impacting model performance in question answering. This work introduces a new paradigm for mitigating specific hallucination issues in generative models, enhancing their robustness and reliability in real-world applications.

[Arxiv](https://arxiv.org/abs/2503.19482)