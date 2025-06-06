# 研究预训练语言模型中的语言知识作用：以UD为例

发布时间：2025年06月05日

`LLM应用

理由：这篇论文探讨了如何将通用依赖（UD）框架整合到预训练语言模型中，以提升其在跨语言对抗性改写识别任务中的性能。研究重点在于应用UD框架来改进模型的表现，属于大语言模型的具体应用场景。` `信息处理`

> Evaluating the Effectiveness of Linguistic Knowledge in Pretrained Language Models: A Case Study of Universal Dependencies

# 摘要

> 通用依赖（UD）作为跨语言句法表示的最成功框架，其有效性尚未得到充分挖掘。本文通过将其整合到预训练语言模型中，评估其在跨语言对抗性改写识别任务中的表现。实验结果表明，引入UD显著提升了准确率和F1分数，平均提升分别达到3.85%和6.08%。这一改进不仅缩小了预训练模型与大语言模型在部分语言对上的性能差距，甚至在某些情况下超越了后者。此外，基于UD的相似性评分与模型性能呈正相关，这表明UD在跨领域任务中具有良好的有效性和应用潜力。

> Universal Dependencies (UD), while widely regarded as the most successful linguistic framework for cross-lingual syntactic representation, remains underexplored in terms of its effectiveness. This paper addresses this gap by integrating UD into pretrained language models and assesses if UD can improve their performance on a cross-lingual adversarial paraphrase identification task. Experimental results show that incorporation of UD yields significant improvements in accuracy and $F_1$ scores, with average gains of 3.85\% and 6.08\% respectively. These enhancements reduce the performance gap between pretrained models and large language models in some language pairs, and even outperform the latter in some others. Furthermore, the UD-based similarity score between a given language and English is positively correlated to the performance of models in that language. Both findings highlight the validity and potential of UD in out-of-domain tasks.

[Arxiv](https://arxiv.org/abs/2506.04887)