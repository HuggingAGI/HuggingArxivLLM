# MoLoRec：通用高效的大语言模型推荐框架

发布时间：2025年02月12日

`LLM应用` `推荐系统` `电子商务`

> MoLoRec: A Generalizable and Efficient Framework for LLM-Based Recommendation

# 摘要

> 大型语言模型（LLMs）凭借强大的泛化能力和丰富的知识储备，在近年来取得了显著的成功。为了充分发挥其作为推荐系统的潜力，现有研究主要围绕两大范式展开。第一种范式通过设计多领域或多任务指令数据实现通用化推荐，使LLMs与通用推荐领域对齐，从而有效处理冷启动推荐问题。第二种范式则借助参数高效微调技术优化特定领域的推荐任务，以提升模型在暖推荐场景下的性能表现。

与以往将这两个范式孤立研究的做法不同，我们认为它们各具优势，有机结合将带来更好的推荐效果。为此，我们提出了一种通用且高效的基于LLM的推荐框架MoLoRec。该框架首先通过通用推荐指令数据对领域通用模块进行参数高效微调，使LLM与推荐知识实现深度对齐。随后，基于特定领域的用户行为数据，我们构建领域特定指令数据集并对预训练的LLM进行高效微调。最后，通过参数混合方法将领域通用模块与领域特定模块进行有机整合。

值得注意的是，MoLoRec具有高效的即插即用特性：领域通用模块只需训练一次，而任何领域特定插件只需通过领域特定微调即可高效融合。通过在多个数据集上的广泛实验，涵盖暖推荐和冷启动推荐场景，我们验证了所提出的MoLoRec框架在推荐效果和适用范围上的显著优势。

> Large Language Models (LLMs) have achieved remarkable success in recent years, owing to their impressive generalization capabilities and rich world knowledge. To capitalize on the potential of using LLMs as recommender systems, mainstream approaches typically focus on two paradigms. The first paradigm designs multi-domain or multi-task instruction data for generalizable recommendation, so as to align LLMs with general recommendation areas and deal with cold-start recommendation. The second paradigm enhances domain-specific recommendation tasks with parameter-efficient fine-tuning techniques, in order to improve models under the warm recommendation scenarios. While most previous works treat these two paradigms separately, we argue that they have complementary advantages, and combining them together would be helpful.
  To that end, in this paper, we propose a generalizable and efficient LLM-based recommendation framework MoLoRec. Our approach starts by parameter-efficient fine-tuning a domain-general module with general recommendation instruction data, to align LLM with recommendation knowledge. Then, given users' behavior of a specific domain, we construct a domain-specific instruction dataset and apply efficient fine-tuning to the pre-trained LLM. After that, we provide approaches to integrate the above domain-general part and domain-specific part with parameters mixture. Please note that, MoLoRec is efficient with plug and play, as the domain-general module is trained only once, and any domain-specific plug-in can be efficiently merged with only domain-specific fine-tuning. Extensive experiments on multiple datasets under both warm and cold-start recommendation scenarios validate the effectiveness and generality of the proposed MoLoRec.

[Arxiv](https://arxiv.org/abs/2502.08271)