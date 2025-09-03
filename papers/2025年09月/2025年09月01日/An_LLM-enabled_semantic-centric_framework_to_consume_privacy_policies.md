# 基于LLM的语义中心框架：解析隐私政策

发布时间：2025年09月01日

`LLM应用` `法律科技`

> An LLM-enabled semantic-centric framework to consume privacy policies

# 摘要

> 如今，人们拥有大量在线账户，却极少阅读这些网站的服务条款或隐私政策——尽管嘴上说会看，根源在于理解这些条款实在太难。数据隐私实践的“迷雾”，给以用户为中心的网络模式、乃至智能体世界的数据共享与重用筑起了一道主要障碍。现有研究提出利用形式化语言和推理验证特定政策合规性，以此作为解决用户忽视隐私政策问题的潜在途径。但在大规模构建或获取这类形式化政策方面，仍存在关键瓶颈。

为此，我们提出一种以语义为核心的方案：借助最先进的大型语言模型（LLM），自动从隐私政策中提取隐私实践的关键信息，并构建【数学公式】——一种基于数据隐私词汇表（DPV）的隐私实践知识图谱，为下游任务提供支持。我们还基于该流程分析了排名前100的热门网站，其【数学公式】已作为公共资源一同发布。

此外，我们演示了如何通过【数学公式】构建形式化政策表示（如开放数字权利语言（ODRL）、长期语义数据使用条款（psDToU）等），进而赋能下游任务。为验证技术有效性，我们邀请法律专家制作定制注释，对Policy-IE数据集进行了扩充；同时测试了不同LLM在该流程中的性能表现，验证了其有效性。

综上，这些成果为在线服务隐私实践的大规模分析提供了新思路，有望成为审计网络与互联网的重要方向。我们已公开所有数据集和源代码，供研究复用与进一步优化。

> In modern times, people have numerous online accounts, but they rarely read the Terms of Service or Privacy Policy of those sites, despite claiming otherwise, due to the practical difficulty in comprehending them. The mist of data privacy practices forms a major barrier for user-centred Web approaches, and for data sharing and reusing in an agentic world. Existing research proposed methods for using formal languages and reasoning for verifying the compliance of a specified policy, as a potential cure for ignoring privacy policies. However, a critical gap remains in the creation or acquisition of such formal policies at scale. We present a semantic-centric approach for using state-of-the-art large language models (LLM), to automatically identify key information about privacy practices from privacy policies, and construct $\mathit{Pr}^2\mathit{Graph}$, knowledge graph with grounding from Data Privacy Vocabulary (DPV) for privacy practices, to support downstream tasks. Along with the pipeline, the $\mathit{Pr}^2\mathit{Graph}$ for the top-100 popular websites is also released as a public resource, by using the pipeline for analysis. We also demonstrate how the $\mathit{Pr}^2\mathit{Graph}$ can be used to support downstream tasks by constructing formal policy representations such as Open Digital Right Language (ODRL) or perennial semantic Data Terms of Use (psDToU). To evaluate the technology capability, we enriched the Policy-IE dataset by employing legal experts to create custom annotations. We benchmarked the performance of different large language models for our pipeline and verified their capabilities. Overall, they shed light on the possibility of large-scale analysis of online services' privacy practices, as a promising direction to audit the Web and the Internet. We release all datasets and source code as public resources to facilitate reuse and improvement.

[Arxiv](https://arxiv.org/abs/2509.01716)