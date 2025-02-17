# MoLoRec：通用高效的大语言模型推荐框架
发布时间：2025年02月12日

`推荐系统`
> MoLoRec: A Generalizable and Efficient Framework for LLM-Based Recommendation
>
> 大型语言模型（LLMs）凭借强大的泛化能力和丰富的知识储备，在近年来取得了显著的成功。为了充分发挥其作为推荐系统的潜力，现有研究主要围绕两大范式展开。第一种范式通过设计多领域或多任务指令数据实现通用化推荐，使LLMs与通用推荐领域对齐，从而有效处理冷启动推荐问题。第二种范式则借助参数高效微调技术优化特定领域的推荐任务，以提升模型在暖推荐场景下的性能表现。

与以往将这两个范式孤立研究的做法不同，我们认为它们各具优势，有机结合将带来更好的推荐效果。为此，我们提出了一种通用且高效的基于LLM的推荐框架MoLoRec。该框架首先通过通用推荐指令数据对领域通用模块进行参数高效微调，使LLM与推荐知识实现深度对齐。随后，基于特定领域的用户行为数据，我们构建领域特定指令数据集并对预训练的LLM进行高效微调。最后，通过参数混合方法将领域通用模块与领域特定模块进行有机整合。

值得注意的是，MoLoRec具有高效的即插即用特性：领域通用模块只需训练一次，而任何领域特定插件只需通过领域特定微调即可高效融合。通过在多个数据集上的广泛实验，涵盖暖推荐和冷启动推荐场景，我们验证了所提出的MoLoRec框架在推荐效果和适用范围上的显著优势。
>
> https://arxiv.org/abs/2502.08271

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.08271](https://arxiv.org/abs/2502.08271)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)