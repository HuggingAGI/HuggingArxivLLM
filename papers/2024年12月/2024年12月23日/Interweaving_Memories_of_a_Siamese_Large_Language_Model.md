# 连体大型语言模型的记忆交织

发布时间：2024年12月23日

`LLM应用` `语言模型` `参数优化`

> Interweaving Memories of a Siamese Large Language Model

# 摘要

> 参数高效微调（PEFT）方法通过修改或引入少量参数来优化大型语言模型（LLMs），以更好地适配下游任务。但这可能会引发灾难性遗忘，也就是 LLMs 会为了优先获取新知识，而舍弃全面的世界知识。要缓解这一问题，一个可行的办法是依据原始知识召回先前的记忆。基于此，我们提出了一个与模型无关的 PEFT 框架——IMSM，它能交织连体大型语言模型的记忆。具体而言，我们的连体 LLM 采用了现有的 PEFT 方法。当有传入的查询时，它会依据预训练和微调的参数生成两个不同的记忆。IMSM 还融入了一个交织机制，在生成下一个标记时调控原始记忆和增强记忆的贡献。这个框架理论上适用于所有开源 LLMs 和现有的 PEFT 方法。我们在众多基准数据集上开展了广泛的实验，将使用所提出的 IMSM 的热门开源 LLMs 的性能与经典及领先的 PEFT 方法进行对比评估。我们的发现表明，IMSM 与骨干 PEFT 方法在时间和空间效率方面相当，同时显著提升了性能，并有效减轻了灾难性遗忘。

> Parameter-efficient fine-tuning (PEFT) methods optimize large language models (LLMs) by modifying or introducing a small number of parameters to enhance alignment with downstream tasks. However, they can result in catastrophic forgetting, where LLMs prioritize new knowledge at the expense of comprehensive world knowledge. A promising approach to mitigate this issue is to recall prior memories based on the original knowledge. To this end, we propose a model-agnostic PEFT framework, IMSM, which Interweaves Memories of a Siamese Large Language Model. Specifically, our siamese LLM is equipped with an existing PEFT method. Given an incoming query, it generates two distinct memories based on the pre-trained and fine-tuned parameters. IMSM then incorporates an interweaving mechanism that regulates the contributions of both original and enhanced memories when generating the next token. This framework is theoretically applicable to all open-source LLMs and existing PEFT methods. We conduct extensive experiments across various benchmark datasets, evaluating the performance of popular open-source LLMs using the proposed IMSM, in comparison to both classical and leading PEFT methods. Our findings indicate that IMSM maintains comparable time and space efficiency to backbone PEFT methods while significantly improving performance and effectively mitigating catastrophic forgetting.

[Arxiv](https://arxiv.org/abs/2412.17383)