# 上下文学习与反学习中的长度偏差

发布时间：2025年02月10日

`LLM理论`

> In-Context Learning (and Unlearning) of Length Biases

# 摘要

> 大型语言模型在上下文学习方面表现出色，通过将示例输入-输出对附加到提示中以进行演示。然而，现有研究表明，模型能够学习词汇和标签偏差，这对模型的性能和鲁棒性产生负面影响。其他统计数据偏差的影响仍需进一步探索，这也是本研究的目标。我们特别研究了长度偏差对上下文学习的影响。我们证明，模型确实会在上下文窗口中学习到预测中的长度偏差，并进一步实证分析了影响模型偏差程度的因素。此外，我们还表明，通过上下文学习长度信息可以用来对抗模型中已经编码的长度偏差（例如，通过微调）。这揭示了上下文学习在不需昂贵的参数更新情况下，对去偏模型预测行为的强大能力。

> Large language models have demonstrated strong capabilities to learn in-context, where exemplar input-output pairings are appended to the prompt for demonstration. However, existing work has demonstrated the ability of models to learn lexical and label biases in-context, which negatively impacts both performance and robustness of models. The impact of other statistical data biases remains under-explored, which this work aims to address. We specifically investigate the impact of length biases on in-context learning. We demonstrate that models do learn length biases in the context window for their predictions, and further empirically analyze the factors that modulate the level of bias exhibited by the model. In addition, we show that learning length information in-context can be used to counter the length bias that has been encoded in models (e.g., via fine-tuning). This reveals the power of in-context learning in debiasing model prediction behaviors without the need for costly parameter updates.

[Arxiv](https://arxiv.org/abs/2502.06653)