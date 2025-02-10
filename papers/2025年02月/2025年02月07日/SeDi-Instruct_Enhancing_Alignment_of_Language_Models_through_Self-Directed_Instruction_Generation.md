# SeDi-Instruct：自驱式指令生成助力语言模型对齐优化

发布时间：2025年02月07日

`LLM应用

LLM应用

论文摘要：大型语言模型（LLMs）的快速发展推动了AI服务的广泛应用。指令微调被认为是将基础模型适配到目标领域、为客户提供高质量服务的关键。然而，指令微调的一个核心挑战在于获取高质量的指令数据。Self-Instruct通过使用ChatGPT API自动生成指令数据，缓解了数据稀缺性问题。为了进一步提高指令数据的质量，Self-Instruct会舍弃ChatGPT生成的许多指令，尽管这会因大量无用的API调用而造成成本上的低效。为此，我们提出了一种新颖的数据生成框架——Self-Direct Instruction generation（SeDi-Instruct），该框架采用了基于多样性的过滤和迭代反馈任务生成方法。基于多样性的过滤通过增强批次中指令的多样性，在不过多丢弃低质量生成指令的情况下，保持模型的准确性。这降低了合成指令数据的成本。迭代反馈任务生成将指令生成与训练任务相结合，并利用训练过程中获得的信息创建高质量的指令集。实验结果表明，与传统方法相比，SeDi-Instruct将AI模型的准确性提升了5.2%，同时将数据生成成本降低了36%。

LLM应用` `AI服务`

> SeDi-Instruct: Enhancing Alignment of Language Models through Self-Directed Instruction Generation

# 摘要

> 大型语言模型（LLMs）的快速发展推动了AI服务的广泛应用。指令微调被认为是将基础模型适配到目标领域、为客户提供高质量服务的关键。然而，指令微调的一个核心挑战在于获取高质量的指令数据。Self-Instruct通过使用ChatGPT API自动生成指令数据，缓解了数据稀缺性问题。为了进一步提高指令数据的质量，Self-Instruct会舍弃ChatGPT生成的许多指令，尽管这会因大量无用的API调用而造成成本上的低效。为此，我们提出了一种新颖的数据生成框架——Self-Direct Instruction generation（SeDi-Instruct），该框架采用了基于多样性的过滤和迭代反馈任务生成方法。基于多样性的过滤通过增强批次中指令的多样性，在不过多丢弃低质量生成指令的情况下，保持模型的准确性。这降低了合成指令数据的成本。迭代反馈任务生成将指令生成与训练任务相结合，并利用训练过程中获得的信息创建高质量的指令集。实验结果表明，与传统方法相比，SeDi-Instruct将AI模型的准确性提升了5.2%，同时将数据生成成本降低了36%。

> The rapid evolution of Large Language Models (LLMs) has enabled the industry to develop various AI-based services. Instruction tuning is considered essential in adapting foundation models for target domains to provide high-quality services to customers. A key challenge in instruction tuning is obtaining high-quality instruction data. Self-Instruct, which automatically generates instruction data using ChatGPT APIs, alleviates the data scarcity problem. To improve the quality of instruction data, Self-Instruct discards many of the instructions generated from ChatGPT, even though it is inefficient in terms of cost owing to many useless API calls. To generate high-quality instruction data at a low cost, we propose a novel data generation framework, Self-Direct Instruction generation (SeDi-Instruct), which employs diversity-based filtering and iterative feedback task generation. Diversity-based filtering maintains model accuracy without excessively discarding low-quality generated instructions by enhancing the diversity of instructions in a batch. This reduces the cost of synthesizing instruction data. The iterative feedback task generation integrates instruction generation and training tasks and utilizes information obtained during the training to create high-quality instruction sets. Our results show that SeDi-Instruct enhances the accuracy of AI models by 5.2%, compared with traditional methods, while reducing data generation costs by 36%.

[Arxiv](https://arxiv.org/abs/2502.04774)