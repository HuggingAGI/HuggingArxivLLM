# GPT随行版：定制化训练基础模型也可以简单、可扩展且经济实惠

发布时间：2025年04月10日

`LLM应用`

> GPT Carry-On: Training Foundation Model for Customization Could Be Simple, Scalable and Affordable

# 摘要

> 现代大型语言基础模型 (LLM) 已经融入了数百万用户的日常生活。我们提出一个自然的问题：是否可以为每个用户或每个任务定制 LLM？从系统和工业经济的角度来看，一般的持续训练或微调仍然需要大量计算和训练 GPU 节点的内存，而大多数部署中的推理节点，可能配备低端 GPU，都配置为尽可能快速地完成前向传递。我们提出一个框架，充分利用现有 LLM 和在线服务系统。我们在预训练 LLM 的最终层嵌入上训练额外的 Transformer 层作为基础，然后通过一个延续模块将基础模型合并，组成一个定制化的 LLM。我们可以混合多个层次，或多个专注于不同领域的 LLM，例如聊天、编码、数学，形成一个最适合新任务的新混合 LLM。由于基础模型不需要更新参数，我们可以将训练任务的大部分计算外包到推理节点，并仅在训练节点上训练一个轻量级的延续模块。例如，我们在 30B 规模的 LLM 上训练一个 1 亿参数的延续层，仅消耗不到 1GB 的 GPU 内存。我们测试了 Qwen 和 DeepSeek 的开源模型进行持续预训练，取得了更快的损失收敛速度。我们将其用于解决数学问题，仅使用 1000 个链式思维数据样本和两个层延续模块（参数量仅为 1MB），取得了令人鼓舞的结果。

> Modern large language foundation models (LLM) have now entered the daily lives of millions of users. We ask a natural question whether it is possible to customize LLM for every user or every task. From system and industrial economy consideration, general continue-training or fine-tuning still require substantial computation and memory of training GPU nodes, whereas most inference nodes under deployment, possibly with lower-end GPUs, are configured to make forward pass fastest possible. We propose a framework to take full advantages of existing LLMs and systems of online service. We train an additional branch of transformer blocks on the final-layer embedding of pretrained LLMs, which is the base, then a carry-on module merge the base models to compose a customized LLM. We can mix multiple layers, or multiple LLMs specialized in different domains such as chat, coding, math, to form a new mixture of LLM that best fit a new task. As the base model don't need to update parameters, we are able to outsource most computation of the training job on inference nodes, and only train a lightweight carry-on on training nodes, where we consume less than 1GB GPU memory to train a 100M carry-on layer on 30B LLM. We tested Qwen and DeepSeek opensourced models for continue-pretraining and got faster loss convergence. We use it to improve solving math questions with extremely small computation and model size, with 1000 data samples of chain-of-thoughts, and as small as 1 MB parameters of two layer layer carry-on, and the results are promising.

[Arxiv](https://arxiv.org/abs/2504.07513)