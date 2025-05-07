# 面向6G天地空一体化网络的基于大语言模型的自我演进安全框架

发布时间：2025年05月06日

`LLM应用` `网络安全`

> An LLM-based Self-Evolving Security Framework for 6G Space-Air-Ground Integrated Networks

# 摘要

> 最近出现的6G天地一体化网络（SAGINs），整合了卫星、空中网络和地面通信，为各种移动应用提供了无处不在的覆盖。然而，SAGINs的高度动态性、开放性和异构性带来了严峻的安全问题。构建SAGINs的防御体系面临两个初步挑战：1）准确理解海量非结构化多维威胁信息，以生成抵御各种恶意攻击的防御策略；2）迅速适应潜在未知威胁，从而产生更有效的安全策略。

为了解决上述两个挑战，我们提出了一种基于大型语言模型（LLMs）的新型SAGINs安全框架，该框架由两个关键组件LLM-6GNG和6G-INST组成。我们提出的LLM-6GNG利用了精炼的链式推理（CoT）和动态多智能体机制，用于分析海量非结构化多维威胁数据并生成全面的安全策略，从而解决第一个挑战。我们提出的6G-INST依赖于一种新型的自我演进方法，能够自动更新LLM-6GNG，使其适应动态通信环境下的未知威胁，从而解决第二个挑战。

此外，我们使用ns-3、OpenAirInterface（OAI）和软件定义无线电（SDR）对提出的框架进行了原型化。在三个基准上的实验验证了我们框架的有效性。结果表明，我们的框架能够生成高度准确的安全策略，并且在面对各种未知攻击时表现得非常稳健。我们将开源我们的代码，以回馈社区。

> Recently emerged 6G space-air-ground integrated networks (SAGINs), which integrate satellites, aerial networks, and terrestrial communications, offer ubiquitous coverage for various mobile applications. However, the highly dynamic, open, and heterogeneous nature of SAGINs poses severe security issues. Forming a defense line of SAGINs suffers from two preliminary challenges: 1) accurately understanding massive unstructured multi-dimensional threat information to generate defense strategies against various malicious attacks, 2) rapidly adapting to potential unknown threats to yield more effective security strategies. To tackle the above two challenges, we propose a novel security framework for SAGINs based on Large Language Models (LLMs), which consists of two key ingredients LLM-6GNG and 6G-INST. Our proposed LLM-6GNG leverages refined chain-of-thought (CoT) reasoning and dynamic multi-agent mechanisms to analyze massive unstructured multi-dimensional threat data and generate comprehensive security strategies, thus addressing the first challenge. Our proposed 6G-INST relies on a novel self-evolving method to automatically update LLM-6GNG, enabling it to accommodate unknown threats under dynamic communication environments, thereby addressing the second challenge. Additionally, we prototype the proposed framework with ns-3, OpenAirInterface (OAI), and software-defined radio (SDR). Experiments on three benchmarks demonstrate the effectiveness of our framework. The results show that our framework produces highly accurate security strategies that remain robust against a variety of unknown attacks. We will release our code to contribute to the community.

[Arxiv](https://arxiv.org/abs/2505.03161)