# 校正式上下文学习：评估大语言模型的自我纠错能力

发布时间：2025年03月20日

`LLM理论` `人工智能`

> Corrective In-Context Learning: Evaluating Self-Correction in Large Language Models

# 摘要

> 在自然语言处理任务中，in-context learning (ICL) 通过基于标注样例进行条件化而无需微调，使大型语言模型 (LLMs) 实现了少样本学习，从而改变了 LLMs 的使用方式。尽管 ICL 有效，但它容易出错，尤其是在处理具有挑战性的样例时。为了提升 ICL 的表现，我们提出了一种名为 corrective in-context learning (CICL) 的方法，该方法将模型的错误预测及其真实标签的修正纳入提示中，旨在通过自我纠错提高分类准确度。然而，与我们的假设相反，我们在文本分类任务上的大量实验表明，CICL 通常表现不如标准 ICL，且随着提示中修正的比例增加，性能下降。我们的研究发现，CICL 通过扰乱模型的任务理解引入了困惑，而非精炼其预测。此外，我们发现，在标准 ICL 中呈现更难的样例并不会提升性能，这表明仅凭样例难度可能无法作为有效选择的可靠标准。通过展示这些负面结果，我们为理解 LLMs 中自我纠错机制的局限性提供了重要见解，并为未来的研究指明了方向。

> In-context learning (ICL) has transformed the use of large language models (LLMs) for NLP tasks, enabling few-shot learning by conditioning on labeled examples without finetuning. Despite its effectiveness, ICL is prone to errors, especially for challenging examples. With the goal of improving the performance of ICL, we propose corrective in-context learning (CICL), an approach that incorporates a model's incorrect predictions alongside ground truth corrections into the prompt, aiming to enhance classification accuracy through self-correction. However, contrary to our hypothesis, extensive experiments on text classification tasks demonstrate that CICL consistently underperforms standard ICL, with performance degrading as the proportion of corrections in the prompt increases. Our findings indicate that CICL introduces confusion by disrupting the model's task understanding, rather than refining its predictions. Additionally, we observe that presenting harder examples in standard ICL does not improve performance, suggesting that example difficulty alone may not be a reliable criterion for effective selection. By presenting these negative results, we provide important insights into the limitations of self-corrective mechanisms in LLMs and offer directions for future research.

[Arxiv](https://arxiv.org/abs/2503.16022)