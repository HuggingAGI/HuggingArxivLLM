# 大型语言模型的定量评估方法

发布时间：2025年06月03日

`LLM应用

这篇论文探讨了大型语言模型（LLM）在评估任务中的应用，展示了如何利用LLM作为评估工具来提升评估效果。因此，它属于LLM应用类别。` `人工智能`

> Quantitative LLM Judges

# 摘要

> LLM作为评估者是一种框架，其中大型语言模型（LLM）自动评估另一个LLM的输出。我们提出了定量LLM评估者，通过回归模型将现有评估者的评分与特定领域的人类评分对齐。模型利用评估者的文本评价和评分进行训练，以提升原始评估者的评分。我们展示了适用于不同类型绝对和相对反馈的四个定量评估者，这体现了我们框架的通用性和灵活性。我们的框架在计算效率上优于监督微调，并且在人类反馈有限的情况下，统计效率更高，这在我们的工作中大多数应用场景中是预期的。我们在四个数据集上使用两个基础评估者进行了实证验证。实验表明，通过后验建模，定量评估者能够有效提升现有评估者的预测能力。

> LLM-as-a-judge is a framework in which a large language model (LLM) automatically evaluates the output of another LLM. We propose quantitative LLM judges, which align evaluation scores of existing LLM judges to human scores in a given domain using regression models. The models are trained to improve the score of the original judge by using the judge's textual evaluation and score. We present four quantitative judges for different types of absolute and relative feedback, which showcases the generality and versatility of our framework. Our framework is more computationally efficient than supervised fine-tuning and can be more statistically efficient when human feedback is limited, which is expected in most applications of our work. We validate these claims empirically on four datasets using two base judges. Our experiments show that quantitative judges can effectively improve the predictive power of existing judges through post-hoc modeling.

[Arxiv](https://arxiv.org/abs/2506.02945)