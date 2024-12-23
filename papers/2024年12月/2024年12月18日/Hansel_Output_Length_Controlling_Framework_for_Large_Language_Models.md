# Hansel：用于大型语言模型的输出长度控制框架

发布时间：2024年12月18日

`LLM应用` `模型优化`

> Hansel: Output Length Controlling Framework for Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）成就斐然，但有效控制输出序列的长度依旧是个难题。在本文中，我们推出了 Hansel 这一高效的 LLMs 长度控制框架，且不影响其生成能力。Hansel 借助周期性输出的隐藏特殊标记来追踪输出序列的剩余目标长度。再加上避免输出突然终止的技术，这种看似简单的方法高效又通用，还不影响生成文本的连贯性和流畅性。此框架能在模型的微调阶段应用于任何预训练的 LLMs，不论其原始位置编码方式怎样。我们通过用 Hansel 对四个不同的 LLMs 进行微调来加以证明，结果显示，与基于提示的长度控制微调相比，每个模型和数据集中输出序列的平均绝对误差都大幅降低。此外，该框架在对微调期间未曾见过的目标长度（比如长对话回应或极短的摘要）进行外推时，能力有了显著提升。这表明模型学到的是长度控制的通用手段，而非学习让输出长度与训练期间所见的长度相匹配。

> Despite the great success of large language models (LLMs), efficiently controlling the length of the output sequence still remains a challenge. In this paper, we propose Hansel, an efficient framework for length control in LLMs without affecting its generation ability. Hansel utilizes periodically outputted hidden special tokens to keep track of the remaining target length of the output sequence. Together with techniques to avoid abrupt termination of the output, this seemingly simple method proved to be efficient and versatile, while not harming the coherency and fluency of the generated text. The framework can be applied to any pre-trained LLMs during the finetuning stage of the model, regardless of its original positional encoding method. We demonstrate this by finetuning four different LLMs with Hansel and show that the mean absolute error of the output sequence decreases significantly in every model and dataset compared to the prompt-based length control finetuning. Moreover, the framework showed a substantially improved ability to extrapolate to target lengths unseen during finetuning, such as long dialog responses or extremely short summaries. This indicates that the model learns the general means of length control, rather than learning to match output lengths to those seen during training.

[Arxiv](https://arxiv.org/abs/2412.14033)