# 通过联想记忆理解 Transformer 中的事实召回

发布时间：2024年12月09日

`LLM理论` `语言模型` `信息存储`

> Understanding Factual Recall in Transformers via Associative Memories

# 摘要

> 大型语言模型展现出了超强的事实回忆能力。以往研究发现，针对事实回忆任务训练的转换器，其信息存储速率与参数数量成正比。在我们的工作里，我们指出浅层转换器能通过联想记忆的组合获取近乎最优的存储容量。我们先是证明了线性和 MLP 联想记忆的存储容量与参数数量呈线性关系。接着，我们引入一个合成的事实回忆任务，并证实只要自注意力参数或 MLP 参数的总数（最多考虑对数因子）与事实数量成线性比例，具有单层自注意力后接 MLP 的转换器在该任务上就能达到 100%的准确率。特别地，转换器能够在将值矩阵或 MLP 用作联想记忆来存储事实数据集之间进行权衡。我们对在我们的事实回忆任务上训练的简化线性注意力模型的梯度流轨迹进行分析，以此补充这些表达能力的结果，结果表明该模型呈现出顺序学习的行为。

> Large language models have demonstrated an impressive ability to perform factual recall. Prior work has found that transformers trained on factual recall tasks can store information at a rate proportional to their parameter count. In our work, we show that shallow transformers can use a combination of associative memories to obtain such near optimal storage capacity. We begin by proving that the storage capacities of both linear and MLP associative memories scale linearly with parameter count. We next introduce a synthetic factual recall task, and prove that a transformer with a single layer of self-attention followed by an MLP can obtain 100% accuracy on the task whenever either the total number of self-attention parameters or MLP parameters scales (up to log factors) linearly with the number of facts. In particular, the transformer can trade off between using the value matrices or the MLP as an associative memory to store the dataset of facts. We complement these expressivity results with an analysis of the gradient flow trajectory of a simplified linear attention model trained on our factual recall task, where we show that the model exhibits sequential learning behavior.

[Arxiv](https://arxiv.org/abs/2412.06538)