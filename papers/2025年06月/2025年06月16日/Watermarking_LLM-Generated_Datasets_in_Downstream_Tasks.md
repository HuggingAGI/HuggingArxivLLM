# # 在下游任务中为大型语言模型生成数据集打上水印

发布时间：2025年06月16日

`LLM应用` `版权保护` `数据安全`

> Watermarking LLM-Generated Datasets in Downstream Tasks

# 摘要

> 大型语言模型（LLMs）正以惊人的速度发展，其应用已渗透到情感分类、评论生成和问答系统等多个领域。凭借其高效的性能和强大的适应性，LLM生成的数据已成为训练模型的重要来源。然而，LLM生成内容的追踪难题日益凸显，这可能给LLM所有者带来版权纠纷风险。针对这一问题，本文提出了一种向LLM生成数据集注入水印的方法，从而实现对下游任务的追踪，判断数据集是否由原始LLM生成。这些下游任务主要分为两类：一类是在输入级别使用生成数据集进行分类任务训练；另一类是将LLM生成内容作为输出用于下游任务，如问答任务。我们设计了全面的实验来评估这两种水印方法的效果。实验结果表明，我们的水印方法表现优异。此外，在模型实用性方面，基于生成数据集训练的分类器在多数情况下实现了超过0.900的测试准确率，证明了此类模型的可靠性。对于输出级别水印，生成文本的质量与真实世界数据集生成的文本不相上下。通过这项研究，我们希望为LLM版权保护开辟新路径，为该领域知识产权的保护迈出重要一步。

> Large Language Models (LLMs) have experienced rapid advancements, with applications spanning a wide range of fields, including sentiment classification, review generation, and question answering. Due to their efficiency and versatility, researchers and companies increasingly employ LLM-generated data to train their models. However, the inability to track content produced by LLMs poses a significant challenge, potentially leading to copyright infringement for the LLM owners. In this paper, we propose a method for injecting watermarks into LLM-generated datasets, enabling the tracking of downstream tasks to detect whether these datasets were produced using the original LLM. These downstream tasks can be divided into two categories. The first involves using the generated datasets at the input level, commonly for training classification tasks. The other is the output level, where model trainers use LLM-generated content as output for downstream tasks, such as question-answering tasks. We design a comprehensive set of experiments to evaluate both watermark methods. Our results indicate the high effectiveness of our watermark approach. Additionally, regarding model utility, we find that classifiers trained on the generated datasets achieve a test accuracy exceeding 0.900 in many cases, suggesting that the utility of such models remains robust. For the output-level watermark, we observe that the quality of the generated text is comparable to that produced using real-world datasets. Through our research, we aim to advance the protection of LLM copyrights, taking a significant step forward in safeguarding intellectual property in this domain.

[Arxiv](https://arxiv.org/abs/2506.13494)