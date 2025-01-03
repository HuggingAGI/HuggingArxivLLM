# 提示与微调小型LLMs：实现长度可控的电话通话摘要

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来构建电话通话摘要系统，涉及了提示工程、合成数据生成、模型微调以及评估技术等应用层面的内容。因此，它属于LLM应用的范畴。`

> Prompting and Fine-Tuning of Small LLMs for Length-Controllable Telephone Call Summarization

# 摘要

> 本文研究了如何利用大型语言模型（LLMs）快速构建电话通话摘要系统。我们首先通过提示现有LLMs生成电话对话摘要进行初步实验，随后利用更强大的前沿模型创建定制化的合成训练数据集。我们特别关注生成数据的多样性和摘要长度的可控性，以满足不同用例的需求。通过两种先进的基于LLM的评估技术，我们验证了方法的有效性，确保摘要的质量和相关性。结果显示，基于微调的Llama-2-7B模型在事实准确性、完整性和简洁性上与GPT-4表现相当。这一研究为快速构建高效实用的通话摘要系统提供了有力支持。

> This paper explores the rapid development of a telephone call summarization system utilizing large language models (LLMs). Our approach involves initial experiments with prompting existing LLMs to generate summaries of telephone conversations, followed by the creation of a tailored synthetic training dataset utilizing stronger frontier models. We place special focus on the diversity of the generated data and on the ability to control the length of the generated summaries to meet various use-case specific requirements. The effectiveness of our method is evaluated using two state-of-the-art LLM-as-a-judge-based evaluation techniques to ensure the quality and relevance of the summaries. Our results show that fine-tuned Llama-2-7B-based summarization model performs on-par with GPT-4 in terms of factual accuracy, completeness and conciseness. Our findings demonstrate the potential for quickly bootstrapping a practical and efficient call summarization system.

[Arxiv](https://arxiv.org/abs/2410.18624)