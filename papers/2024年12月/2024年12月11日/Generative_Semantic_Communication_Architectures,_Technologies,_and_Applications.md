# 生成式语义通信：其架构、技术与应用

发布时间：2024年12月11日

`LLM应用` `人工智能`

> Generative Semantic Communication: Architectures, Technologies, and Applications

# 摘要

> 这篇论文深入探究了生成式人工智能（GAI）于语义通信（SemCom）中的应用，并展开了全面研究。先是介绍了由经典 GAI 模型赋能的三个热门 SemCom 系统，涵盖变分自编码器、生成对抗网络以及扩散模型。针对每个系统，都阐释了 GAI 模型的基本理念、对应的 SemCom 架构以及近期工作的相关文献综述。接着，借助前沿的 GAI 技术——大型语言模型（LLMs），提出了一种新颖的生成式 SemCom 系统。此系统在发射端和接收端均设有两个基于 LLM 的 AI 代理，分别充当“大脑”，以实现强大的信息理解和内容再生能力。这种创新设计让接收端能够依据发射端传达的编码语义信息直接生成所需内容，而非恢复比特流。故而，它将通信思路从“信息恢复”转变为“信息再生”，由此开启了生成式 SemCom 的新纪元。通过一个点对点视频检索的案例研究彰显了所提生成式 SemCom 系统的优越性，相较于传统通信系统，通信开销降低了 99.98%，检索准确率提升了 53%。此外，勾勒出了生成式 SemCom 的四个典型应用场景，随后探讨了三个有待未来研究的开放问题。简而言之，本文为在 SemCom 中应用 GAI 提供了一整套全面的指南，为未来无线网络中生成式 SemCom 的高效实现铺平了道路。

> This paper delves into the applications of generative artificial intelligence (GAI) in semantic communication (SemCom) and presents a thorough study. Three popular SemCom systems enabled by classical GAI models are first introduced, including variational autoencoders, generative adversarial networks, and diffusion models. For each system, the fundamental concept of the GAI model, the corresponding SemCom architecture, and the associated literature review of recent efforts are elucidated. Then, a novel generative SemCom system is proposed by incorporating the cutting-edge GAI technology-large language models (LLMs). This system features two LLM-based AI agents at both the transmitter and receiver, serving as "brains" to enable powerful information understanding and content regeneration capabilities, respectively. This innovative design allows the receiver to directly generate the desired content, instead of recovering the bit stream, based on the coded semantic information conveyed by the transmitter. Therefore, it shifts the communication mindset from "information recovery" to "information regeneration" and thus ushers in a new era of generative SemCom. A case study on point-to-point video retrieval is presented to demonstrate the superiority of the proposed generative SemCom system, showcasing a 99.98% reduction in communication overhead and a 53% improvement in retrieval accuracy compared to the traditional communication system. Furthermore, four typical application scenarios for generative SemCom are delineated, followed by a discussion of three open issues warranting future investigation. In a nutshell, this paper provides a holistic set of guidelines for applying GAI in SemCom, paving the way for the efficient implementation of generative SemCom in future wireless networks.

[Arxiv](https://arxiv.org/abs/2412.08642)