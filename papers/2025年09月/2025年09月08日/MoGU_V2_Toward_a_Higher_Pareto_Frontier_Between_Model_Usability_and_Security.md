# MoGU V2：致力于模型可用性与安全性的更高帕累托前沿

发布时间：2025年09月08日

`LLM应用` `基础理论`

> MoGU V2: Toward a Higher Pareto Frontier Between Model Usability and Security

# 摘要

> 随着大型语言模型（LLMs）日益融入人类生活，其安全性已成为核心关切，尤其是它们面对恶意指令时能否保持无害响应的能力。尽管大量方法提升了LLMs的安全性，但往往导致保守的、以拒绝为主的响应，进而影响实际可用性。这带来了一个关键挑战：如何推进LLMs可用性与安全性之间的帕累托前沿，而非在两者间进行权衡。为此，我们提出MoGU框架，其中层内路由器通过感知隐藏状态动态分配权重，以平衡安全优化和可用性优化变体的贡献。尽管MoGU框架具有初步潜力，但仍存在参数冗余和性能瓶颈等局限。为克服这些问题，我们进一步提出改进的MoGU_v2框架，在路由器与隐藏状态间建立更紧密的耦合。在MoGU_v2中，路由器仅嵌入编码高度可分类安全特征的层，且骨干模块在路由器优化期间被激活以实现双向适应。MoGU_V2在各类LLMs中展现出强大适应性和稳定改进，包括在各类应用中作为核心的主流LLMs、针对资源受限场景优化的设备端LLMs，以及为用户可解释性定制的推理LLMs。同时，即便面临指令微调带来的风险，MoGU_v2也能通过简单的数据混合策略轻松恢复安全性，且不损害任务性能增益。这些全面改进表明，MoGU_V2是缓解现实应用中安全风险的强大且多功能的解决方案。

> As Large Language Models (LLMs) increasingly permeate human life, their security has emerged as a critical concern, particularly their ability to maintain harmless responses to malicious instructions. Although extensive methods have improved LLMs' security, they often lead to conservative, rejection-oriented responses that compromise practical usability. This presents a key challenge: how to advance the Pareto frontier between LLMs' usability and security, rather than necessitate a trade-off between them. To address this, we propose the MoGU framework, in which the intra-layer router dynamically allocates weights by sensing hidden states, thereby balancing the contributions of security-optimized and usability-optimized variants. Despite its initial potential, the MoGU framework faces limitations such as parameter redundancy and performance bottlenecks. To overcome these, we further propose an improved MoGU_v2 framework that establishes a tighter coupling between the routers and hidden states. In MoGU_v2, routers are embedded only in layers encoding highly classifiable security features, and backbone modules are activated during router optimization to enable bidirectional adaptation. MoGU_V2 exhibits strong adaptability and stable improvements across various series of LLMs, including mainstream LLMs serving as brains in various applications, on-device LLMs optimized for resource-constrained scenarios, and reasoning LLMs tailored for user interpretability. Meanwhile, even facing risks introduced by Instruction Fine-tuning, MoGU_v2 can easily restore security without compromising the task performance gains via a simple data-mix strategy. These comprehensive improvements highlight MoGU_V2 as a robust and versatile solution for mitigating security risks in real-world applications.

[Arxiv](https://arxiv.org/abs/2509.06807)