# 训练小规模大型语言模型的计算瓶颈

发布时间：2024年10月25日

`LLM应用` `人工智能` `语言模型`

> Computational Bottlenecks of Training Small-scale Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）在 AI 领域独领风骚，但出于消费者对成本和效率的考量，小型大规模语言模型（SLMs）也开始备受关注。不过，针对 SLMs 的训练表现和计算需求的研究尚少。本研究通过考察包括 GPU 类型、批处理大小、模型大小、通信协议、注意力类型以及 GPU 数量等各类超参数和配置的影响，来探究训练 SLMs（参数高达 20 亿）的计算瓶颈。我们借助每美元损失和每秒令牌数等指标在热门云服务上对这些因素进行评估。我们的研究成果旨在助力低资源的人工智能研究所更广泛地采用和优化语言模型训练。

> While large language models (LLMs) dominate the AI landscape, Small-scale large Language Models (SLMs) are gaining attention due to cost and efficiency demands from consumers. However, there is limited research on the training behavior and computational requirements of SLMs. In this study, we explore the computational bottlenecks of training SLMs (up to 2B parameters) by examining the effects of various hyperparameters and configurations, including GPU type, batch size, model size, communication protocol, attention type, and the number of GPUs. We assess these factors on popular cloud services using metrics such as loss per dollar and tokens per second. Our findings aim to support the broader adoption and optimization of language model training for low-resource AI research institutes.

[Arxiv](https://arxiv.org/abs/2410.19456)