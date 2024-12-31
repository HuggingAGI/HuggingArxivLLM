# 由大型语言模型赋能的多任务物理层网络

发布时间：2024年12月30日

`LLM应用` `无线通信` `人工智能`

> Large Language Model Enabled Multi-Task Physical Layer Network

# 摘要

> 人工智能（AI）的最新进展持续重塑着未来 6G 无线通信的格局。近来，大型语言模型（LLMs）的发展为有效提升不同物理层任务的性能和泛化能力提供了极具前景的途径。然而，现有的多数工作都是针对单个无线通信任务分别对专用的 LLM 网络进行微调。如此一来，执行多样的物理层任务便会带来极高的训练资源、内存占用和部署成本。为解决此问题，我们提出了一个基于 LLM 的多任务物理层网络，用单个 LLM 来统一多个任务。具体而言，我们首先提出了一个多任务 LLM 框架，对 LLM 进行微调，使其能同时进行多用户预编码、信号检测和信道预测。此外，还精心设计了多任务指令模块、输入编码器以及输出解码器，以区分多个任务，并让无线数据不同格式的特征适配 LLM 的特征。同时，还展示了数值模拟来验证所提方法的有效性。

> The recent advance of Artificial Intelligence (AI) is continuously reshaping the future 6G wireless communications. Recently, the development of Large Language Models (LLMs) offers a promising approach to effectively improve the performance and generalization for different physical layer tasks. However, most existing works finetune dedicated LLM networks for a single wireless communication task separately. Thus performing diverse physical layer tasks introduces extremely high training resources, memory usage, and deployment costs. To solve the problem, we propose a LLM-enabled multi-task physical layer network to unify multiple tasks with a single LLM. Specifically, we first propose a multi-task LLM framework, which finetunes LLM to perform multi-user precoding, signal detection and channel prediction simultaneously. Besides, multi-task instruction module, input encoders, as well as output decoders, are elaborately designed to distinguish multiple tasks and adapted the features of different formats of wireless data for the features of LLM. Numerical simulations are also displayed to verify the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2412.20772)