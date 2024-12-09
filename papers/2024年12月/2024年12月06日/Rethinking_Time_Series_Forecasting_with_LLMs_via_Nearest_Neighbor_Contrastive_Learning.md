# 借助最近邻对比学习，利用 LLMs 对时间序列预测进行重新思考

发布时间：2024年12月06日

`LLM应用` `时间序列预测`

> Rethinking Time Series Forecasting with LLMs via Nearest Neighbor Contrastive Learning

# 摘要

> 适应那些在海量文本数据上广泛训练的大型语言模型（LLMs），并定制输入提示以实现时间序列预测，这一研究已备受关注。尽管近期工作展现出了适应LLMs所学先验知识的巨大潜力，但用于微调LLMs的提示制定仍具挑战，毕竟提示需与时间序列数据相契合。而且，当下的方法无法有效利用体现LLMs所学到的丰富表示空间的词标记嵌入。这凸显出需要一种强有力的方法来构建提示，既要利用词标记嵌入，又要有效呈现时间序列的特性。为应对这些挑战，我们提出了NNCL-TLLM：基于LLMs的时间序列预测的最近邻对比学习。首先，我们生成与时间序列兼容的文本原型，使每个文本原型通过端到端微调，同时兼具其邻域中的词标记嵌入和时间序列特征。接下来，我们从最近邻对比学习中获取灵感来制定提示，同时获取前k个最近邻的时间序列兼容文本原型。随后，我们对LLM的层归一化和位置嵌入进行微调，保持其他层不变，从而减少可训练参数并降低计算成本。我们的综合实验表明，NNCL-TLLM在少样本预测中表现出众，在长期和短期预测任务中，其性能与最先进的方法相比具有竞争力或更优。

> Adapting Large Language Models (LLMs) that are extensively trained on abundant text data, and customizing the input prompt to enable time series forecasting has received considerable attention. While recent work has shown great potential for adapting the learned prior of LLMs, the formulation of the prompt to finetune LLMs remains challenging as prompt should be aligned with time series data. Additionally, current approaches do not effectively leverage word token embeddings which embody the rich representation space learned by LLMs. This emphasizes the need for a robust approach to formulate the prompt which utilizes the word token embeddings while effectively representing the characteristics of the time series. To address these challenges, we propose NNCL-TLLM: Nearest Neighbor Contrastive Learning for Time series forecasting via LLMs. First, we generate time series compatible text prototypes such that each text prototype represents both word token embeddings in its neighborhood and time series characteristics via end-to-end finetuning. Next, we draw inspiration from Nearest Neighbor Contrastive Learning to formulate the prompt while obtaining the top-$k$ nearest neighbor time series compatible text prototypes. We then fine-tune the layer normalization and positional embeddings of the LLM, keeping the other layers intact, reducing the trainable parameters and decreasing the computational cost. Our comprehensive experiments demonstrate that NNCL-TLLM outperforms in few-shot forecasting while achieving competitive or superior performance over the state-of-the-art methods in long-term and short-term forecasting tasks.

[Arxiv](https://arxiv.org/abs/2412.04806)