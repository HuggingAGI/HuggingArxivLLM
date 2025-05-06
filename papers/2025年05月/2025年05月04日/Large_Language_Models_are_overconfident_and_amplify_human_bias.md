# 大型语言模型不仅过度自信，还加剧了人类偏见的问题。

发布时间：2025年05月04日

`LLM理论` `人工智能` `决策支持`

> Large Language Models are overconfident and amplify human bias

# 摘要

> 大型语言模型（LLMs）正在彻底改变社会的方方面面。它们越来越多地被用于解决问题的任务中，以替代人类的评估和推理。由于 LLMs 是基于人类的书写内容进行训练的，因此容易学习到人类的偏见。其中，过度自信是人类最常见的偏见之一。我们研究了 LLMs 是否继承了这一偏见。我们自动构建了具有已知事实依据的推理问题，并提示 LLMs 对其答案的自信程度进行评估，这一过程严格遵循人类实验中的类似协议。我们发现，我们研究的所有五种 LLM 都存在过度自信的问题：它们对自己的答案正确性的估计过高，误差范围在 20% 到 60% 之间。人类的准确性与更先进的 LLM 相当，但过度自信的程度却低得多。尽管在那些人类和 LLMs 都确信自己正确回答了的问题上，两者的偏见相似，但一个关键差异显现出来：当 LLMs 对自己答案的正确性不再那么确定时，它们的偏见相对于人类会急剧增加。我们还展示了 LLM 输入对人类决策的模糊影响：LLM 输入提高了准确性，但同时也使答案的过度自信程度增加了一倍多。

> Large language models (LLMs) are revolutionizing every aspect of society. They are increasingly used in problem-solving tasks to substitute human assessment and reasoning. LLMs are trained on what humans write and thus prone to learn human biases. One of the most widespread human biases is overconfidence. We examine whether LLMs inherit this bias. We automatically construct reasoning problems with known ground truths, and prompt LLMs to assess the confidence in their answers, closely following similar protocols in human experiments. We find that all five LLMs we study are overconfident: they overestimate the probability that their answer is correct between 20% and 60%. Humans have accuracy similar to the more advanced LLMs, but far lower overconfidence. Although humans and LLMs are similarly biased in questions which they are certain they answered correctly, a key difference emerges between them: LLM bias increases sharply relative to humans if they become less sure that their answers are correct. We also show that LLM input has ambiguous effects on human decision making: LLM input leads to an increase in the accuracy, but it more than doubles the extent of overconfidence in the answers.

[Arxiv](https://arxiv.org/abs/2505.02151)