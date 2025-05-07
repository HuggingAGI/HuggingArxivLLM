# 换个说法：基于用户反馈的改写框架

发布时间：2025年05月06日

`LLM理论` `人工智能`

> Say It Another Way: A Framework for User-Grounded Paraphrasing

# 摘要

> 提示词的微小变化可能会导致大型语言模型（LLMs）的行为产生显著差异，这引发了人们对模型评估稳定性和可靠性的担忧。尽管之前的研究探索了简单的格式调整，但这些调整很少能捕捉到真实语言使用中自然出现的变化。我们提出了一种基于最小语言转换分类的控制性改写框架，以系统地生成自然的提示词变体。通过BBQ数据集，我们使用人工标注和自动化检查验证了我们的方法，然后利用它来研究LLMs在刻板印象评估任务中对改写提示词的反应。我们的分析表明，即使是细微的提示词修改也会导致模型行为的重大变化。这些结果凸显了建立稳健且能识别改写的评估方案的必要性。

> Small changes in how a prompt is worded can lead to meaningful differences in the behavior of large language models (LLMs), raising concerns about the stability and reliability of their evaluations. While prior work has explored simple formatting changes, these rarely capture the kinds of natural variation seen in real-world language use. We propose a controlled paraphrasing framework based on a taxonomy of minimal linguistic transformations to systematically generate natural prompt variations. Using the BBQ dataset, we validate our method with both human annotations and automated checks, then use it to study how LLMs respond to paraphrased prompts in stereotype evaluation tasks. Our analysis shows that even subtle prompt modifications can lead to substantial changes in model behavior. These results highlight the need for robust, paraphrase-aware evaluation protocols.

[Arxiv](https://arxiv.org/abs/2505.03563)