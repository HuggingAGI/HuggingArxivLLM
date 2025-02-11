# Steel-LLM：从零到开源——打造以中文为核心的LLM探索之旅

发布时间：2025年02月10日

`LLM应用

这篇论文主要介绍了Steel-LLM的开发过程、模型架构设计、训练方法以及实际应用中的表现，属于语言模型的应用与开发实践，因此归类为LLM应用。` `语言模型`

> Steel-LLM:From Scratch to Open Source -- A Personal Journey in Building a Chinese-Centric LLM

# 摘要

> Steel-LLM 是一款从零打造的以中文为核心的开源语言模型，旨在突破计算资源限制，打造高质量开源模型新标杆。该项目于2024年3月正式推出，致力于通过大规模数据集训练10亿参数级模型，同时秉持开放透明的态度，分享实用经验，助力社区共同进步。训练过程中，我们着重使用中文数据，辅以少量英文数据，填补现有开源LLMs空白，详尽记录并分享了完整的模型构建过程。在CEVAL和CMMLU等权威评测中，Steel-LLM表现优异，超越了多家大型机构的早期模型。本文将全面梳理项目核心贡献，包括数据采集、模型架构设计、训练方法论以及开发过程中的关键挑战，为致力于开发自有LLMs的研究者和实践者提供宝贵参考。模型权重和训练代码已开源，详情请访问https://github.com/zhanshijinwat/Steel-LLM。

> Steel-LLM is a Chinese-centric language model developed from scratch with the goal of creating a high-quality, open-source model despite limited computational resources. Launched in March 2024, the project aimed to train a 1-billion-parameter model on a large-scale dataset, prioritizing transparency and the sharing of practical insights to assist others in the community. The training process primarily focused on Chinese data, with a small proportion of English data included, addressing gaps in existing open-source LLMs by providing a more detailed and practical account of the model-building journey. Steel-LLM has demonstrated competitive performance on benchmarks such as CEVAL and CMMLU, outperforming early models from larger institutions. This paper provides a comprehensive summary of the project's key contributions, including data collection, model design, training methodologies, and the challenges encountered along the way, offering a valuable resource for researchers and practitioners looking to develop their own LLMs. The model checkpoints and training script are available at https://github.com/zhanshijinwat/Steel-LLM.

[Arxiv](https://arxiv.org/abs/2502.06635)